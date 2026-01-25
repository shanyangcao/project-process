### ✅ 第 1 步：安装 Claude Code CLI（最关键）

1code **不自带 Claude**，它只是 UI。

#### 安装方式（官方）

```
npm install -g @anthropic-ai/claude-code
```

安装完成后，确认：

```
claude --version
```

能看到版本号就对了 ✅

------

### ✅ 第 2 步：准备 Claude API Key

你需要：

- Anthropic 的 API Key
- **不是 ChatGPT 的**

获取后记住这个 key。

------

### ✅ 第 3 步：在 1code 里配置

打开 1code → Settings（设置）里，检查 / 填：

- **Claude API Key**
- **Claude CLI Path**
  - 一般是自动识别的
  - 不行就手动填，例如：
    - macOS / Linux：`/usr/local/bin/claude`
    - Windows：`C:\Users\xxx\AppData\Roaming\npm\claude.cmd`

👉 保存