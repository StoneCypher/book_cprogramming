# Professional C Programming: Framework and Plugin Design in C

I first met the C language 20 years ago. I have been working with C language for 12 years.
I have read several C programming books but the purpose of them is teaching how to start C programming.
There is no book about how to do C programming practically for real product.

Fortunately, I've learned good C programming skill when working for companies which had good C programmers and good development processes.

Also, I have seen how great C programmers develop large scale software from the Linux kernel source.

This document is part of what I have learned and seen.

For a student, this document will take one or two weeks. Please focus on how the C basics, such as function pointer, pointer, macro and etc, are used in the real product.

If you are already professional C programmer, you could compare the source of this document and your product. I would be happy if you find out something to be applied to your product.

Please let me know if you have any tips for practical C programming skill. Please register your tips in the ticket of this repository. I will write a document for it andd add here with your name.

*I am not a native English speaker. Please inform me if you find any broken English.*

* 1st version in Korean: Feb. 12 2019
    * Started translation: Feb. 23 2019
    * Finished translation: Mar. 12 2019

## INDEX

* [Error handling with goto](error_handle.md)
* [Make if-else short with branch table](long-if.md)
* [Make for-loop with macro](foreach.md)
* Implement framework and plugin
  * [Object programming in C: make cstring class with C](cstring.md)
  * [Introduction](interface.md)
  * [Implement unittest framework](unittest.md)
  * [Implement unittest for cstring](unittest_cstring.md)
  * [Make test case with macro](unittest_cstring2.md)
* Sample project: serial number generator
  * [Initial version](serial_step1.md)
  * [Implementation the framework and plugin for the serial number generator](serial_step2.md)

## TODO
