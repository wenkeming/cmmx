# CleanMyMac X

免费解锁(几乎)所有CleanMyMac X的功能！

更新至版本4.12.6(App Store)-英特尔芯片

不支持 M 系列芯片。

M 芯片的可参考 https://git.icrack.day/somebasj/CleanMyMacXCrack

## 如何使用

> 注意必须使用 python3

1. 克隆本仓库到任意位置
2. cd进克隆的目录 `CleanMyMacX`
3. 更改 `patch.py` 的执行权限：`chmod u+x patch.py`
4. 运行 `patch.py`：`sudo python ./patch.py`

输出结果:

```
$ sudo ./patch.py
Patching /Applications/CleanMyMac-MAS.app/Contents/MacOS/CleanMyMac-MAS...
Patching /Applications/CleanMyMac-MAS.app/Contents/Library/LoginItems/CleanMyMac-MAS Menu.app/Contents/MacOS/CleanMyMac-MAS Menu...
Re-signing /Applications/CleanMyMac-MAS.app...
/Applications/CleanMyMac-MAS.app: replacing existing signature
/Applications/CleanMyMac-MAS.app: valid on disk
/Applications/CleanMyMac-MAS.app: satisfies its Designated Requirement
Enjoy!
```

## TODO

- Parse Objective-C metadata
- Unlock missing features
- 隐藏菜单中的 `解锁完整版` 按钮
- 支持 Apple Silicon

## 提示

有问题建议删掉APP后从 `App Store` 重新下载，然后再执行。
