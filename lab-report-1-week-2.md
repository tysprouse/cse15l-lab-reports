# Tutorial for Incoming CSE15L Students

**Step 1: Installing VScode**
- Install VScode; can be done using this 
[Link](https://code.visualstudio.com/)
- Make sure you install the right version for your operating system
- When youopen VScode, it should look lik this:


![Image](https://lh6.googleusercontent.com/QYr6APHNod2bf6ocbH8VJYbPMszneMwkbQBWQldwrtzH4h_TWAaeYJPRTyaehj3246lW3nW5xlzyADYygTMfv95E4tKzSCmxj08_6QdZk1btAX3MpW_2jNJmeGDgphHFimv-qppi)


**Step 2: Remotely Connecting**

- Install OpenSSH using the directions in this 
[Link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
- Look up your course-specific account for CSE15L using this 
[Link](https://sdacs.ucsd.edu/~icc/index.php)
- Open a new terminal and enter "ssh " followed by your course-specific account login
- when prompted with whether you want to continue connecting, enter yes then when it asks you for your password, enter your password
- when complete, the terminal should look like this:

![Image](https://lh4.googleusercontent.com/vGDxMAhaPUiHYVFAnWfqzHxu4exzCHQKSnnY2CFXJToKIAYZrF4ff6acrGFPxi7qLO3M1QdTlN4yme25t02YQ386pnoF6K6-7m79B6bOtOVaplmnxIxjDNn6iLRJME9id0vg4Zbd)

**Step 3: Trying Some Commands**
- run some cammands from the terminal
- In the following example, the commands "ls" and "touch" were used to view the contents of the folder, create a new file, then re-view the contents to see the new file

![Image](https://lh5.googleusercontent.com/JMIczvulPHsiyjEqHOVLnHDsfQL_55UtGXkMom5Zm1E7FwQuOmJv6kCmvNHtdmPeg6w6t88WyNZGFkn4ledpT94WntATZCah7JPjcrlSVxONXXvn5-Np0JJunZXx5z1wZymOvImD)


**Step 4: Moving Files with scp**
- create a file named "WhereAmI.java" that prints the location of the file
- run the file using javac and java from the client (your computer)
- move the file to the server by typing in the terminal "scp WhereAmI.java (course-specific account):~/"
- log into ieng6 using ssh, navigate to the "WhereAmI.java" file, and run it again using javac and java
- When completed, the terminal should look similar to this:
![Image](https://lh3.googleusercontent.com/1Gc64RzAGreDe_jPCZTMeJdYgXmutQ_dPXX5HX2zDu3x1KNGEYWuphSkDSI3lWybIJcXyoin2IepL3zCby3VqqdD3poGWhCXa_surRsDBecl_WLBCjO8fIvy0fCJf6fYxu9Tlpq3)


**Step 5: Setting an SSH Key**
- To create keys, type "ssh-keygen" into the terminal
- If you're using Windows, see extra step here --> 
[Link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement#user-key-generation)
- Press enter when it asks for a passphrase and location to save the file
- When completed, the terminal should look similar to this: 

![Image](https://lh3.googleusercontent.com/JsY5Qpm-r72hqPzuDgmbBFiVn1eikIOWw4PypVF8j80PVG-NaQMsBi_7i8BVAn1S5zbLSw7ENeZ86-uec1rEv0-X813yhtYhRFpd-ehJYiky59wDn87Ew4OL55dCQUrXYOdUe7ZL)

- log into ieng6 then create a new directory named ".ssh" by using the command "mkdir .ssh", then log out
- back in the client terminal, type "scp /Users/(username)/.ssh/id_rsa.pub (course-specific account):~/.ssh/authorized_keys
- now you should be able to use ssh and scp without having to enter a password:
![Image](https://lh3.googleusercontent.com/00yrNxVvCJtqV8CzjGU4fDyG1r_d0ZwoCr0x3VJsu5sEMr6-0XnJun5bGNz0wdEx-mZxeTz-iLfXaCxjE0653hM559OqvH7mADb8VysAxs9pTTLghvoZapd69l8rOBoVf-FFsnFU)


**Step 6: Optimizing Remote Running**
- you can use quotations at the end of an ssh command to run additional commands from the remote server
- you can also use semicolons to run multiple commands in a single line
- example:
![Image](https://lh6.googleusercontent.com/_MsyvI2lz2g7syuXdKqm-5etd019tPWl8048_HOyjH2qhNbc_9lDZSQUCuRB-yL26PYnsnpyMipEjh1WHfO3Ba7q-icDpuW36cY0p_w0NCpysFmHo0RiQvSiGVY1BKhANxD-4r10)


