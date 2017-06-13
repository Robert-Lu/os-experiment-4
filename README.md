# os-experiment-4

使用了 dirtycow.github.io 中的 cowroot 的解决方案。

将/usr/bin/passwd 进行修改，使其一旦运行，便产生 root shell。

将“touch /success”传递给修改后的 /usr/bin/passwd，达到创建目标文件的目的。
