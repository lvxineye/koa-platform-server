# koa-platform-server

> koa 框架服务端搭建


## 安装要求

> 列出运行该项目必须要具备的条件以及必须要安装的软件，最好给出具体的安装步骤。

- 安装nodejs

- 全局安装Koa脚手架

  ```
  npm install koa-generator -g
  ```

- 项目模板生成

  ```
  koa2 my-project-name
  ```

- 安装依赖和运行

  ```
  cd my-project-name # 切换目录
  npm install # 安装依赖 或者 yarn install 或者 cnpm install
  npm start # 项目运行
  ```


## 安装步骤

sequelize 生成表对应的schema
sequelize-auto -o "./schema" -d healthy_life_management -h localhost -u root -p 3306 -x lvxin123 -e mysql

sequelize-auto -o "./schema" -d healthy_life_management -h localhost -u root -p 3306 -x lvxin123 -e mysql -t dim_houses

一步一步地说明怎么去搭建环境，怎么让项目跑起来。

首先你需要

1. 干这件事

2. 干那件事

3. 继续干这件事

......一直到完成。

## 部署

对以上的安装步骤进行补充说明，描述如何在在线环境中安装部署该项目。

## 框架

## 线上部署启动项目配置
  #开发环境 "env": { "NODE_ENV": "dev" },
  启动命令：pm2 start processes.json --env dev

  #预发环境 "env_beta": { "NODE_ENV": "beta" },
  启动命令：pm2 start processes.json --env beta

  #线上环境 "env_production": { "NODE_ENV": "production" },
  启动命令：pm2 start processes.json --env production
