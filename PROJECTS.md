# Projects & Research Notes

## WaitingThreadInject
- **技术栈**：C / Win32 API / NtQuerySystemInformation / ZwWriteVirtualMemory
- **亮点**：自动筛选 WaitReason=WrQueue 的线程，栈返回地址重定向，shellcode 内嵌原始返回，执行后恢复。
- **下一步**：增加 APC 注入回退、ETW patchless 隐匿。

## BYOVD-终止进程
- **技术栈**：DeviceIoControl / Vulnerable Driver / IOCTL 0x22201C
- **亮点**：自动枚举设备对象，详细日志 + 进程验证。
- **下一步**：自定义驱动签名检测、跨平台封装。

## BeaconGuard (实验中)
- **技术栈**：Detours / Vectored Exception Handler / Memory Protection
- **亮点**：Hook VirtualAlloc/Sleep 捕获 Beacon，动态切换内存属性，利用异常恢复执行。
- **TODO**：增加 APC 在逃逸链，记录 Telemetry。

---

> 更多实时实验记录请关注博客或 Twitter；欢迎通过 Issue/PR 交流。
