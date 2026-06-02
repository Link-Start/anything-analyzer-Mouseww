# Anything Analyzer v3.6.45

## 修复

- **OpenAI 工具调用状态输出校验** — 流式状态通知前先校验工具调用字段
  - 启用 `onChunk` 时，缺少 function name 的 tool_call 现在会返回明确协议错误
  - 避免畸形工具调用在工具状态文本拼接阶段退化成原生运行时异常

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.45.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.45-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.45-x64.dmg |
| Linux | Anything-Analyzer-3.6.45.AppImage |
