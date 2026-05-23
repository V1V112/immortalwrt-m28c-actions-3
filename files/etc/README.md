# `/etc` 覆盖目录

放在这里的文件会被复制到固件根文件系统中的 `/etc/...` 路径。

示例：

```text
files/etc/config/network
files/etc/config/wireless
files/etc/uci-defaults/99-custom
```
README.md 和 .gitkeep 会被 staging 脚本忽略。