# 这个是快应用API的集合Demo
## 效果图
![image](https://github.com/l455202325/APIDemo/blob/master/images/scan.gif)
## 使用方式：
1. Clone下来代码
2. 打开命令行工具
3. 切换到代码所在的目录然后输入 npm install  按回车
4. 等待结束 然后再输入 npm run build 或者 输入 npm run watch 按回车
5. 另外再打开一个命令行窗口 切换到项目目录 输入 npm run server

- 好了现在就可以愉快的看 API 效果了
- [这个是已经完成API功能列表](https://github.com/l455202325/APIDemo/blob/master/completeList.md)，大家可查看，这个列表每天更新，直到全部开发完成


## 非常感谢大家积极参与到项目中来，现在功能开发小组人员已满，进入编写代码群二维码已经失效
- 下面是进学习交流群的二维码链接
----------
![image](https://github.com/l455202325/APIDemo/blob/master/images/group.jpg)

-----------
1. Cannot find module '/work/quick/node_modules/hap-tools/webpack.config.js'
- 如果报错遇到Cannot find module '.../webpack.config.js'，请重新执行一次hap update --force。这是由于高版本的npm在npm install时，会校验并删除了node_modules下部分文件夹，导致报错。而hap update --force会重新复制hap-toolkit文件夹到node_modules中
