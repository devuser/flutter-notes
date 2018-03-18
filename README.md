# flutter-notes

记录学习 `Flutter` 过程中的经验，笔记体。
本人开发环境在 `macOS` 下。

## 关于 Flutter

请查阅官网
[documentation](https://flutter.io/).

## 启动模拟器

```
open -a Simulator.app

```

## 运行

```
flutter packages get;flutter run
```

## FAQ

- Q: 找不到 `Device`
- A: 执行如下命令 `flutter devices` 查看当前链接的设备清单，
    选择其中之一比如 `EB51A0FC-1528-4738-AD44-2D1289A249D2`，执行如下命令
    `flutter packages get;flutter run -d EB51A0FC-1528-4738-AD44-2D1289A249D2`
