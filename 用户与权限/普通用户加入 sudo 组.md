# 普通用户加入 sudo 组

将普通用户加入 `sudo` 组，使其可以使用 `sudo` 执行需要管理员权限的命令

# 将用户加入 sudo 组

root 用户执行：

```shell
usermod -aG sudo <user-name>
```

参数说明：

- `usermod`：修改用户账户信息
- `-a`：追加（append），保留用户原来的附加组
- `-G`：指定用户的附加组

# 验证生效

注销并重新登录或重启系统，然后执行：

```shell
sudo whoami
```

> 输出 `root`，说明 `sudo` 权限正常


