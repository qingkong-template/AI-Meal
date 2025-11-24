# AI-Meal
Now supporting AI-powered work meal recommendations.

**English Documentation** | **[中文文档](README.zh-CN.md)**

AI-Meal helps people solve the problem of not knowing what to eat. Developed with HTML + Tailwind CSS + JavaScript + Font Awesome (SVG Icons) + LocalStorage + OpenRouter API (AI Features) + Noto Sans SC Font, it features a modern and aesthetically pleasing interface design.

**Online Demo**: [https://eat.dawua.dpdns.org/](https://eat.dawua.dpdns.org/) - Try it now!

## 🚀 Key Features

### 1. Core Recommendation Features
1. **Mood-Based Selection**: Offers 4 emotional food preference options (Craving Spicy, Meat Lover, Light/Healthy, Random), aligning with users' immediate dining needs and reducing decision-making costs.
2. **Daily Recommendation Limit**: Default 3 recommendations per day to avoid overthinking. The limit resets when updating the menu, balancing practicality and guidance.
3. **Optimized Result Interaction**: Recommendation results include dish name, recommendation reason, and encouraging message. Supports "Get Another Recommendation" or "Confirm Selection", with quick switching to other taste preferences if unsatisfied.

### 2. Menu Management Features
1. **Custom Menu Input**: Supports pasting/entering canteen/restaurant menus, automatically recognizing dishes to form a personal menu library, adapting to different dining scenarios (canteens, regular restaurants, etc.).
2. **Menu Status Indication**: Real-time display of menu-related status (e.g., number of dishes, availability), allowing users to clearly understand the basic data for recommendations.

### 3. Intelligent & Personalized Configuration
1. **AI-Enhanced Recommendations**: After configuring the OpenRouter API Key, AI-powered intelligent recommendations are enabled—accurately matching based on mood and menu content. It can also recommend general work meals when no menu is available.
2. **History Management**: Records dishes that users have "confirmed to eat", supports viewing dining history, and avoids duplicate recommendations.
3. **Flexible Avoidance Rules**: Allows setting "Duplicate Dish Avoidance Days" (0-30 days) and "Recommended Dish Avoidance Days" (0-30 days), customizing the intensity of avoiding duplicates to meet different user needs.

### 4. Basic Experience Optimization
1. **Theme Switching**: Supports automatic light/dark mode adaptation (following system settings) or manual switching, adapting to different usage scenarios and visual preferences.
2. **Clear Status Feedback**: Includes status prompts such as loading, recommendation limit exceeded, and no more historical dishes, avoiding user confusion.
3. **Local Data Storage**: Automatically saves menu input, theme preferences, dining history, etc. locally, eliminating repetitive operations and improving usage continuity.

### 5. Usage Scenario Adaptation
- Core Scenarios: Quick decision-making when dining in canteens or fixed restaurants;
- Extended Scenarios: General work meal recommendations when no clear menu is available (after configuring API Key);
- Device Compatibility: Supports mobile/desktop devices with a responsive interface design and simple operation flow (single-page interaction, no multi-page navigation).

## 🛠️ Tech Stack

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - Basic language for web content structure
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework for building responsive interfaces quickly
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Core language for web interaction logic
- [Font Awesome (SVG Icons)](https://fontawesome.com) - Lightweight and customizable vector icon library
- [LocalStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) - Browser local data storage solution
- [OpenRouter API](https://openrouter.ai) - Third-party AI model calling interface providing intelligent recommendation capabilities
- [Noto Sans SC](https://fonts.google.com/specimen/Noto+Sans+SC) - Google's open-source Chinese sans-serif font, suitable for multi-scenario display

## 🧩 Project Structure

```
```

## 🧪 Development Guide

Development steps:

1. Create a new directory in the `root directory` for modifications

## 🌍 Contribution Guide

Contributions are welcome! Feel free to submit a Pull Request.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- GitHub Repository: [https://github.com/qingkong-template/AI-Meal](https://github.com/qingkong-template/AI-Meal)

## ADD API KEY

```
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

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

```