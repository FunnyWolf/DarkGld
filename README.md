# DarkGld
A tool for quickly generating fishing Trojan horse.

#### 介绍

项目是根据 [gld](https://github.com/darkb1rd/DarkGld.git) 进行二次开发的，**仅用于交流学习，禁止用于非法活动** 

#### 依赖

需要安装GO环境， 依赖库如下：

```
github.com/klauspost/cpuid
github.com/fatih/color
```

#### 命令

```
Usage of C:\Users\root\Desktop\temp\test\DarkGld.exe:
  -arch string
        target system architecture. x64/x86 , default: x64
  -file string
        file loaded into exe
  -icon string
        exe icon file path.
  -protect
        is Virtual machine detection required
  -shellcode string
        shellcode bin file. Example: shellcode.bin
  -uac
        is UAC permission required
```

#### 示例

`DarkGld.exe -shellcode beacon.bin -protect` 

#### 演示

