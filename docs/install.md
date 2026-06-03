# 🛠️ Codex 桌宠安装教程

## 1. 下载宠物包

一个标准 Codex Pet 通常至少包含：

```text
pet.json
spritesheet.webp
```

有些项目会额外提供：

```text
README.md
preview.gif
license
```

## 2. 检查目录结构

推荐结构：

```text
my-pet/
├── pet.json
└── spritesheet.webp
```

`pet.json` 负责描述宠物信息和动画状态，`spritesheet.webp` 是宠物动画素材。

## 3. 放到 Codex Pets 目录

不同系统和版本的路径可能不同。常见位置类似：

```text
~/.codex/pets/my-pet/
```

如果你的 Codex 设置里有自定义 pets 目录，请以本机设置为准。

## 4. 在 Codex 里启用

1. 打开 Codex。
2. 进入 Settings / Appearance / Pets。
3. 选择你的自定义宠物。
4. 回到 Codex 主界面。
5. 输入 `/pet` 唤醒桌宠。

## 5. 常见问题

- 看不到宠物：检查目录层级，不要多套一层文件夹。
- 动画错位：检查 `spritesheet.webp` 尺寸和 `pet.json` 帧配置。
- 图片裁切：检查每一帧是否留有透明边距。
- 无法加载：检查文件名是否严格为 `pet.json` 和 `spritesheet.webp`。

更多排错见：[troubleshooting.md](troubleshooting.md)

