# 🧪 制作自己的 Codex Pet

## 基本流程

1. 设计宠物形象。
2. 规划动画状态。
3. 生成或绘制 sprite sheet。
4. 编写 `pet.json`。
5. 放入 Codex pets 目录测试。
6. 调整帧数、速度、裁切和透明边距。

## 推荐先做的状态

- `idle`：静止待机
- `running-right`：向右移动
- `running-left`：向左移动
- `waiting`：等待任务
- `failed`：任务失败
- `waving`：打招呼

## Prompt 模板

```text
Create a cute pixel-art Codex desktop pet spritesheet.
The pet is a small bioinformatics lab assistant wearing a white coat.
It should include idle, running left, running right, waving, waiting, and failed states.
Use a transparent background, consistent frame size, clean silhouette, and readable animations.
```

更多 Prompt 见：[../prompts/](../prompts/)

