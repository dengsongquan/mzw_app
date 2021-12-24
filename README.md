项目运行：
- 安装依赖
```
yarn install
```

- 开发模式运行
```
yarn run serve
```

- 编译项目
```
yarn run build
```

- Lints and fixes files
```
yarn run lint
```

页面布局：
BasicLayout.vue

以下配置是用来说明是否需要配置主题的按钮：
<!-- Setting Drawer (show in development mode) -->
<setting-drawer v-if="!production"></setting-drawer>

在/config/defaultSettings中配置
 production: process.env.NODE_ENV === 'production' && process.env.VUE_APP_PREVIEW !== 'true',

svn操作：
svn commit    提交更改项目
svn diff           显示变更项目
svn revert       还原/回滚变更操作
svn update     从SVN版本库获取更新
svn add          添加项目
svn rename    重命名SVN项目
svn log            显示日志文件
svn blame       项目变动追溯（这TM是谁写的……）
svn lock          锁定项目（一般是某些文件）
svn unlock      解除锁定  
# mzw_app
