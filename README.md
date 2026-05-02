# WWlab HPC Bioinformatics & AI4Bio Manual

本仓库维护生物信息组 HPC 与 AI4Bio 软件使用手册。文档覆盖：

- HPC 使用规则、存储管理和任务提交；
- 基础生信命令行工具；
- 基因组学、比较基因组学和多组学分析；
- 单细胞、空间组学与 GPU 加速分析；
- 蛋白结构预测、蛋白设计、AI4Bio 大模型与多模态工具；
- 数据库、模型权重、常见错误和软件记录模板。

## 在线文档

推荐使用 MkDocs + Read the Docs 或 GitHub Pages 发布。源码位于 `docs/`。

本地预览：

```bash
pip install -r requirements-docs.txt
mkdocs serve
```

构建静态网页：

```bash
mkdocs build
```

## 维护原则

新增或更新公共软件时，请同步更新：

1. 软件用途；
2. 安装路径；
3. 环境名或容器；
4. 启动方式；
5. 最小测试命令；
6. 常用命令；
7. 数据库或模型权重路径；
8. 注意事项和维护记录。
