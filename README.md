# octalArrayManip

A simple program to read in byte values from stdin in octal notation. Input bytes are separated by either spaces, newlines, or both.
Each pair of input bytes is assembled into 16-bit, little-endian words, and stored in an array.
Then, the memory contents in the array are printed in octal.