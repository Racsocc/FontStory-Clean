# FontStory

一个专业的字体展示和管理平台。

## 项目说明

这是FontStory项目的完全干净版本，拥有全新的Git历史记录，确保项目的纯净性。

## 功能特性

- 🎨 字体在线预览和动态调整
- 📱 完美的响应式设计
- 🌓 深色/浅色主题切换
- ⚡️ 字体分包加载，极速体验
- 🔒 完整的后台管理系统
- 📊 详细的系统日志记录
- 🛠 SEO优化设置支持

## 界面截图

![FontStory界面1](ui_screenshots/1_FontStory.png)
![FontStory界面2](ui_screenshots/2_FontStory.png)
![FontStory界面3](ui_screenshots/3_FontStory.png)
![FontStory界面4](ui_screenshots/4_FontStory.png)
![FontStory界面5](ui_screenshots/5_FontStory.png)
![FontStory界面6](ui_screenshots/6_FontStory.png)
![FontStory界面7](ui_screenshots/7_FontStory.png)
![支持页面](ui_screenshots/Support.png)

## 技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **后端**: PHP 7.4+
- **数据库**: SQLite 3
- **服务器**: Nginx/Apache

## 安装部署

### 系统要求
- PHP 7.4+
- SQLite 3
- Nginx 1.22+ / Apache
- 写入权限：database/, fonts/, logs/

### 安装步骤

1. 克隆项目
```bash
git clone https://github.com/Racsocc/FontStory-Clean.git
cd FontStory-Clean
```

2. 设置目录权限
```bash
chmod -R 755 .
chmod -R 777 database fonts logs
```

3. 初始化数据库
- 访问 admin/init_db.php 进行初始化

4. 登录后台
- 地址：admin/login.php
- 默认账号：fontstory
- 默认密码：fontstory123

## 项目结构

```
FontStory-Clean/
├── admin/              # 后台管理系统
├── css/               # 样式文件
├── js/                # JavaScript文件
├── includes/          # 核心文件
├── fonts/             # 字体文件存储
├── database/          # SQLite数据库
├── logs/              # 系统日志
├── ui_screenshots/    # 界面截图
└── index.php          # 首页
```

## 许可证

MIT License

## 作者

Racsocc - [GitHub](https://github.com/Racsocc)

## 项目历史

本项目采用完全干净的Git历史记录，确保代码库的纯净性和专业性。