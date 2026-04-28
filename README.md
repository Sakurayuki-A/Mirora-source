### 基本结构

```json
{
  "id": "example",
  "name": "示例动漫站",
  "version": "1.0.0",
  "baseURL": "https://example.com/",
  "searchURL": "https://example.com/search?q={keyword}",
  "searchList": "//div[@class='result-item']",
  "searchName": ".//h2/a/text()",
  "searchResult": ".//h2/a/@href",
  "imgRoads": "//img[@class='cover']/@src",
  "chapterRoads": "//div[@class='episode-list']",
  "chapterResult": ".//a/@href",
  "isEnabled": true
}
```

## ⚠️ 免责声明

- 本仓库仅提供数据源配置信息，用于技术学习和研究目的
- 用户应遵守目标网站的服务条款和 robots.txt
- 用户应遵守所在地区的法律法规
- 本项目不对用户的使用行为负责
- 数据源配置由社区贡献，准确性和可用性不做保证

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

## 🔗 相关链接

- [DimenX 主项目](https://github.com/Sakurayuki-A/DimenX)
- [问题反馈](https://github.com/Sakurayuki-A/DimenX-source/issues)

## 📊 版本历史

- **v1.0.0** (2026-04-28) - 初始版本，包含 5 个数据源
