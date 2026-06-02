# Anything Analyzer v3.6.46

## 修复

- **Responses/Anthropic 工具调用状态输出校验** — 流式状态通知前先完成工具调用协议校验
  - Responses API 缺少 function_call name 时不会再提前输出工具调用状态
  - Anthropic/MiniMax 缺少 tool_use name 时不会再提前输出工具调用状态

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.46.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.46-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.46-x64.dmg |
| Linux | Anything-Analyzer-3.6.46.AppImage |
