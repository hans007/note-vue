# vue 装饰器

## 内容

- 什么是 `Decorator 装饰器`
- `vue` 官方提供的装饰器
- `vuex` 官方提供的装饰器

## 什么是 `Decorator 装饰器`

首先这是一个 `es7` 的新特性

```ts
@Prop() data: any
```

这是一个 `属性` 修饰器，在执行 `data` 之前，先执行 `@Prop` 的加工处理

顺序是 `@Prop` -> `data` 里面

我感觉装饰器，可以大大的简化代码可读性，把重复的内容都抽象掉了

## `vue` 官方提供的装饰器

- vue-class-component

这是vue

- vue-property-decorator


## `vuex` 官方提供的装饰器



