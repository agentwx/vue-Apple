#  Vue.js 仿苹果官网 

-  This is a `beginning` project of `vue.js` for imitating the official `Apple website`
-  最近开始学的`Vue.js`这是一个我仿的`PC端`的`Apple官网`

### 暂时想实现的功能

- [X] 完成顶部的headerBar

      编写router-link的样式的时候可以用`<a>`标签代替，就可以按照需求改变链接样式。

- [X] 完成首页页面

- [ ] Mac页面

- [ ] 一件商品的详细页面（因为涉及到CSS动画和页面量太大，考虑放后面一点实现）

- [ ] 登录注册功能

- [ ] 购物车页面

### Day 1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2018.1.24)

-  利用`EasyMock`建立好`Home页面`的网址图片数据和`Mac页面`图片的数据

    -  Home 页面 : 
        [HomeData的页面数据](https://www.easy-mock.com/mock/5a67ef8cbdf9f5437bb4979a/Data/homedata/)
    -  Mac 页面 : 
    [MacData的图片数据](https://www.easy-mock.com/mock/5a67ef8cbdf9f5437bb4979a/Data/macData)

-  在`iconfont`上下载好所需要的`图标`

### Day 2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2018.1.25)

-  今天没做很多事，有些烦心事，就做了一个顶部的`headbar的基础样式`，没写很多，脑子想很多，想其他事情去了，写代码的心情很复杂

### Day 3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2018.1.26)

-  router编写顶部的headerbar完成页面的跳转
    -  发现的router的tag属性默认是 `<a>`这个标签，这样就可以按照自己需要更改router-link的样式

-  利用`axios`获取我再EasyMock上提前搭建好的数据，赋值给首页所需要的数组
-  大致做好了首页的框架

### Day 4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2018.1.27)

-  天气好冷，等下雪，等不到呢（来自一只南方人的忧桑） :( 
-  首页做完了，本来想一起将Mac页面也写掉的，手冷就没有然后咯

### Day 5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2018.1.28)

-  将底部的页面划分为一个组件供其他页面使用
-  实现了Mac页面的顶部的小电脑们，一开始想一个个写的(发现有十个，就不想写那么多，我就想用一个简洁的方法来实现这些不一样大小的图片和文字让他们排列好显示出来，没想到很快就实现了，一个v-for就解决了，样式也很简单，成就感满满，代码越简洁，我越开心，哈哈哈哈哈哈哈哈，开心)  :D
-  这个项目最近好像都一直拖拖拖，都没写什么，第五天啦，进展有点慢，接下来一段时间要赶紧啦

### Day 6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2018.1.29)

-  Mac页面还差一个tab切换，切了几百行的页面代码很难受
-  去看了一点点 CSS3 和 WebGL ，不得不说对3D还是有蛮大兴趣的
-  自己用CSS的伪元素实现了部分简单的图标
-  给自己的代码加了注释，看起来和修改起来方便一些
-  每天步数都不超过100步，我想出去玩啊，要疯了啊 
-  附上一个20多岁的老年人悟出的一些道理
      
    -  就是早睡早起，多运动，才不会猝死在电脑前面，毕竟我还年轻
    -  还有就是要多穿点
    -  嗯 就是这样 很有道理 :D

   
