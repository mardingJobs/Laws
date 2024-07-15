---
draft: true
---

本项目收集各类法律法规、部门规章、案例等，并将其按照章节等信息进行了处理。



### 手动贡献

 - 根据[法律法规模版](法律法规模版.md) 的格式，将法律法规放入 `法律法规` 文件夹下合适的位置
 - 在 `scripts` 目录下运行 `python database.py`（会自动更新 `sqlite` 内容）
 - 提交更改，并提 pr

### 自动脚本

`scripts` 目录下有一 `request.py` 脚本，支持从 [国家法律法规数据库](https://flk.npc.gov.cn) 爬取最新的法律法规。

在 `scripts` 目录下，执行以下指令

 - `python requessts.py` （脚本会自动处理，将新增法律加入列表以及合适的位置）
 - `python database.py` （会自动更新 `sqlite` 内容）


