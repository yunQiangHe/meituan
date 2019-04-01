# vue-learn

## 1. [vue-cli](https://cli.vuejs.org/zh/)
##### 1.1 配置文件说明
```bash
|-- dist                        # 打包后文件夹
|-- public                      # 静态文件夹
|   |-- favicon.ico				
|   |-- index.html			    #入口页面
|-- src                         # 源码目录
|   |--assets				    # 模块资源
|   |--components			    # vue公共组件
|   |--views 
|   |--App.vue                  # 页面入口文件
|   |--main.js	                # 入口文件，加载公共组件
|   |--router.js                # 路由配置
|   |--store.js	                # 状态管理
|-- .env.pre-release            # 预发布环境
|-- .env.production	            # 生产环境
|-- .env.test		            # 测试环境
|-- vue.config.js               # 配置文件
|-- .eslintrc.js    		  	# ES-lint校验
|-- .gitignore          		# git忽略上传的文件格式
|-- babel.config.js   			# babel语法编译
|-- package.json       	        # 项目基本信息
|-- postcss.config.js   	 	# CSS预处理器(此处默认启用autoprefixer)
```

##### 1.2 [vue.config.js配置](https://cli.vuejs.org/zh/config/#vue-config-js)


##### 1.3 [打包配置](https://cli.vuejs.org/zh/config/#vue-config-js)
* 开发环境（开发阶段，本地开发版本，一般会使用一些调试工具或额外的辅助功能）
* 测试环境（测试阶段，上线前版本，除了一些 bug 的修复，基本不会和上线版本有很大差别）
* 预发布环境（即将上线阶段，上线前版本，预测线上出现问题的可能性，和上线版本无差别）
* 生产环境（上线阶段，正式对外发布的版本，一般会进行优化，关掉错误报告）

```bash
"scripts": {
    "serve": "vue-cli-service serve ",
    "build:pre": "vue-cli-service build --mode pre-release",  #预发布环境
    "build:test": "vue-cli-service build --mode test", #测试环境
    "build:prod": "vue-cli-service build --mode production", #正式环境
    "lint": "vue-cli-service lint",
    "test:unit": "vue-cli-service test:unit"
}
```


## 2. [vue-router](https://router.vuejs.org/zh/)
```bash
    $ vue add router
    添加了router.js, views/About.vue
```
## 3. [vuex](https://vuex.vuejs.org/zh/)
```bash
    $ vue add vuex
```

## 3. [axios](https://github.com/axios/axios)
