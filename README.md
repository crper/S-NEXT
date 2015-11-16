#S-NEXT
一款基于bootstrap的响应式后台主题,修改和更新可以查看'CHANGELOG.md`

##注意:
请到gh-pages分支去下载模版

###贯穿整个模版的五个必备库
- FontAwesome v4.4.0 -- 丰富的图标
- Bootstrap v3.3.5 -- 响应式框架
- jquery-2.1.4 -- 可以快速开发的JS框架
- velocity.js v1.2.3（非常快速的动画插件，很明显改善了整个模板动画的执行效率）
- s-next.js -- 整个后台模板的核心库


#为什么做！！
1. 原有模版有很多用不到的东西，比如调用谷歌的在线字体；
2. IE10+下的一些BUG没有修复．提交ISSUE没反应
3. 插件不使用bower管理,升级插件什么太麻烦
4. 原有的模版样式不够丰富,准备自行拓展
5. 原有的模版不用sass,准备自行添加进去
6. 调整一些东东更适合国内
7. 不喜欢太耦合,基本元素做成页面,插件的单独页面


#模版的特点
- 使用bower管理依赖
- 能不用插件的实现的功能，尽量不用插件
- 能用CSS实现的效果，也尽量不借助其他东东
- 尽可能的减少错误,规范的书写代码(去掉了原来模板的一些语法错误),及精简了一些冗余代码
- 用`velocity.js`改善整个模板的动画执行效率，非常明显！！
- 低级浏览器的提醒，及一些功能上的CSS HACK添加
- CDN使用国内的
- 还有一些小细节上的完善及功能添加(比如表单验证!!!`checkbox` css3美化!)
- `fastclick`并入`s-next.js` -- 解决移动端点击300ms问题


#后续可能添加的功能
-  使用gulp自动化构建
-  换肤功能
-  模块化(`webpack`或者`requirejs`)

#兼容性
1. IE9+
2. Firefox 40+
3. Chrome 30+

#目录结构
```
    │  .bowerrc
    │  bower.json
    │  box.html
    │  button.html
    │  form.html
    │  general.html
    │  icons.html
    │  index.html
    │  README.md
    │  table.html
    │  
    ├─dist
    │  ├─css
    │  │  ├─all   
    │  │  └─skins        
    │  ├─fonts     
    │  ├─img
    │  └─js
    │      └─plugins
```

#感谢
基于[**Admin-lte**](https://github.com/almasaeed2010/AdminLTE)为基础制作而成;<br>
有个成型的模版省去了大量的时间,非常感谢作者[@Abdullah Almsaeed](https://github.com/almasaeed2010)
<br>
**有兴趣的小伙伴们`fork`一起完善吧!!应该还有相当多的地方可以继续完善的**