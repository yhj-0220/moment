# 开发约束

## 文件范围
- **只修改**: `moment-prototype/moment-prototype.html`
- **不动其他文件**: `index.html`、备份文件、临时脚本等一律不碰

## 数据存储
- 用户的真实数据在 `file://` 域下的浏览器 localStorage/IndexedDB 中
- 测试/开发时不得清除用户浏览器的数据
