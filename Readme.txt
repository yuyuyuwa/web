人员信息管理系统 - 赛博朋克风格

项目说明：
这是一个基于Web的人员信息管理系统，具有赛博朋克风格的UI设计。
系统支持Excel文件上传、数据可视化、筛选和分页显示等功能。

功能特性：
- Excel文件上传和解析
- 数据统计和可视化图表
- 多条件数据筛选
- 分页显示数据表格
- 响应式设计，支持移动端

文件结构：
project/
├── index.html               # 主页面入口
├── Readme.txt               # 项目说明文档
├── css/
│   └── styles.css           # 全局样式文件
├── js/
│   └── app.js               # 主脚本逻辑文件
└── components/              # 页面组件目录
    ├── sidebar.html         # 侧边栏组件
    └── admin-section.html   # 管理员信息组件
└── dataset #数据集
    └── ***.xlsx #示例数据集

使用说明：
1. 打开 index.html 文件
2. 点击"上传Excel文件"按钮选择Excel文件
3. 系统将自动解析并显示数据统计和图表
4. 使用筛选功能可以过滤数据
5. 使用分页控件浏览数据

技术支持：
- 使用 Tailwind CSS 进行样式设计
- 使用 Chart.js 进行数据可视化
- 使用 SheetJS (xlsx) 进行Excel文件解析

注意事项：
- 请确保Excel文件格式正确
- 建议使用现代浏览器访问