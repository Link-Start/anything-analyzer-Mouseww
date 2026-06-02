# Anything Analyzer v3.6.28

## 修复

- **OpenAI Chat 非流式响应格式校验** — 避免兼容服务缺少 `message.content` 时被误判为空成功结果
  - 普通 Chat Completions 请求现在会明确拒绝缺少 `message.content` 的 malformed choice
  - 工具调用最终文本轮次复用同一校验，保留工具调用中 `content` 为空的合法场景

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.28.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.28-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.28-x64.dmg |
| Linux | Anything-Analyzer-3.6.28.AppImage |
