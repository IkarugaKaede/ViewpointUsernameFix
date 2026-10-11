# Viewpoint 中文用户名闪退修复

适用于 Project Zomboid Build 42 的 Viewpoint 模组。用于修复 Windows 用户名含中文等非英文字符时，加入世界后因字体加载失败而闪退的问题。

## 使用方法

1. 退出游戏和 Steam。
2. 下载本项目的 `mods` 文件夹。
3. 用其中的文件覆盖创意工坊 Viewpoint 模组目录：

   ```text
   <Steam库>\steamapps\workshop\content\108600\3809306528\mods\Viewpoint
   ```

4. 启动游戏，正常进入世界即可。

只需要替换以下文件；`tools` 文件夹无需复制：

```text
mods\Viewpoint\42\media\java\client\Viewpoint.jar
```

> 创意工坊更新模组后可能覆盖此修复，需要重新替换。
