# wow
Wow! is a compiler for compiling amazing software to python.

## Requirements

Install the parser dependency before running the tool:

```
 pip install pycparser
```

For richer header coverage (so `#include` statements resolve to headers that pycparser understands), also install the lightweight header shim:

```
 pip install pycparser_fake_libc
```

Wow! ships with its own pure-Python preprocessor that understands nested conditionals, object-like and function-like macros, and basic `#include` resolution. Installing `pycparser_fake_libc` simply gives the preprocessor more headers to pull from when expanding standard library includes.

