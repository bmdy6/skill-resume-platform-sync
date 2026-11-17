# 招聘平台简历同步

给 Agent 一份新版简历，一次更新 BOSS 直聘、前程无忧、智联招聘和猎聘的附件与在线资料。可以指定其中几个平台，也可以只更新附件。

## 在 Codex 使用

将本仓库的 [SKILL.md](SKILL.md) 安装到本机技能目录。以下命令以 macOS 或 Linux 为例。

```bash
git clone https://github.com/bmdy6/skill-resume-platform-sync.git
mkdir -p ~/.codex/skills/resume-platform-sync
cp skill-resume-platform-sync/SKILL.md ~/.codex/skills/resume-platform-sync/
```

在 Codex 输入 `$resume-platform-sync 用这份 PDF 更新四个平台的简历附件和在线资料`，并附上文件或给出本机路径。需要能访问本地文件和已登录求职账号的浏览器工具，技能优先使用 Ego Lite。遇到登录或验证码时，由你在浏览器里完成。

完成后会逐个平台列出附件状态、已回读的在线资料和待处理项。审核中的附件会单独标明。
