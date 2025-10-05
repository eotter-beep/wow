# wow
Wow! is a compiler for compiling amazing software to python.

## Requirements

Install the parser dependency before running the tool:

```
 pip install pycparser
```

For full preprocessing support (so `#include` statements resolve to headers that pycparser understands), also install the lightweight header shim:

```
 pip install pycparser_fake_libc
```

Without the shim Wow! still works, but it falls back to a simplified preprocessing mode that only understands basic `#define` usage.

