# weather-comparison 天气对比网站

## 文件说明
- index.html：天气网站主文件
- CNAME：自定义域名配置文件
- _headers：Netlify缓存控制文件（现托管于GitHub Pages，暂时无效，备用保留）

## 技术说明
- 数据来源：Open-Meteo API
- 韩国用KMA气象厅模型（kma_seamless）
- 其他国家用best_match模型
- 韩国坐标自动显示韩文，其他地区显示中文
