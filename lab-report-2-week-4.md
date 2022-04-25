## Lab Report 2 Week 4

**Fix #1**

![Image](https://lh6.googleusercontent.com/kw6Uy4zj99J0erBSgihrRT1HBOPExXH9cpBwAK4I3Uw7klaJSwebh4_IDpcZh0HuD4zG77Sv3GuFmCAyNMoW5Z9wcvNOAWyJTZ4uxLfZYi82TneSXNVuaV0pmhc3dygC_-FltRFO)

[Link to Failure-Inducing Input](https://github.com/tysprouse/markdown-parser/blob/main/test-file2.md)

![Image](https://lh5.googleusercontent.com/TF3DkBKqXwVaUvyG_AAp7jG9koy-F40F-E5pLcJJiuYuojJl8i4Wltpb4si-UxVPNz8F4YM4KWXFGcBS1SJFFnQ5cHVX9nawQOLT1HYvXAQrUzZ3yZ_2OThzmXYx3zp1wZ5UdY5q)  

The bug was that the program sees the open bracket and attempts to read further, but since there is nothing else in the file, an out of index error occurs. The error is caused because the program tries to evaluate the contents of the file at a non-existant index. 
