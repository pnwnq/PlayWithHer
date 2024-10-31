# 想和她一起玩 (PlayWithHer)

一款轻量级的社交活动平台，通过骰子元素和游戏化设计，让朋友之间更轻松愉快地组织和参与聚会活动。

## 主要特点

- **简洁清新的UI设计**：轻松愉快的视觉风格
- **无处不在的骰子元素**：从用户注册到活动创建，处处可见骰子，增添随机性和乐趣
- **悬浮骰子框**：用户打开app即可看到悬浮的骰子框，随时可用
- **简单小游戏**：3-5个趣味小游戏，包括猜数字、文字接龙、你画我猜等
- **简化的社交活动组织流程**：轻松创建和加入活动
- **用户颜色标识系统**：每个用户都有独特的颜色标识，方便识别
- **事件投票功能**：用户可以对感兴趣的事件进行投票，促进群体决策
- **智能群组加入机制**：基于时间范围和数字代号，轻松加入群组

## 技术栈

- **前端**: React Native + Expo + TypeScript
- **状态管理**: Redux Toolkit
- **实时通信**: Socket.IO
- **后端**: Node.js + Express
- **数据库**: MongoDB
- **文件存储**: AWS S3
- **推送通知**: Expo Notifications

## 开始使用

1. 克隆仓库：
```bash
git clone https://github.com/pnwnq/PlayWithHer.git
```

2. 安装依赖：
```bash
cd PlayWithHer
npm install
```

3. 启动开发服务器：
```bash
npm start
```

## 项目结构

```
src/
  ├── screens/           # 页面组件
  ├── components/        # 可复用组件
  ├── navigation/        # 路由导航
  ├── store/            # Redux状态管理
  ├── services/         # API服务
  ├── hooks/            # 自定义Hooks
  ├── utils/            # 工具函数
  └── assets/           # 静态资源
```

## 当前进展

- 完成技术栈评估和选型
- 确定项目架构和结构
- 设计核心功能模块
- 规划开发路线

## 下一步计划

1. 初始化React Native + Expo项目
2. 实现悬浮骰子基础功能
3. 实现基础UI框架
4. 实现基础游戏框架
5. TODO: 设计和实现主题系统

## 贡献

这是一个个人项目，主要用于自用和朋友间使用。如果您有任何海洋、天空主题或骰子玩法的创意，欢迎与我分享！

## 许可证

本项目采用 MIT 许可证。详情请见 [LICENSE](./LICENSE) 文件。

## 联系我们

- 项目维护者：pnwnq
- 项目主页：[https://github.com/pnwnq/PlayWithHer](https://github.com/pnwnq/PlayWithHer)

让我们一起，用骰子创造精彩的社交体验！🎲
