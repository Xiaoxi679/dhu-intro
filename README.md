# DHU 指北 — 东华大学指北

一个由"新生事项"、《大学生活质量指北》、《上交生存手册》等启发的东华大学常见资料汇总项目。意在帮助新生了解校园生活、学业规划、社团组织等信息。

📖 **在线浏览**：https://xiaoxi679.github.io/dhu-intro/

---

## 本地运行

### 环境要求

- Python 3.8+
- pip

### 安装与启动

```bash
# 1. 安装依赖
pip install mkdocs-material

# 2. 启动本地预览
mkdocs serve
```

打开浏览器访问 `http://127.0.0.1:8000/`，修改 `docs/` 下的文件会自动刷新预览。

### 构建静态站点

```bash
mkdocs build
```

生成的 HTML 文件在 `site/` 目录中，可直接部署到任意静态服务器。

### 部署到 GitHub Pages

```bash
mkdocs gh-deploy
```

---

## 项目结构

```
├── mkdocs.yml          # MkDocs 配置文件（导航、主题、扩展）
├── overrides/          # 主题模板覆写（首页自定义）
│   └── main.html       # 首页 Hero + 透明导航栏
├── docs/               # 所有 Markdown 内容
│   ├── index.md        # 首页
│   ├── Q&A/            # 开学准备
│   ├── campus-life/    # 校园生活（食堂、宿舍、设施）
│   ├── academic/       # 学习指南（选课、资源）
│   ├── club/           # 社团与组织
│   ├── committee/      # 学生组织
│   ├── gohome/         # 家乡群
│   ├── computer.md     # 电脑选购指南
│   ├── pitfall.md      # 避坑指南
│   ├── future.md       # 未来规划
│   ├── health.md       # 身心健康
│   ├── transportation.md
│   └── acknowledgements.md
└── site/               # `mkdocs build` 生成的静态文件
```

---

## 贡献

> 欢迎所有形式的贡献！

- **没有 Git 经验**：在 [Discussions Ideas](https://github.com/Xiaoxi679/dhu-intro/discussions/categories/ideas) 提出你的想法！咱会帮助你上架
- **有 Git 经验**：对 `docs/` 下的文件 Pull Request，Merge 后即时上线
- **文件名**：请使用英文，不允许空格，用 `-` 代替
- **讨论**：前往 [Discussions](https://github.com/Xiaoxi679/dhu-intro/discussions)

---

## 参考与致谢

详见 [感谢与致谢](docs/acknowledgements.md) 页面。

## 免责声明

本站内容来源于网络和他人解答，由于回复的准确性无法保证，请仅作为参考并结合其他来源使用。
