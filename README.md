# ROV & Aerial Vehicle Dynamics, Control & INDI Bilingual Literature Reader

水下航行器（ROV/AUV）及多旋翼飞行器动力学建模、非线性模型预测控制（NMPC）与增量非线性动态逆（INDI）控制文献中英双语精读平台与全译资产库。

## 目录结构说明

- `index.html`：双语文献精读 Web 交互式阅读平台入口。支持中英文段落左右对照、专业词汇悬浮释义与图表联动查看。
- `css/`：
  - `reader.css`：阅读平台双栏排版、暗色/明亮高亮、学术公式与图表样式。
- `js/`：
  - `reader_app.js`：阅读器前端交互逻辑与术语库联动引擎。
  - `data_paper1.js`：论文 1（NMPC 与微分平坦控制对比）中英文段落及结构化数据。
  - `data_paper2.js`：论文 2（微型飞行器自适应增量非线性动态逆）中英文段落及结构化数据。
  - `data_paper3.js`：论文 3（水下特技作业 AUV Cuttlefish 姿态 INDI 控制）中英文段落及结构化数据。
- `images/`：论文高清插图、控制框图与矢量实验曲线资源。
- `master_vocab_cache.json`：控制科学与水下航行器专业术语双语对照与释义缓存库。
- `论文1_四旋翼敏捷飞行的NMPC与微分平坦控制对比研究_中文全译.md`：论文 1 独立 Markdown 完整译本。
- `论文2_微型飞行器姿态控制的自适应增量非线性动态逆_中文全译.md`：论文 2 独立 Markdown 完整译本。
- `论文3_基于增量非线性动态逆的水下特技作业AUV姿态控制_中文全译.md`：论文 3 独立 Markdown 完整译本。

## 使用方法

直接在任意现代浏览器中双击打开 `index.html` 即可使用完整交互式精读平台（无需搭建后台服务，纯前端静态化设计）。
