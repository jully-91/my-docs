# my-docs：我的技术文档

这是我的 MkDocs 文档网站实践项目。网站包含首页、关于、使用指南和 API 参考四个页面，通过 GitHub Actions 自动构建并部署到 GitHub Pages。

- [访问公开网站](https://jully-91.github.io/my-docs/)
- [查看个人实验报告](report/README.md)

## 本地预览

在仓库根目录运行：

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m mkdocs build --strict
.\.venv\Scripts\python.exe -m mkdocs serve
```

打开终端显示的本地网址，检查完后按 `Ctrl+C` 停止预览。
