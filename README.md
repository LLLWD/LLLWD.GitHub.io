<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>小张笔记</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="description" content="Description">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0">
  <link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify@4/lib/themes/vue.css">
  <link rel="stylesheet" href="//unpkg.com/gitalk/dist/gitalk.css">
  <style>
    .markdown-section code {
      color: rgb(184, 101, 208);
    }
  </style>
</head>
<body>
  <div id="app">🏃‍🏃‍🏃‍💨 Loading....</div>
   <script>
    window.$docsify = {
      search: 'auto',
      name: '小张笔记',//侧边栏标题
      repo: 'https://github.com/Proberen/xiaozhang_java.git',
      coverpage: true,
      loadNavbar: true,//顶部导航
      loadSidebar: true, // 加载自定义侧边栏
      maxLevel: 4, // 默认情况下会抓取文档中所有标题渲染成目录，可配置最大支持渲染的标题层级。
      subMaxLevel: 5, // 生成目录的最大层级
      mergeNavbar: true, // 小屏设备下合并导航栏到侧边栏
      topMargin: 60,
      search: {
        paths: 'auto',
        placeholder: '🔍 搜索',
        noData: '😒 找不到结果',
        // Headline depth, 1 - 6
        depth: 6,
        maxAge: 86400000, // 过期时间，单位毫秒，默认一天
      },//添加搜索框
    } 
  </script>
  <script src="//unpkg.com/docsify/lib/docsify.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/search.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/emoji.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/external-script.min.js"></script>
  <!--Java代码高亮-->
  <script src="//cdn.jsdelivr.net/npm/prismjs@1.23.0/components/prism-java.js"></script>
  <script src="//cdn.jsdelivr.net/npm/prismjs@1/components/prism-bash.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/prismjs@1/components/prism-php.min.js"></script>
  <!--Java代码高亮-->
  <script src="//unpkg.com/prismjs/components/prism-python.js"></script>
  <!--sql代码高亮-->
  <script src="//unpkg.com/prismjs/components/prism-sql.js"></script>
  <!--shell代码高亮-->
  <script src="//unpkg.com/prismjs/components/prism-bash.js"></script>
  <!-- 复制到剪贴板 -->
  <script src="//unpkg.com/docsify-copy-code"></script>
  <!-- 字数统计 -->
  <script src="//unpkg.com/docsify-count/dist/countable.js"></script>
  <!-- 上一篇/下一篇 -->
  <script src="//cdn.jsdelivr.net/npm/docsify-pagination/dist/docsify-pagination.min.js"></script>
  <!-- mouse click -->
  <script src="//cdn.jsdelivr.net/gh/jerryc127/butterfly_cdn@2.1.0/js/click_heart.js"></script>
  <!-- 图片缩放插件 -->
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/zoom-image.min.js"></script>
  <script src="//unpkg.com/docsify/lib/plugins/gitalk.min.js"></script>
  <script src="//unpkg.com/gitalk/dist/gitalk.min.js"></script>
  <script>
    const gitalk = new Gitalk({
      clientID: 'a704ca6f182b7758af8c',
      clientSecret: 'bc34952b5245ac0c9e794d53962ff60a0d7c2b7d',
      repo: 'xiaozhang_java',
      owner: 'Proberen',
      admin: ['Proberen'],
      id: location.pathname,
      distractionFreeMode: false
    })
  </script>
  <script src="https://unpkg.com/docsify-plugin-flexible-alerts"></script>
  <!-- 回到顶部功能 -->
  <script src="https://cdn.jsdelivr.net/gh/wugenqiang/NoteBook@master/plugin/jquery.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/wugenqiang/NoteBook@master/plugin/jquery.goup.js"></script>
  <script type="text/javascript">
    $(document).ready(function () {
      $.goup({
        trigger: 100,
        bottomOffset: 52,
        locationOffset: 25,
        //title: 'TOP',
        titleAsText: true
      });
    });
  </script>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-S02Z7R76NJ"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-S02Z7R76NJ');
</script>

<script src="https://eqcn.ajz.miesnfu.com/wp-content/plugins/wp-3d-pony/live2dw/lib/L2Dwidget.min.js"></script>
<script>
  L2Dwidget.init({
    "model": {
      //jsonpath控制显示那个小萝莉模型，
      //(切换模型需要改动)
      jsonPath: "https://unpkg.com/live2d-widget-model-koharu@1.0.5/assets/koharu.model.json",
      "scale": 1
    },
    "display": {
      "position": "right", //看板娘的表现位置
      "width": 80,  //小萝莉的宽度
      "height": 160, //小萝莉的高度
      "hOffset": 35,
      "vOffset": -20
    },
    "mobile": {
      "show": true,
      "scale": 0.5
    },
    "react": {
      "opacityDefault": 0.7,
      "opacityOnHover": 0.2
    }
  });
</script>

</body>
</html>
