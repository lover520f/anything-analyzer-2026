# Anything Analyzer v3.6.47

## 修复

- **工具调用空参数校验** — 拒绝 OpenAI Chat Completions 与 Responses API 返回的空字符串工具参数
  - OpenAI tool_call arguments 为空字符串时不再被当作空对象执行
  - Responses API function_call arguments 为空字符串时会在入站协议边界报错

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.47.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.47-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.47-x64.dmg |
| Linux | Anything-Analyzer-3.6.47.AppImage |
