# Huohuahua SDK

##  配置工程 

### 选择1：Cocoapods导入

#### 通过Cocoapods下载地址：

    pod 'Huohuahua'

### 选择2：手动导入
     导入 huohuahua.a和Huohuahua.h两个文件
    
### 调用说明
    ViewController：当前控制器
    token:平台登录令牌  （服务端返回）
    
    [Huohuahua skipAnHuohuahuaCashloan:ViewController andToken:token];
    
### 配置说明
    火花花项目用到了 定位、通讯录、相机权限，请在info配置权限，以免造成不必要的崩溃

