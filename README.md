# nest 项目框架

## Fastify
Fastify 是一个高效的 web 框架，专注于提供最佳性能和开发者体验。它是一个低开销的框架，它的目标是在保持开销尽可能低的同时提供快速的速度。切换到 Fastify 是一个简单的过程，因为它是一个完全兼容的框架，同时提供了更好的性能。

## 版本控制
nest内置了版本控制,enableVersioning: true,默认版本号为v1,可以通过@Version('v2')来指定版本号。

## 全局返回参数

## 全局异常拦截

## 环境配置
安装 @nestjs/config,并在app.module.ts中引入ConfigModule.forRoot()即可使用.env文件中的配置。
自定义 YAML ,yarn add yaml。

## 文档生成
yarn add @nestjs/swagger