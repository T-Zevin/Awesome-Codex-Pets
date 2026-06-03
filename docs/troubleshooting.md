# 🧯 常见问题

## 宠物没有显示

检查：

- 目录是否放对。
- 是否存在 `pet.json`。
- 是否存在 `spritesheet.webp`。
- 文件名大小写是否正确。

## 宠物只显示一半

可能原因：

- sprite sheet 帧尺寸配置不匹配。
- 角色主体太靠近边缘。
- 单帧透明边距不足。

## 动画顺序不对

检查：

- `pet.json` 中的帧范围。
- 每行/每列帧数。
- 状态名称是否和 Codex 支持的状态一致。

## WSL / 路径问题

如果你在 WSL 或跨系统环境使用，请优先检查 pets 目录是否被 Codex 正确读取。

## 相关 issue

- WSL custom pets issue: https://github.com/openai/codex/issues/20730
- Half-cropped issue: https://github.com/openai/codex/issues/20828
- Interaction hooks issue: https://github.com/openai/codex/issues/21657
- Pet overlay issue: https://github.com/openai/codex/issues/20706

