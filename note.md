# 问题解决记录

## PA0

1. nemu编译报错

    src/monitor/sdb/sdb.c:18:10: fatal error: readline/readline.h: No such file or directory

    > 解决方案

    ```shell
    sudo apt-get install libreadline-dev
    ```

    fatal error: llvm/MC/MCAsmInfo.h: No such file or directory

    > 解决方案

    ```shell
    sudo apt-get install llvm
    ```