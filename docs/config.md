# ⚙️ 配置说明

## 标准文件

```text
pet.json
spritesheet.webp
```

## pet.json 常见字段

不同项目字段可能有差异，但通常会包含：

```json
{
  "name": "Example Pet",
  "version": "1.0.0",
  "author": "your-name",
  "description": "A custom Codex pet.",
  "spritesheet": "spritesheet.webp",
  "states": {}
}
```

## 常见动画状态

常见状态包括：

- `idle`
- `running`
- `running-left`
- `running-right`
- `waving`
- `jumping`
- `waiting`
- `review`
- `failed`

具体状态名称以 Codex 当前支持和宠物项目说明为准。

## 素材建议

- 使用透明背景。
- 每一帧大小保持一致。
- 不要让主体贴边，避免裁切。
- 预留 idle、running、waiting、failed 等基础状态。
- 发布前用本地 Codex 实际加载检查。

