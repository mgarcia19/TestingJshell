# Repository for testing jshell

b = n;
|  Error:
|  incompatible types: possible lossy con
version from int to byte
|  b = n;
|      ^

C = n;
|  Error:
|  cannot find symbol
|    symbol:   variable C
|  C = n;
|  ^

## After Errors
   3 : int n = 68;
   4 : byte b = 127;
   5 : char c = 'B';
   6 : b = (byte)n;
   7 : c = (char)n;

