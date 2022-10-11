# 使用文档

## 使用示例

```javascript
const FC = window.MakeCache;
const cache = new FC();
cache.set("a", 100);
console.log(cache.get("a"));
```

## 设置

```javascript
const FC = window.MakeCache;
const cache = new FC();
cache.set("a", 100);
```

## 获取

```javascript
const FC = window.MakeCache;
const cache = new FC();
const value = cache.get("a");
```

## 删除

```javascript
const FC = window.MakeCache;
const cache = new FC();
cache.remove("a");
```

## 清空

```javascript
const FC = window.MakeCache;
const cache = new FC();
cache.clear();
```

## 参数说明

| 属性 | 说明 | 类型 | 默认值 | 备注 |
| get | 获取字段值 | function | - |
| set | 设置字段值 | function | - |
| remove | 删除指定字段 | function | - |
| clear | 清空所有数据 | function | - |
