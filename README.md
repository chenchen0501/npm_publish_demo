# 注意点
 *  clone本仓库至本地
 *  npm install
 *  修改package.json中
    *  name - 修改为自己需要发版的npm包名字（名字不可与npm已有包名重复、名字正常一点不然发不了）
    *  main - 根据name自行修改
    *  author - 在npm注册的账号
 * app.vue中的组件即为需要发版的组件
 * index.js中导出组件
 * 发版一定要切换npm源，不要使用淘宝源，不然会发布失败
 * npm发版步骤请查看[我的简书](https://www.jianshu.com/p/999e3f85b37f)
