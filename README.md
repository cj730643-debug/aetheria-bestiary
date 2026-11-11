# 艾瑟拉大陆生物图鉴

艾瑟拉大陆的动物、植物与大陆地理百科。项目记录原始物种、地方演化分支、生态关系、高清矢量插图和区域地图，不记录世界回合、种群数量或世界进度。

## 在线访问

https://cj730643-debug.github.io/aetheria-bestiary/

## 当前版本

**V1.2｜物种独立档案与交互地图**

- 首页提供物种视觉索引，每张物种卡片可进入独立档案页。
- 12张独立矢量图鉴插图，SVG格式，可在网页中无损缩放。
- 12个独立物种页面，展示对应插图和完整档案内容。
- 大陆地图支持点击北境、西境、中央、东境和南境，查看区域地理、气候、代表生物和生态特点。
- 保留此前的五大区域描述、河流水系、气候带、生态屏障和主要生态关系。
- 原始物种不被地方亚种或演化分支覆盖。

## 项目结构

- `index.html`：图鉴首页、物种视觉索引、交互式大陆地图、区域介绍和生态关系。
- `assets/species/`：每个物种独立的SVG矢量插图。
- `species/`：每个物种独立的详细档案页面。
- `README.md`：项目说明。

## 当前物种插图

| 编号 | 名称 | 插图文件 |
|---|---|---|
| 001 | 草蜥 | `assets/species/001-grass-lizard.svg` |
| 002 | 秃鹰 | `assets/species/002-vulture.svg` |
| 002-1 | 猎隼秃鹰 | `assets/species/002-1-hawk-vulture.svg` |
| 003 | 巨狼 | `assets/species/003-giant-wolf.svg` |
| 003-1 | 草原狼 | `assets/species/003-1-grass-wolf.svg` |
| 004 | 角背兽 | `assets/species/004-hornback.svg` |
| 005 | 霜叶草 | `assets/species/005-frostleaf.svg` |
| 006 | 迁徙角羊 | `assets/species/006-migratory-ram.svg` |
| 007 | 林地巨蛇 | `assets/species/007-forest-serpent.svg` |
| 008 | 深根牧草 | `assets/species/008-deeproot-grass.svg` |
| 009 | 沙丘跳兔 | `assets/species/009-dune-hare.svg` |
| 010 | 西境巨狮 | `assets/species/010-giant-lion.svg` |

## 地图说明

当前地图是世界观方位示意图，支持五大区域点击交互。下一阶段可继续细化大陆海岸线、山脉高度、河流源头、湖泊、岛屿、气候边界、迁徙路线和生态分布图层。新增地图细节时，应保持五大区域的相对方位一致。

## 数据口径

此前没有明确给出的生物参数，按世界观补充为图鉴设定值，属于可继续调整的虚构参数，不代表现实动物数据。地图为示意图，不是精确比例尺测绘图。后续以用户最新确认的设定为准。

## 本地预览与维护

下载或克隆仓库后，直接用浏览器打开 `index.html` 即可预览，无需安装依赖。后续新增生物时，新增对应SVG插图和 `species/` 独立页面，并更新首页视觉索引与地图资料。

## GitHub Pages

仓库 Settings → Pages：
- Source：Deploy from a branch
- Branch：`main`
- Folder：`/ (root)`

网站地址：https://cj730643-debug.github.io/aetheria-bestiary/
