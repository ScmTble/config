# 配置

### Git

```bash
#配置用户名
git config --global user.name "test"

#配置邮箱
git config --global user.email  abc@163.com
```

## Windows

### wsl2

- wsl.conf
    ```conf
    # /etc/wsl.conf

    [boot]
    systemd=true
    ```
    [示例](https://learn.microsoft.com/zh-cn/windows/wsl/wsl-config#example-wslconf-file)
    
- .wslconfig
    ```conf
    [wsl2]

    memory=4GB 

    processors=2
    ```
    [示例](https://learn.microsoft.com/zh-cn/windows/wsl/wsl-config#example-wslconfig-file)