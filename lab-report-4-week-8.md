# Lab Report 4


[Link to my repo](https://github.com/tysprouse/markdown-parser-echidnas.git)


[Link to the reviewed repo](https://github.com/fnriv/markdown-parser.git)


According to VScode Preview, the expected for each snippet is as follows:


- Snippet 1 test should return the list [%60google.com, google.com, ucsd.edu] *I don't know where the %60 comes from, but that is what the preview says*
- Snippet 2 test should return the list [a.com, a.com(()), example.com]
- snippet 3 test should return the list [https://www.twitter.com, https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule, https://cse.ucsd.edu/]


## My Implementation:
**Test Snippet 1**


![Image](https://lh3.googleusercontent.com/FpBaLdRpAuF0Qy8N0r3rSzYR3lhrQd5YufPaGcy6nW4mTNFZ07JFpop1kItE0SQfFvydMW4UUIwbpRP3plPHI5vbiolW9ZJJjSLzdwawgPdUmJfRHxEIfG33H2LlU1n6rRj7JJQW9pJRRQrn-w)


- Test Failed


![Image](https://lh4.googleusercontent.com/qUwP15YGF5GgnAZ_OdBVh8UgEdY01VXL_FYZj_hl_uSMtpLL_vTT8KxB_VxePk-H1fr_kPELKVXS6wEZHvrlgbyaaJh-ZTgxes6O71B-uqqJMwQeEotT625YY4T2NfwVeRcnBlcSgWTXlLI-DQ)


**Test Snippet 2**


![Image](https://lh6.googleusercontent.com/XfZDROcw9tEuBTquaKwhGY7K6ismQbAfbsqbpZ8P3QZSFd2UfouvIL1pifkdKwXi2-0bZY4bwbFWZ85NOb0SVCRP3z1JQElc_zCx2JenUy8yBbYMhxv7qh2wGGzaAWKMZRYRwaBPHViEzXFzcw)


- Test Failed


![Image](https://lh6.googleusercontent.com/uddU3IlKWBLZbUFR8lk3z8Zec9T1YyZe3cuoZb1sc-wqyjd_2R4TdKR4QdamujgkaAhGTNZixWZ_QJUwUiC2KjuXRXLKj_3KS0qNwYKQ_7Y5wFsfrbdTD8XVtTweypk85uFHnx9J8lEYv2jRsA)




**Test Snippet 3**


![Image](https://lh6.googleusercontent.com/9umY7QZlZAv3ZaWEnThe1JGHIf0bOvWMjDb_ydFWPOXH3HlV7on5-8lqfr5fdvAqMEiV2pG_POwCF6Q7x2zFiW2mFvzYfW5Xh7uo8x1neKG6PyNwF-U7M0PDMqG8YGFCQbuaTilplppFixqmGA)


- Test Failed


![Image](https://lh5.googleusercontent.com/O2keY7oOKwdR2_6P925fy4I9iibpzWnz5nw6HnCcIgRen7_wBsHJHuQVrVVIUkxnIzUm4JIzTbcjKtKDf82HuZ1g49hI9Pi2McYdfi4VJBBI0YqQn-DfHw9UdgRg0xtwLYSXppGiQrUoqJVXCQ)


## Reviewed Implementation:
**Test Snippet 1**


![Image](https://lh3.googleusercontent.com/DtDqxnfHChQWHpEIY7VDPRTRHhEZCfqTWCOaRmWnb5GEiSpsGYHWSpz1l3W9vWh54KcclkqNadTH7ULPjoOvdRPwKEznjSjb0ZxkaD_PfGgFquioxz4c5FZoYoiOLbTgCmFsv34Im6KL87WaGg)


- Test Failed


![Image](https://lh3.googleusercontent.com/yhD-J7iUsn3kVN2FMEyfQh37vW8AsEEwg-4D-Yuuq6nnaPnFlIw3ss_AYB7OT95Dq8_GTPLo19DeXkLcc9yqLzgjQK1rBUCrTRNY5gnv3AjupLHeBuv0fcserMCm5Xl8EJmV1fdc5iOQv3OnMw)


**Test Snippet 2**


![Image](https://lh4.googleusercontent.com/AsYbDg5Rt3xNhTtiHyZxK1qX0ho48zWeqjdGrMJKwm4cOl7M5z3C9RQOwHNF4p0YrGP3wNhDiCDOIc3IoN7eV-RcM2HCc03Pein_KnJyvkvbU596XPVnB_HmAqKOaSpOMe3_30fOtz318T-XXw)


- Test Failed


![Image](https://lh4.googleusercontent.com/RaC_xb-mYOTcfp2AbdfKI-eTeUBau1rtbjirUcHpXrYRBtDI2dIzTx973JzXpn2o5fabVDIpu2NdSfWhw1AYEArFfS7_DOWEoG0Gv0N5yEOohYoX8MibxJ4NzTUL89FLLg0QZnhr7YaIYIOzVA)


**Test Snippet 3**


![Image](https://lh5.googleusercontent.com/vzsco-mRapsSVK6OxW7yWISdoYwtCl7Ts7qSmwJXMg0nr89Hh7VR-6IN1OS5QJ2S9p0fw524o1hkhCvgbw88-hGR4pd-hLtaqkDidR28MSlwAr9M9vFHy-TMe0XcqXEU_JhaTRqAZHea_W3Aqg)


- Test Failed


![Image](https://lh5.googleusercontent.com/_qPCv0k80cWs3Zs2UU7dwxl4kSDTQ0sXbtrPjsrto4qic9VZOxcqd1MDUd-H9bVlUnF-nveJ1JF5of1obDkd1MEj1XsM4UDTuUCHgHpxMJbQoO8WweVhq-0_ZGlMF9qbZFFIk41Y4P1r6Y30CA)


## Answers
For snippet 1, there is a small (>10 line) fix that could make the implementation pass the test. Regarding specficially backticks, we could make a if statement, to check for and disregard backticks when parsing through a .md file. 


For snippet 2, there is not an easy, straight-forward fix. This is because the program must track the indices of brackets and parantheses in order to find where the link is. Furthermore, the VScode preview allows parentheses to exist within the linked url.


For snippet 3, there is not an easy, straight-forward fix for the same reason as snippet 2. Additionally, gaps between lines of text can cause the file reader to get stuck. So, when making the fix, we must make sure that it does not affect how the implementation handles gaps/newlines.


