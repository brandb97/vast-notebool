# VAST 流程文档

使用 uv 启动 JupyterLab，在浏览器中阅读 `vast.ipynb`：

```bash
cd /Users/lidongyan/Code/src/vast-notebook
uv run jupyter lab vast.ipynb
```

首次运行会自动创建 `.venv` 并安装 `pyproject.toml` 中的依赖，之后直接运行同一条命令即可。

JupyterLab 默认会打开浏览器。如果没有自动打开，复制终端显示的带 `token` 的完整链接到浏览器。

阅读完成后，在启动服务的终端按 `Ctrl+C`，根据提示确认关闭。
