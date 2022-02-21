# Nodejs Addon 扩展


### 目录

- demo-addon: 演示项目，加载和测试addon
- hello-world: addon扩展


### 使用方法

```shell
 cd hello-world
 npm link

 cd ../demo-addon
 npm link hello-world

 yarn start
```