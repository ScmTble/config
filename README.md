# 配置
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