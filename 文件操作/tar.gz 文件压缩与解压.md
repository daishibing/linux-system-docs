# tar.gz 文件压缩与解压

使用 `tar` 命令对 `.tar.gz` 文件进行压缩与解压

# 压缩文件

```shell
tar -czvf <file-name>.tar.gz <source>
```

参数说明：

- `-c`：创建压缩文件
- `-z`：使用 `gzip` 压缩
- `-v`：显示详细信息
- `-f`：指定压缩文件

# 解压文件

解压到当前目录：

```shell
tar -xzvf <file-name>.tar.gz
```

解压到指定目录：

```shell
tar -xzvf <file-name>.tar.gz -C <target-directory>
```

参数说明：

- `-x`：解压文件
- `-z`：通过 `gzip` 解压
- `-v`：显示详细信息
- `-f`：指定压缩文件
- `-C`：指定解压目录


