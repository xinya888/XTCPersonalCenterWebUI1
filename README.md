# XTC Personal Center WebUI Clone

高仿小天才 (XTC) 个人中心主页的 WebUI 前端项目。

## 项目简介
本项目通过前端技术还原小天才个人中心的界面，提供直观的可视化界面。支持自定义修改用户的个人资料，包括头像、头像框、背景、昵称等。

## 核心功能
* 界面可视化：还原小天才个人中心主页布局，素材全部直观展示。
* 自定义头像：支持上传或选择替换个人头像。
* 头像框更换：支持切换不同样式的头像框（ProfileFrame）。
* 背景切换：支持更换个人主页背景（Material/personalBackground2 等）。
* 昵称修改：支持点击修改用户昵称。
* 徽章墙展示：可视化展示已获得的徽章（BadgeWall）。
* 运动数据展示：可视化展示运动数据与进度（sport）。

## 目录结构
```text
├── PersonalCenter/          # 核心页面及素材目录
│   ├── BadgeWall/           # 徽章墙图片
│   ├── Material/            # 个人背景素材 (含男孩/女孩/节日等)
│   ├── Profile/             # 个人资料页素材
│   ├── ProfileFrame/        # 头像框素材
│   ├── home/                # 首页图标及背景
│   └── sport/               # 运动数据页素材
├── index.php                # 项目入口文件
└── ic_badge_select_bottom_bg.png # 徽章选择底图
