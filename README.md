# HeySage 官网

## 🌐 网站概览

这是 HeySage AI心理健康助手的官方网站，包含产品介绍、功能特色、定价信息以及法律文档。

## 📁 文件结构

```
website/
├── index.html              # 主页
├── privacy-policy.html     # 隐私政策页面
├── terms-of-service.html   # 服务条款页面
└── README.md               # 说明文档
```

## 🚀 部署方案

### 方案1: GitHub Pages (推荐)
1. 创建GitHub仓库 `heysage-website`
2. 上传所有HTML文件到仓库
3. 在仓库设置中启用GitHub Pages
4. 选择从main分支部署
5. 获得免费域名：`https://yourusername.github.io/heysage-website/`

### 方案2: Netlify
1. 将website文件夹压缩为ZIP
2. 访问 [netlify.com](https://netlify.com)
3. 拖拽ZIP文件到Netlify
4. 获得免费域名：`https://random-name.netlify.app`

### 方案3: Vercel
1. 安装Vercel CLI：`npm i -g vercel`
2. 在website目录运行：`vercel`
3. 跟随CLI指示完成部署
4. 获得免费域名：`https://project-name.vercel.app`

## 🔗 App Store Connect 配置

部署完成后，在App Store Connect中使用以下URL：

- **隐私政策URL**: `https://your-domain.com/privacy-policy.html`
- **服务条款URL**: `https://your-domain.com/terms-of-service.html`
- **技术支持URL**: `https://your-domain.com/#contact`
- **营销URL**: `https://your-domain.com`

## 🎨 自定义建议

### 1. 添加App图标
在`<head>`部分添加：
```html
<link rel="icon" type="image/png" href="favicon.png">
```

### 2. 更新联系信息
替换以下占位符：
- `support@heysage.com` → 您的实际邮箱
- `privacy@heysage.com` → 您的隐私邮箱
- `legal@heysage.com` → 您的法务邮箱
- `（您的公司地址）` → 实际公司地址

### 3. 添加App Store链接
当App上线后，更新主页中的下载链接：
```html
<a href="https://apps.apple.com/app/heysage/idXXXXXX" class="btn btn-primary">立即下载</a>
```

### 4. SEO优化
- 添加Google Analytics代码
- 设置合适的meta标签
- 提交到Google Search Console

## 📱 移动端适配

网站已经包含响应式设计，在手机、平板、桌面设备上都有良好的显示效果。

## 🔒 安全考虑

- 所有表单都使用HTTPS
- 隐私政策和服务条款符合GDPR、CCPA标准
- 包含医疗免责声明

## 📊 SEO关键词

网站已优化以下关键词：
- 心理健康
- AI助手
- 心理咨询
- 情绪管理
- 焦虑缓解
- 压力疏导
- CBT认知行为疗法

## 🌍 多语言支持

当前支持中文，如需英文版本：
1. 复制所有HTML文件
2. 添加`-en`后缀（如`index-en.html`）
3. 翻译内容
4. 在主页添加语言切换链接

## 📞 技术支持

如需修改网站内容或添加新功能，请根据以下优先级操作：

1. **紧急修改**（如联系方式）：直接编辑HTML文件
2. **内容更新**：更新对应的HTML文件
3. **设计调整**：修改CSS样式
4. **功能添加**：在JavaScript部分添加新功能

## ✅ 发布检查清单

- [ ] 所有联系信息已更新
- [ ] App Store链接已添加（上线后）
- [ ] 隐私政策和服务条款日期正确
- [ ] 网站在不同设备上测试正常
- [ ] 所有链接可以正常访问
- [ ] 提交到App Store Connect 