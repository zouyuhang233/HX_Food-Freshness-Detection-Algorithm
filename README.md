# HX Food Freshness Detection Algorithm

海信冰箱气味/食材新鲜度识别上位机（HX4）发布版本归档。

## 版本目录

| 目录 | 版本 | 说明 |
| --- | --- | --- |
| [`V1.5/`](V1.5/) | HX4_V1.5 | Windows 64 位测试人员交付版：900 秒等待、S 阈值分段识别、16 项算法参数（`config/algorithm_v14.json`）。 |
| [`V2.0/`](V2.0/) | HX4_V2.0 | Windows 10/11 64 位版：原始电阻前后比值 + 前次状态，60 分钟单次结果、10 项算法参数（`config/algorithm_v20.json`）。 |

每个版本目录包含可执行程序 `HX4_Vx.x.exe`、`config/` 参数配置与 `说明文档/`，并附 `README.md` 与 `测试人员操作说明.txt`。运行时保持 exe 与 `config/` 同级，无需安装 Python。

> 注：本仓库使用 Git LFS 托管 `.exe` 大文件，克隆前请先安装 Git LFS（`git lfs install`）。
