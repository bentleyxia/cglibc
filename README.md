Change glibc with custom compiled version.

```
Usage: cglibc [OPTIONS] BIN OUT

  Change the linked glibc of an ELF binary.

Options:
  --libc PATH  Custom libc path
  --ld PATH    Custom ld path
  --help       Show this message and exit.
```
  
Install:
```shell
    python -m build 
    pip install ./dist/cglibc-0.0.1-py3-none-any.whl
```

reference:
[Using a non-system glibc](https://www.ayrx.me/using-a-non-system-libc/)
