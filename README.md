# c_header_macro_generator
    Generate name of Macro which is used in C/CPP header file according to header file name.

# install
```
pip install antee-c_header_macro_generator
```

# how to use
```
from antee.c_header_macro_generator import get_macro_name

print(get_macro_name("abc.h")) # __ABC_H__ will be printed
```
