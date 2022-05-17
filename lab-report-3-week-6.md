# Lab Report 3

## Streamlining ssh Configuration

![Image](https://lh5.googleusercontent.com/myA_F-HsMLJw5Exk5FeqVGO6dpmKn_1LobHCpoeeYcdZvAA_Q2VbIj-EMjqJb6Cqr7VqMY8yOw9D7mi4KIYaA0KYRZ4HhUvQ6uFA6l8htSwkBa3f5_daOb8Yv1EWu3Mjw4eDBaAI3H-yEFHJvA)

- I created a new file named "Config" in my .ssh directory.
- Using Visual Studio Code, I added the three lines of text as shown in the screenshot.

![Image](https://lh4.googleusercontent.com/2PFu5gG8Cgw-KULP8aOETlV6pwzEvYeKjnmWEIaVtuXjGQBoIcBoMmLQvkyWNOmyw2hKVghn8deAE-AlAu69v8pJ7gllfElXpRy-vg40aueOwAFxzyiqsfChHYNYfOsiwqydXPt1GvQC04w50w)

- As we can see, I was able to login into my course-specific account on the remote server by simply typing "ssh ieng6".
- We can also see that logging in this way utilizes the ssh-keys we previously set up.

![Image](https://lh3.googleusercontent.com/3DHPrbne7ZNLhXCCM8EJ1bMkWorGRhBRMkdaVR3ufNkkc826dgeWYExtwnwFHDCtCMPjp_T6vWPCy9ja1TP22BqEzB7ZL9ZhU3_lV1mRIWA-z1FR_wPl6FELa_Y8D64ZhlCsqblaXinb8-4V2A)

- At the top of the screenshot we can see that Test.txt is a simple test file that contains the text "sample text".
- By typing "scp Test.txt ieng6: Test.txt", I copied Test.txt from my client to another file called "Test.txt" on the remote server using the nickname "ieng6".
- Then, I used the command "ls" to see that the file had indeed been copied over.
- Finally, I used the command "cat" to view the Test.txt file on the remote server and see that the contents are the same.


## Setup Github Access from ieng6

## Copy whole directories with scp -r

![Image](https://lh6.googleusercontent.com/5hgRxIFxdCmShJsgbHf3Wunx8uceaJwk5kycIm95jVgv9y6q6qo-geHLeRwpGWcGPZ0qOfF2JmoigttgI7ZUG4eale295O-pSgbJXdmkFi-xNydcD614SbGA1gppR8IbtV9LAXxCLEe-Lz1nig)

![Image](https://lh6.googleusercontent.com/630A_QmvED8xSQOstzYNl8bsE7Crt0oQodG9Fo5Ex5JlA_OEQdGfsyFtOckAq9KWs8e9iFCuPP_DaV5RGBVA82As3mTgiN-lFkGRe27iwLmMxoROMSZXkksNa8pVGKeEmwB2s1yun82j1i60tg)

- I first navigated to the "markdown-parser-echidnas" directory since it contained the latest version of our markdown parser files.
- By typing, "scp -r . ieng6:~/markdown-parse", I copied the current directory, which is the "markdown-parser-echidnas" directory.
- The copied directory was placed in a new directory on the remote server called "markdown-parse". 

![Image](https://lh3.googleusercontent.com/kOplCgihN640dgbx23EgPMX-qLMBai-X6LsTod39xsCZ5Pogo348XedIqdpCzPeKmt-fxWkLsvMBDWUyK4qQRhWGGIt8GNzZ9HMHuIhJb5LGM83LGMaCKM0wYoh9EVkmqiPAf2BcVRXpRuFe3Q)

- Then, I logged into the remote server and ran the "javac" and "java" commands to run the tests from the remote server.
- We can see that nine tests ran and all nine tests passed.

![Image](https://lh6.googleusercontent.com/9X2KeN0IbP2j5fkcs6LBA8JyPUUNUXlQywJP9UBaxwoj9yx4FnZNyJkWgrqQddWWlG5v8Wka_i4JjLbtY0H04Ie3BzCgu9wNmbAcGDc3Unw5R7QOj7GlFjuDOJhlOWVC60eIKpJ68A17mvELmg)  
When trying to combine commands to copy the directory and run the tests in the same line, I first deleted the directory from the remote server. I ran into a problem where the file in the above screenshot could not be deleted. Now, when I try to use the "scp -r" command to copy the directory, the terminal freezes when trying to copy the following file:
![Image](https://lh3.googleusercontent.com/a9oW5MbTHL0olGJrluOGvlx76wQHi-Fa69oh5bLttaYn9cBja2p7uB79qRFWybhk7Xmbhb2ZU7DuOxC2te5MnqPjvNcpifY3BcfO_bbGB-GVFJ1eMJ9nxHPstSs11qW5mx_S0830c3xCELg6yw)
