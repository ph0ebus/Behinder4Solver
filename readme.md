# Behinder4Solver

## Introduce

《系统性程序设计》结课设计

目前支持 Behinder4 中 default_aes 和 default_xor 传输协议的解密和暴力破解，主要用到了 Linux 的文件操作和多线程编程

## Get Start

编译，需要有 openssl 库，Linux上默认应该是有的

```bash
gcc main.c -o main -lcrypto -lssl -lpthread
```

执行，建议带上 `2>/dev/null` 参数，将报错信息重定向

```bash
./main 2>/dev/null
```