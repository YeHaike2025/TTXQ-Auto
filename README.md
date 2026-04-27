# TTXQ-Auto · 天天象棋自动对弈系统 · 项目站点

> 面向普通玩家的使用说明与演示视频

## 在线预览

部署后访问：`https://<你的 GitHub 用户名>.github.io/ttxq-auto/`

## 本地预览

```bash
# 任选一种
python -m http.server 8080
# 或
npx http-server . -p 8080
```

然后打开浏览器访问 `http://localhost:8080`。

## 内容

- `index.html` — 项目说明主页
- `assets/demo.mp4` — 演示视频（720p, 6.3 MB, H.264 + faststart）
- `assets/install-*.png` — 安装步骤截图

## 部署说明

仓库根目录即站点根目录。通过 GitHub Actions 自动部署：

1. 推送到 `main` 或 `master` 分支触发
2. Actions 会自动把整个仓库作为静态站点发布到 GitHub Pages

## 许可

仅供学习与研究使用。
