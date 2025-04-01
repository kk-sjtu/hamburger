# 汉堡网站项目

一个现代化的汉堡餐厅网站前端项目，使用React和Tailwind CSS构建，提供美观的用户界面和响应式设计。

主体框架来自油管博主Code Info，视频链接 [Create A Responsive Burger Website in React and Tailwind CSS | Step-By-Step Tutorial](https://www.youtube.com/watch?v=Yr74_n83ipQ)

![汉堡网站预览](/src/assets/result.png)


## 项目特点

- 🎨 **现代UI设计** - 使用Tailwind CSS实现的精美用户界面
- 📱 **完全响应式** - 在所有设备上都能完美展示
- 🚀 **高性能** - 基于Vite构建系统，提供快速的开发和生产体验
- 🧩 **组件化架构** - 使用React组件化开发，代码结构清晰
- 💫 **动画效果** - 精心设计的交互动画提升用户体验

## 技术栈

- [React](https://reactjs.org/) - 用户界面库
- [Vite](https://vitejs.dev/) - 下一代前端构建工具
- [Tailwind CSS](https://tailwindcss.com/) - 实用优先的CSS框架
- [Lucide React](https://lucide.dev/) - 美观的图标库

## 安装说明

确保你已安装Node.js (推荐v16.0.0或更高版本)

1. 克隆仓库
```bash
git clone <仓库URL>
cd hamburger
```

2. 安装依赖
```bash
npm install
```

3. 启动开发服务器
```bash
npm run dev
```

## 项目结构

```
src/
  ├── assets/       # 图片和其他静态资源
  ├── components/   # 可复用的UI组件
  │   ├── IconButton.jsx
  │   ├── Logo.jsx
  │   └── NavLink.jsx
  ├── sections/     # 页面主要部分
  │   ├── Header.jsx
  │   └── Hero.jsx
  ├── App.jsx       # 主应用组件
  └── main.jsx      # 应用入口点
```

## 使用方法

- 开发模式: `npm run dev`
- 构建生产版本: `npm run build`
- 预览生产构建: `npm run preview`
- 代码检查: `npm run lint`

## 功能特点

- **响应式导航栏** - 在移动设备上自动转换为汉堡菜单
- **动画效果** - 包括悬停效果和过渡动画
- **现代设计元素** - 使用渐变、模糊效果和阴影
- **订单跟踪** - 提供订单跟踪功能入口


