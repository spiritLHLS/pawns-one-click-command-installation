# iproyal-一键式命令安装
# pawns-一键式命令安装

## 介绍

iproyal 是一个允许用户通过分享流量来赚钱的平台。(被动收入)

您共享的 1G 流量将获得 0.20 美元，并且此脚本只支持家庭带宽以及类似的流量。

它具有以下特点：

1.根据系统自动安装docker，如果已经安装了docker，则不再安装。

2.根据架构自动选择和构建拉取的docker镜像，无需您手动修改官方案例安装。
    
3.使用Watchtower进行镜像自动更新，无需手动更新和重新输入参数。

(Watchtower 是一款实现自动化更新 Docker 镜像与容器的实用工具.它监控着所有正在运行的容器以及相关镜像,当检测本地镜像与镜像仓库中的镜像有差异时,会自动拉取最新镜像并使用最初部署时的参数重新启动相应的容器.)

### 信息

- 本项目已经在 AMD64 和 ARM 上验证上测试通过
- 感兴趣可以尝试一下，[注册链接点我](https://pawns.app?r=usdbonus), 走我链接注册你获得1刀的注册奖励。

## 安装

### 交互式安装

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/iproyal-one-click-command-installation/main/iproyal.sh -o iproyal.sh && chmod +x iproyal.sh && bash iproyal.sh
```

注册链接注册后，记住邮箱和密码，运行这个脚本，粘贴邮箱和密码，回车开始安装。

### 一键安装

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/iproyal-one-click-command-installation/main/iproyal.sh -o iproyal.sh && chmod +x iproyal.sh && bash iproyal.sh -m 你的邮箱 -p 你的密码
```

在此命令的中更改为你的账号邮箱和密码即可

## 卸载

```shell
bash iproyal.sh -u
```

卸载服务

### 经验

该平台不允许数据中心IP的流量，因此只能使用家庭带宽或类似带宽共享，也就是说服务器多半是挂不了的 (极少部分算得上家宽商宽的服务器可挂)

国内我用了一天0.05美元，我这网延迟和带宽不行，如果延迟和带宽好一点的网估计比上面那个收益高一点，不能用梯子挂，需要裸挂真实ip。

### 免责声明

本程序仅供学习了解, 非盈利目的，请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。

使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责.
