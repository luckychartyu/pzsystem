# 🏥 医院陪诊系统

> 基于 Vue 3 的现代化医院陪诊服务平台，包含用户端和管理端，提供完整的陪诊服务解决方案

## ✨ 项目特色

- 🏗️ **全栈解决方案**：涵盖 H5 用户端 + 后台管理系统
- 🎯 **企业级规范**：真实的业务场景和代码规范
- 🔐 **完整权限体系**：基于角色的菜单权限控制
- 📊 **数据可视化**：自动统计报表和订单状态管理
- 📱 **响应式设计**：完美适配移动端和桌面端

## 🚀 技术架构

### 前端技术栈
- **框架**: Vue 3.0 + Composition API
- **构建工具**: Vite (最新版)
- **路由**: Vue Router + 动态路由权限
- **状态管理**: Vuex + 持久化存储
- **UI 组件**: Element Plus（后台） + Vant (H5端)
- **HTTP 请求**: Axios + 拦截器封装
- **工具库**: Vuse

### 后端技术
- **运行环境**: Node.js v20+
- **接口管理**: Apifox 接口文档
- **数据校验**: 表单验证 + 输入保护

## 📱 系统功能模块

### H5 用户端 (C端)
- ✅ 用户注册/登录 (短信验证码)
- ✅ 陪诊服务浏览和选择
- ✅ 在线下单和支付集成
- ✅ 订单状态实时跟踪
- ✅ 个人中心管理

### 后台管理系统
- ✅ **权限管理**
  - 菜单权限分配
  - 角色权限控制
  - 动态路由加载
- ✅ **用户管理**
  - 账号内容配置
  - 用户信息维护
  - 批量操作功能
- ✅ **订单管理**
  - 订单全生命周期管理
  - 状态流转控制
  - 订单数据导出
- ✅ **数据统计**
  - 自动生成统计报表
  - 业务数据可视化
  - 首页数据看板

## 🏗️ 项目架构
pzadmin
src/
├── components/ # 公共组件
│ ├── treeMenu/ # 树形菜单
│ ├── navHeader/ # 导航头菜单
│ ├── pannelHead/ # 面板头菜单
│ └── aside/ # 侧边栏组件
├── views/ # 页面组件
│ ├── auth/ # 用户管理
│ ├── vppz/ # 订单管理
│ ├── login/ # 登录管理
│ └── dashboard/ # 数据看板
├── router/ # 路由配置
│ └── index.js # 路由守卫
├── store/ # 状态管理
├── api/ # 接口管理
├── utils/ # 工具函数
└── assets/ # 静态资源

pzH5

text

## 🚀 快速开始

### 环境要求
- Node.js >= 20.0.0
- npm >= 9.0.0

### 安装依赖
```bash
npm install
开发环境
bash
# 启动 H5 用户端
npm run dev

# 启动后台管理系统
npm run dev

🔧 核心功能实现
权限控制系统
基于用户角色的动态菜单生成

路由守卫实现页面访问控制

按钮级权限控制

订单状态管理
javascript
// 订单状态流转
const orderStatus = {
  PENDING: '待接单',
  ACCEPTED: '已接单', 
  IN_PROGRESS: '服务中',
  COMPLETED: '已完成',
  CANCELLED: '已取消'
}
数据统计报表
实时业务数据统计

图表数据可视化展示

数据导出和下载功能

📋 开发进度
已完成功能
项目基础架构搭建

路由配置和权限验证

用户登录和注册功能

菜单和账号管理系统

订单管理核心功能

数据统计报表

进行中功能
支付系统集成

消息通知系统

移动端优化

🤝 贡献指南
Fork 本仓库

创建特性分支: git checkout -b feature/AmazingFeature

提交更改: git commit -m 'Add some AmazingFeature'

推送到分支: git push origin feature/AmazingFeature

提交 Pull Request

📄 许可证
本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情

👥 开发团队
开发者

GitHub: @luckychartyu

