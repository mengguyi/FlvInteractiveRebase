# FlvInteractiveRebase

一个对 FLV 文件进行 Tag 级别编辑的命令行工具

## 用法

```bash
.\FlvInteractiveRebase.exe parse input.flv tags.xml

.\FlvInteractiveRebase.exe build tags.xml output.flv
```

## 编译

```bash
dotnet publish -c release -r win-x64
dotnet publish -c release -r osx-x64
dotnet publish -c release -r linux-x64
dotnet publish -c release -r linux-arm
```
