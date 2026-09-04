# 叶绿体环保官网 — 站点资料包

佛山市叶绿体环保科技有限公司 中英文双语官网（静态站点）

## 📁 文件结构

```
叶绿体环保官网/
├── index.html              # 官网主页面（含中英文切换、全部样式与脚本）
└── images/
    ├── logo.jpg            # 公司 Logo
    ├── A_stunning_wide_banner_image_f_2026-09-04T03-26-47.png   # Hero 首屏背景图
    ├── Aerial_view_of_a_modern_green__2026-09-04T03-27-11.png    # 关于我们配图
    ├── Elegant_abstract_nature_backgr_2026-09-04T03-27-11.png    # 装饰背景图
    ├── Environmental_monitoring_and_s_2026-09-04T03-26-39.png    # 环境监测配图
    ├── Modern_environmental_engineeri_2026-09-04T03-26-38.png    # 环保工程配图
    └── Professional_illustration_of_e_2026-09-04T03-26-37.png    # 环保咨询配图
```

## ✨ 站点特性

- **中英文双语**：右上角「中文 / EN」一键切换，全站文案同步切换
- **响应式布局**：电脑端与手机端均自动适配，含移动端汉堡菜单
- **蓝绿色调**：teal / emerald / cyan 环保配色体系
- **页面板块**：首页 Hero（含数据动画）→ 关于我们 → 核心业务（6 大服务）→ 资质荣誉 → 产学研合作 → 服务区域（大湾区 7 城）→ 联系我们
- **动效**：加载动画、飘落叶片、滚动渐现、数字计数、卡片悬浮

## 🚀 如何部署

本网站为纯静态站点，无任何框架依赖。打开或部署方式：

1. **本地预览**：直接用浏览器打开 `index.html` 即可；也可在任意静态服务器上托管
2. **服务器部署**：将 `index.html` 与 `images/` 文件夹整体上传到服务器（Nginx / Apache）或对象存储（腾讯云 COS、阿里云 OSS、EdgeOne Pages 等），即可通过域名访问
3. **内网/团队共享**：将整个文件夹放入共享盘或团队空间后，其他成员可直接打开 `index.html` 预览

> 提示：全站样式与脚本已内联在 `index.html` 单个文件中，唯一外部依赖为 Font Awesome 图标库（CDN）。若需完全离线可用，可将图标库改为本地文件或替换为内联 SVG。

## ✏️ 修改指引

- 改文字/翻译：直接编辑 `index.html` 中带 `data-zh` / `data-en` 属性的文本
- 改配色：调整 `index.html` 顶部 `:root` 中的 CSS 变量（`--primary` 等）
- 换图片：替换 `images/` 下同名文件即可
