## Lab Report 2 Week 4

**Fix #1**

![Image](https://lh6.googleusercontent.com/kw6Uy4zj99J0erBSgihrRT1HBOPExXH9cpBwAK4I3Uw7klaJSwebh4_IDpcZh0HuD4zG77Sv3GuFmCAyNMoW5Z9wcvNOAWyJTZ4uxLfZYi82TneSXNVuaV0pmhc3dygC_-FltRFO)

[Link to Failure-Inducing Input](https://github.com/tysprouse/markdown-parser/blob/main/test-file2.md)

![Image](https://lh5.googleusercontent.com/TF3DkBKqXwVaUvyG_AAp7jG9koy-F40F-E5pLcJJiuYuojJl8i4Wltpb4si-UxVPNz8F4YM4KWXFGcBS1SJFFnQ5cHVX9nawQOLT1HYvXAQrUzZ3yZ_2OThzmXYx3zp1wZ5UdY5q)  

The bug was that the program sees the open bracket and attempts to read further, but since there is nothing else in the file, an out of index error occurs. The error is caused because the program tries to evaluate the contents of the file at a non-existant index. 


**Fix #2**

![Image](https://lh6.googleusercontent.com/C68urnuCxNSU8F9EUd7KQs7d6K7vvqrJRW-OmaSAo4V_8_f2KD6gEqLdRrIL88N6pZoRPW38h1wFOJJDZZ9TgrT3bXlLTgVI8thUL5ChA2Yq1PSDoitBBXxZz6pvqD4yBN1AoFSc)

[Link to Failure-Inducing Input](https://github.com/tysprouse/markdown-parser/blob/main/test-file3.md)

![Image](https://lh5.googleusercontent.com/pYLyt2pcVSySjjMhysNJfqSjvBNFpyHJzOreqTxKSwG_N1E9wgAHGJsm7-0v8M1YYN2oCE8c_z6SA2M0Oyfv0Ll6pvrVRLeFM815T0VquJ4V0kSGNMvtDQ9BUw-GDeaB7fY8PJ0e)
