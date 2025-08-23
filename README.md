# 仓库管理系统

一个基于HTML、CSS和JavaScript的简单仓库管理系统，使用Tailwind CSS框架构建。

## 功能特点

- 工作记录管理（出库、入库、打包、装卸货）
- 物品清单管理
- 客户信息管理
- 员工信息管理
- 本地数据存储（使用浏览器localStorage）
- 响应式设计，支持移动端和桌面端
- 数据导入/导出功能

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件即可使用
2. 系统数据存储在浏览器中，清理浏览器数据前请先导出数据，否则数据会丢失
3. 可以通过导入 `.json` 文件来恢复数据，继续上一次记录

## 技术栈

- HTML5
- Tailwind CSS (通过CDN引入)
- Font Awesome (通过CDN引入)
- JavaScript (ES6+)

## 本地开发

```bash
# 克隆项目
git clone <repository-url>

# 进入项目目录
cd 仓库管理系统

# 使用npm启动本地服务器 (需要先安装Node.js)
npm start

# 或者直接使用Python启动本地服务器 (需要Python)
python -m http.server 8000

# 然后在浏览器中访问 http://localhost:8000
```

## 数据存储

数据存储在浏览器的localStorage中，导出数据会生成一个JSON文件，可以用于数据备份和迁移。

## 注意事项

- 清理浏览器数据前请先导出数据，否则数据会丢失
- 只要有数据.json文件就可以导入数据，继续上一次记录

## 许可证

[MIT](LICENSE) © 仓库管理系统