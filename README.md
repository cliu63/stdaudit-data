# stdaudit-data

标准审查（WPS 加载项 stdaudit）的离线标准库数据包，供「一键更新」功能从 CDN 拉取。

- 数据来源：工标网（csres.com）公开目录整理，仅作状态参考
- 文件结构：`manifest.js`（版本与分片统计表）/ `index.js`（编号索引）/ `name-index.js`（名称索引）/ `shard_NNN.js`（数据分片）
- 通过 jsdelivr CDN 访问：`https://cdn.jsdelivr.net/gh/cliu63/stdaudit-data@<tag>/manifest.js`
- 版本 tag 与插件数据版本号一致（如 v0.9.1 = 85,343 条 / 569 片）
