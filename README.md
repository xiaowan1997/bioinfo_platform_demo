# BioinfoCloud v2.0 — GitHub Pages 静态多页面演示站

本项目是 **BioinfoCloud v2.0**（基于 NiceGUI + FastAPI + Celery + Snakemake 的生物信息学云分析平台）的 **纯静态多页面交互式演示站（Multi-Page Interactive Showcase）**。

与平台源码 [`frontend/pages/`](../../frontend/pages/) 保持 1:1 模块化镜像对应，支持点击侧边栏与卡片直接跳转到各个独立的分析流程表单！

---

## 📂 页面目录结构

```
gh_pages/
├── index.html                     # 首页 (河南中医药大学测序数据分析平台)
├── pages/
│   ├── history.html               # 历史任务管理中枢 (含状态筛选与操作)
│   ├── pipeline.html              # 8 大分析流程目录总览
│   ├── bulk_rnaseq.html           # Bulk RNA-Seq 标准转录组提交页 (含样本表格编辑)
│   ├── dnbc4tools_rna.html        # DNBC4tools RNA 单细胞转录组提交页
│   ├── dnbc4tools_atac.html       # DNBC4tools ATAC 单细胞染色质可及性提交页
│   ├── dnbc4tools_vdj.html        # DNBC4tools VDJ 单细胞受体库提交页
│   ├── sc_downstream.html         # scRNA Downstream 单细胞下游高级分析
│   ├── saw_count.html             # SAW Count Stereo-seq 空间转录组提交页
│   ├── saw_secondary.html         # SAW Realign / Reanalyze 空间重分析
│   ├── visualization.html         # 可视化分析中心 (内置 WebGL 交互火山图)
│   └── chat_biomni.html           # Chat-Biomni 生信多智能体问答
└── README.md                      # 本说明文档
```

---

## 💻 本地直接预览

你可以直接在本地电脑上双击 `index.html`，浏览器打开后点击任何侧边栏、卡片和按钮，都会如同真实部署的网站一样在各个子页面之间流畅跳转！
