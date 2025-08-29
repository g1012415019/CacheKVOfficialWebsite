# CacheKV Official Website

## 目录结构

```
├── assets/                 # 静态资源
│   ├── css/               # 样式文件
│   │   ├── style.css      # 主样式文件
│   │   └── prism-tomorrow.min.css  # 代码高亮样式
│   ├── js/                # JavaScript文件
│   │   ├── prism-core.min.js       # Prism核心库
│   │   └── prism-autoloader.min.js # Prism自动加载器
│   └── images/            # 图片资源
├── public/                # 公共文件
│   ├── index.html         # 主页
│   ├── docs.html          # 文档页面
│   ├── manifest.json      # PWA清单
│   ├── sitemap.xml        # 站点地图
│   ├── robots.txt         # 爬虫规则
│   └── .htaccess          # Apache配置
├── docs/                  # 文档相关
│   └── schema.json        # 结构化数据
├── src/                   # 源代码（预留）
└── .git/                  # Git版本控制
```

## 变更说明

1. **标准化目录结构**: 采用了Web项目的标准目录结构
2. **本地化CDN资源**: 将所有CDN的JS/CSS文件下载到本地
   - Prism代码高亮库的CSS和JS文件
3. **更新文件引用**: 修改了HTML文件中的资源路径引用

## 本地化的CDN资源

- `prism-tomorrow.min.css` - 代码高亮主题样式
- `prism-core.min.js` - Prism核心库
- `prism-autoloader.min.js` - Prism自动加载器

这样可以提高网站加载速度，减少对外部CDN的依赖。
