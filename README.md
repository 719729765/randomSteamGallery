# Random Steam Gallery

一个轻量级 JS 库，用于在网页上随机展示 Steam 截图图库并自动轮播。  
无需后端 PHP，**纯前端实现**，适合 Gal 游戏资源网站或个人博客使用。  

---

## 🔹 功能

- 随机选取指定数量的 Steam 截图显示  
- 自动轮播（淡入淡出效果）  
- 支持自定义显示数量  
- 完全前端实现，无依赖  

---

## 🔹 使用方法

### 1. HTML 占位

```html
<section class="hidden-xs">
    <ul class="cb-slideshow"></ul>
</section>
````

### 2. 引入 JS 文件

```html
<script src="randomSteamGallery.js"></script>
```

> 页面加载完成后，脚本会自动随机选取 6 张截图生成轮播。

### 3. 可自定义参数（可选）

* `total`：显示图片数量
* `轮播间隔`：默认 3000ms，可在 JS 内 `setInterval` 修改

---

## 🔹 声明

* 所有截图来源于 Steam 社区公开图片
* 本脚本仅做前端展示用途，不涉及任何商业用途

---

## 🔹 贡献

欢迎提 Issue 或 PR 改进轮播效果、支持更多自定义配置或增加控制按钮。

```
