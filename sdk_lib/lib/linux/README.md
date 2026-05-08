# Linux SDK 库文件

请将以下海康SDK文件复制到此目录：

- libhcnetsdk.so
- libHCCore.so
- libcrypto.so.1.1
- libssl.so.1.1
- libPlayCtrl.so
- HCNetSDKCom/ 目录及其内容

## 环境配置

需要将库路径添加到 LD_LIBRARY_PATH：

```bash
export LD_LIBRARY_PATH=/path/to/HIK-django/sdk_lib/lib/linux:$LD_LIBRARY_PATH
```

文件下载地址：https://open.hikvision.com/download

下载"设备网络SDK"和"播放库SDK"
