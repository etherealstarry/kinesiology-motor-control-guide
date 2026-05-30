# Kinesiology Motor Control Learning Guide

运动控制与运动机能学自学指南 - 参考 [CS自学指南](https://csdiy.wiki/) 的风格，为Kinesiology专业Motor Control方向打造的系统学习资源网站。

## 项目简介

本项目旨在为运动机能学（Kinesiology）专业中对**运动控制（Motor Control）**方向感兴趣的学生和研究者提供系统性的学习资源指引。

项目参考了北大同学开发的 [CS自学指南](https://github.com/PKUFlyingPig/cs-self-learning) 的优秀经验，结合德州农工大学（Texas A&M University）运动机能学专业运动行为（Motor Behavior）方向的课程设置，整理出一套完整的学习路径。

## 网站特色

- ✅ **系统性**：按照德州农工大学官方课程设置组织内容
- ✅ **高质量**：收录顶尖大学和相关领域的优质开源课程资源
- ✅ **实践性**：包含实验设计、数据分析、科研方法等实践内容
- ✅ **前沿性**：涵盖运动控制领域的最新研究进展和应用
- ✅ **双语支持**：提供中英文学习资源

## 学习内容概览

### 基础课程
- 解剖学基础
- 生理学基础
- 运动机能学基础

### 核心课程
- 运动控制理论
- 运动学习
- 神经力学
- 生物力学
- 运动发育

### 研究方法
- 实验设计与统计
- 科研方法

### 研究方向
- 运动控制与学习
- 神经康复
- 生物力学应用
- 运动表现优化

### 学习工具
- 文献管理
- 数据分析工具（R/Python）
- 实验设备使用
- 学术写作

## 快速开始

### 在线访问

网站部署后可通过以下链接访问：
- 中文版：[https://kinesiology-motor-control.wiki/](https://kinesiology-motor-control.wiki/)
- GitHub仓库：[https://github.com/etherealstarry/kinesiology-motor-control-guide](https://github.com/etherealstarry/kinesiology-motor-control-guide)

### 本地运行

1. **安装依赖**

```bash
pip install -r requirements.txt
```

2. **启动本地服务器**

```bash
mkdocs serve
```

3. **访问本地站点**

打开浏览器访问：[http://127.0.0.1:8000](http://127.0.0.1:8000)

### 构建静态网站

```bash
mkdocs build
```

构建后的文件将位于 `site` 目录下。

## 项目结构

```
kinesiology-motor-control-guide/
├── docs/                          # 文档目录
│   ├── index.md                   # 首页
│   ├── 使用指南.md                # 使用指南
│   ├── 学习规划.md                # 学习规划
│   ├── 好书推荐.md                # 好书推荐
│   ├── 后记.md                   # 后记
│   ├── 必修课程/                  # 必修课程
│   │   ├── 基础课程/
│   │   │   ├── 解剖学基础.md
│   │   │   ├── 生理学基础.md
│   │   │   └── 运动机能学基础.md
│   │   ├── 核心课程/
│   │   │   ├── 运动控制理论.md
│   │   │   ├── 运动学习.md
│   │   │   ├── 神经力学.md
│   │   │   ├── 生物力学.md
│   │   │   └── 运动发育.md
│   │   └── 研究方法/
│   │       ├── 实验设计与统计.md
│   │       └── 科研方法.md
│   ├── 研究方向/                  # 研究方向
│   │   ├── 运动控制与学习.md
│   │   ├── 神经康复.md
│   │   ├── 生物力学应用.md
│   │   └── 运动表现优化.md
│   ├── 学习工具/                  # 学习工具
│   │   ├── 文献管理.md
│   │   ├── 数据分析工具.md
│   │   ├── 实验设备使用.md
│   │   └── 学术写作.md
│   └── 拓展资源/                  # 拓展资源
│       ├── 在线课程.md
│       ├── 学术会议.md
│       ├── 研究实验室.md
│       └── 实习与就业.md
├── overrides/                     # 主题自定义文件
│   └── partials/
├── mkdocs.yml                    # MkDocs配置文件
├── requirements.txt               # Python依赖
├── README.md                     # 本文件
└── LICENSE                       # 开源许可证
```

## 贡献指南

本指南是开源项目，欢迎贡献！

### 如何贡献

1. **Fork本仓库**
   
2. **创建你的分支**
   ```bash
   git checkout -b feature/your-feature
   ```

3. **提交你的修改**
   ```bash
   git commit -m "Add: 添加某课程内容"
   ```

4. **推送到分支**
   ```bash
   git push origin feature/your-feature
   ```

5. **提交Pull Request**

### 贡献内容

- 📚 **新增课程资源**：参考 `docs/必修课程/` 下的模板格式
- 📖 **推荐好书**：在 `docs/好书推荐.md` 中按照格式添加
- 🔧 **修正错误**：发现错误直接在GitHub提交Issue
- 🌟 **改进网站**：改进网站样式、功能等

### 课程文档模板

创建新课程文档时，请参考以下结构：

```markdown
# 课程名称

## 课程信息
- **课程代码**：XXXX
- **开设院校**：XX大学
- **课程难度**：⭐⭐⭐
- **建议学期**：第X学期
- **先修课程**：XXXX

## 课程简介

[课程内容简介]

## 学习目标

- 目标1
- 目标2
- ...

## 学习资源

### 主要教材
- [教材名称](链接) - 作者

### 推荐读物
- [读物名称](链接) - 作者

### 视频资源
- [视频链接](链接) - 说明

## 学习建议

[学习这门课程的建议和注意事项]

## 相关课程

- [相关课程1](链接)
- [相关课程2](链接)

## 贡献者

- 贡献者1
- 贡献者2
```

## 参考项目

本项目灵感来源于：

- **[CS自学指南](https://github.com/PKUFlyingPig/cs-self-learning)** - PKUFlyingPig开发的CS自学指南，73k+ Stars
- **[CS DIY Wiki](https://csdiy.wiki/)** - CS自学指南的在线阅读网站

## 许可证

本项目采用 [MIT License](LICENSE) 开源。

## 联系方式

- **GitHub Issues**：[提交问题或建议](https://github.com/etherealstarry/kinesiology-motor-control-guide/issues)
- **Pull Requests**：[贡献内容](https://github.com/etherealstarry/kinesiology-motor-control-guide/pulls)
- **Email**：欢迎发邮件交流

---

**让我们一起完善这个学习指南，帮助更多人学习运动控制！** 💪
