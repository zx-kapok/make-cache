# 使用文档

<br />

### 使用示例

```javascript
const FC = window.MakeCache;
const cache = new FC();
// 设置
cache.set("a", 100);
// 获取
const value = cache.get("a");
// 删除
cache.remove("a");
// 清空
cache.clear();
```

<br />

### API

| 属性   | 说明 | 类型     | 默认值 | 备注 |
| ------ | ---- | -------- | ------ | ---- |
| get    | 获取 | function | -      |
| set    | 设置 | function | -      |
| remove | 删除 | function | -      |
| clear  | 清空 | function | -      |
