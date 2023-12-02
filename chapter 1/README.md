VALUES TYPES, AND OPERATORS

Inside the computer's world, there is only data. You can read data, modify data, create new data--but that which isn't data cannot be mentioned. All this data is stored as long sequence of bits and is thus fundamentally alike.
Bits are any kind of two valued things, usually described as zeros and one. Inside the computer, they take forms such as a high or low electrical charge, a strong or week signal, or shiny or dull spot on the surface of a CD. Any piece of discrete information can be reduced to a sequence of zeros and ones and thus represented in bits.
For example, we can express the number 13 in bits. It works the same way as a decimal number, but instead of 10 different digits, you have only 2, and the weight of each increases by a factor of 2 from right to left. Here are the bits that make up number 13, with the weights of the digits shown below them:

        0   0   0   0  1  1  0  1
      128  64  32  16  8  4  2  1

So that's the binary number 0001101. Its non-zero digits for 8, 4 and 1 and add up to 13.

VALUES

Imagine a sea of bits-- an ocean of them. A typical modern computer has more than 30 billion bits in its volatile data storage (working memory). Nonvalatile storage (the hard disk or equivalent) tends to have yet few orders of magnitude more.
To be able to work with such quantities of bits without getting lost, we must seperate them into chunks that represent pieces of information. In Javascript environment, those chunks are called values. Though all values are made of bits, they play different roles. Every value has a type that determines its role
