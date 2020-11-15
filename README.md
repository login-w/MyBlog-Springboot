# 这是我的个人博客系统
使用到的技术栈为springboot+mysql+mybatis+html+css+jquery+semantic-ui
项目主体功能：
    分为前后台两个系统
    前台：负责展示博客内容，用户访问可以浏览博客，也可以留言给博主，
          首页有最新推荐--根据访问量推荐出最火的四篇文章
          分类页面有所有类别的标签名，用户可以通过点击具体某一个标签名，去访问该标签下的所有博客内容，每一个标签下，如果有多篇内容需要翻页，采用ajax来进行翻页操作，在这里要注意ajax中               click失效的问题
          归档页面，采用timeline时间轴，进行展示每一篇博客，博客按其创作时间，依次展示在页面上，在这里只展示博客的标题，具体内容，用户可以通过点击页面后，浏览到更多信息。
          关于我页面，有博主的爱好标签，在这里你可以了解到关于博主的更多信息，以及博主写作的所有标签展示，租后还有作者的练习方式，可以通过这些方式，去联系博主
          后台：博客内容的增删改查
