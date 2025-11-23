# AI-Meal 
目前已支持通过 AI 推荐工作餐.

**中文** | **[English Documentation](README.md)**

AI-Meal 辅助大众不知道吃什么的问题。本项目使用 HTML + Tailwind CSS + JavaScript + Font Awesome（SVG 图标） + LocalStorage + OpenRouter API（AI 功能） + Noto Sans SC 字体 开发，拥有美观现代的界面设计。

**在线演示**: [https://eat.dawua.dpdns.org/](https://eat.dawua.dpdns.org/) - 立即体验！

## 🚀 功能特点

### 一、核心推荐功能
1. **心情导向选择**：提供4种情绪化菜品偏好入口（想吃辣、肉食爱好者、清淡/健康、随便），贴合用户即时用餐需求，降低决策成本。
2. **每日推荐限制**：每天默认3次推荐次数，避免过度纠结，次数耗尽后可通过更新菜单重置，兼顾实用性与引导性。
3. **结果交互优化**：推荐结果包含菜品名称、推荐理由、鼓励文案，支持“换一个推荐”或“确认选择”，不满意时可快速切换其他口味偏好。

### 二、菜单管理功能
1. **自定义菜单输入**：支持粘贴/输入食堂/餐厅菜单，自动识别菜品，形成个人专属菜单库，适配不同用餐场景（食堂、常去餐厅等）。
2. **菜单状态提示**：实时显示菜单相关状态（如菜品数量、是否可用），让用户清晰了解推荐基础数据。

### 三、智能与个性化配置
1. **AI 增强推荐**：配置 OpenRouter API Key 后，可启用 AI 智能推荐——结合心情和菜单内容精准匹配，无菜单时也能推荐通用工作餐。
2. **历史记录管理**：记录用户“确认选择”的菜品，支持查看用餐历史，避免重复推荐。
3. **灵活避让规则**：可设置“重复菜品避让天数”（0-30天）和“推荐过的菜品避让天数”（0-30天），自定义避免重复的强度，适配不同用户需求。

### 四、基础体验优化
1. **主题切换**：支持明/暗模式自动适配（跟随系统）或手动切换，适配不同使用场景和视觉偏好。
2. **状态反馈清晰**：包含加载中、推荐次数耗尽、历史菜品耗尽等状态提示，避免用户困惑。
3. **数据本地存储**：菜单输入内容、主题偏好、用餐历史等自动本地保存，无需重复操作，提升使用连贯性。

### 五、使用场景适配
- 核心场景：食堂就餐、固定餐厅用餐时的快速决策；
- 延伸场景：无明确菜单时（配置API Key后）的通用工作餐推荐；
- 适配设备：支持移动端/桌面端，界面响应式设计，操作流程简洁（单页交互，无需多页跳转）。

## 🛠️ 技术栈

- [HTML](https://developer.mozilla.org/zh-CN/docs/Web/HTML) - 网页内容结构基础语言
- [Tailwind CSS](https://tailwindcss.com) - 实用优先的CSS框架，快速构建响应式界面
- [JavaScript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript) - 网页交互逻辑核心语言
- [Font Awesome（SVG图标）](https://fontawesome.com) - 轻量可定制的矢量图标库
- [LocalStorage](https://developer.mozilla.org/zh-CN/docs/Web/API/Window/localStorage) - 浏览器本地数据存储方案
- [OpenRouter API](https://openrouter.ai) - 第三方AI模型调用接口，提供智能推荐能力
- [Noto Sans SC](https://fonts.google.com/specimen/Noto+Sans+SC) - 谷歌开源的中文无衬线字体，适配多场景显示

## 🧩 项目结构

```

```

## 🧪 开发指南

开发的步骤:

1. 在 `根目录` 创建新目录进行修改

## 🌍 贡献指南

欢迎贡献代码！请随时提交Pull Request。

1. Fork仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m '添加某项惊人功能'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 打开Pull Request

## 📄 许可证

本项目基于Apache License 2.0许可 - 详情请查看 [LICENSE](LICENSE) 文件。

## 🔗 链接

- GitHub仓库: [https://github.com/qingkong-template/AI-Meal](https://github.com/qingkong-template/AI-Meal) 
