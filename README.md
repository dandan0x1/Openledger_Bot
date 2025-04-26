# Openledger_Bot 2.0
Openledger.xyz的项目

注册地址：https://testnet.openledger.xyz/?referral_code=swpstmlzqe

插件下载地址：https://chromewebstore.google.com/detail/openledger-node/ekbbplmjjgoobhdlffmgeokalelnmjjc

## 注意事件
openledger会获取粘贴板的所有权限，请在虚拟机下安装插件，或者安装插件获取了相关信息就停用或者卸载！

为什么我们还要运行呢？撸毛我们要有不放过任何一个项目的精神去做！

## 1、教程开始(注意这个教程是2.1的教程)
### 1.1、设置 accounts.json
登录上网站，里面有钱包地址
```json
[
    {
        "Address": "address1",
        "Token": "token1"
    },
    {
        "Address": "address2",
        "Token": "token2"
    }
]
```

![image](https://github.com/user-attachments/assets/10659500-1f13-428e-9dfc-279855e02fa4)


### 1.2、设置 proxy.txt
```txt
ip:port # 不加协议，默认使用http，protocol是你的协议头！正式使用请全部删除！
protocol://ip:port
protocol://user:pass@ip:port
```

### 1.3、设置proxy_config.json（代理池用户）
```json
{
    "ip": "192.168.2.7", #代理池ip
    "port_range": {
        "start": 50002,#开始端口
        "end": 50004 #结束端口
    },
    "max_ips": 2 #抓取最大ip数
}
```

## 2、运行脚本
### 2.1、Mac
```bash
wget url地址
unzip Openledger_Mac_2.0.zip
cd Openledger_Linux
chmod +x Openledger_Mac
./Openledger_Mac
```

### 2.2、Win
方法1：

双击Openledger.exe

方法2:
带日志
cmd到你的目录，然后输入 ``.\Openledger.exe``


### 2.3、Linux
```bash
wget url地址
unzip Openledger_Linux_2.0.zip
cd Openledger_Linux
chmod +x Openledger_Linux
./Openledger_Linux
```
