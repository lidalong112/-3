# auto green

每天由 GitHub Actions 自动提交一次，让 GitHub 主页贡献图保持绿色。工作流见 `.github/workflows/ci.yml`：每天 08:37（北京时间）左右触发，随机延迟 0–30 分钟，更新 GREEN.md 中的日期并提交。
