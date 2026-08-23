# 最后发布时需要什么

不需要把 GitHub 密码或 API Token 发给任何人。最终发布时只需要：

1. 你本人在浏览器或 GitHub CLI 的官方登录页面完成登录。
2. 确认 GitHub 用户名。
3. 确认仓库名与可见性。
4. 提供 Git 提交邮箱；如果不想公开真实邮箱，可使用 GitHub 提供的 `noreply` 邮箱。
5. 确认是否把 Windows 安装包作为 Release 附件上传。

推荐方案：

- 公开仓库：`personal-dictionary-desktop`，只包含当前展示材料。
- 私有仓库：`personal-dictionary-core-private`，保存完整源码与商业核心。
- GitHub Release：确认体验无误后再上传安装版，避免 README 与程序版本不一致。
