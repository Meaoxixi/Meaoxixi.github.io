## 宠物设置
$ npm i hexo-helper-live2d --save
$ npm i live2d-widget-model-hijiki --save

编辑配置文件~/文档/hexo/_config.yml,在最下方添加如下配置信息启用宠物
# live2d配置宠物
live2d:
  enable: true
  scriptFrom: local
  model:
    #use: live2d-widget-model-tororo
    use: live2d-widget-model-hijiki
  display:
    position: right
    width: 240
    height: 480
  mobile:
    show: false
  react:
    opacityDefault: 1
    opacityOnHover: 1
