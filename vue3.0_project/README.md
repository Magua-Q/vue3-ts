# vue3.0_project

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
### setup函数
    1. 执行时机 创建组件实例，然后初始化props，紧接着就调用setup函数，会在beforeCreate钩子之前被调用
    2. 在模板中使用 如果setup返回一个对象，则对象的属性将会被合并到组件模板的渲染上下文