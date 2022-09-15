#### Linux查看系统架构
```
lscpu
```

### Linux配置免密ssh
- 在.ssh/config文件中配置如下内容
```
Host 别名
    HostName 目标地址ip
    user 用户名
    IdentitiesOnly yes
```
- 生成秘钥
```
ssh-keygen -t rsa
ssh-keygen -t ed25519
```
- 传输秘钥
```
ssh-copy-id -i /秘钥地址/id_rsa.pub 用户名@ip
```
