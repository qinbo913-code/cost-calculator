# 成本测算工具

一个用于工程物资项目成本测算的Web工具，支持三种投资模式对比测算。

## 功能特性

- 多材料独立测算（钢材、水泥、柴油、地材、外加剂、沥青等）
- 三种投资模式对比：100%投资 / 50%投资+垫资 / 100%垫资
- 自动计算税费（增值税、印花税、附加费）
- 盈亏平衡点分析（0%、1%、3%利润率）
- 历史记录保存与导出
- 飞书表格格式导出

## 密码保护

默认密码：`jyb`

## 部署到 Vercel

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/cost-calculator)

### 手动部署步骤

1.  Fork 或下载本仓库
2.  登录 [Vercel](https://vercel.com)
3.  点击 "New Project"
4.  导入本仓库
5.  点击 "Deploy"
6.  在 Settings → Domains 中添加你的自定义域名

### 修改密码

编辑 `login.html` 文件中的密码：

```javascript
const CORRECT_PASSWORD = 'jyb'; // 修改为你自己的密码
```

## 技术栈

- React + TypeScript
- Tailwind CSS
- 纯前端静态网站（无后端）

## 数据存储

- 数据保存在浏览器本地存储（LocalStorage）
- 支持导出 CSV 备份

## License

MIT
