# 参赛作品名
Mixlab-百变小青

## 作品简介
   起因是看到了画风迁移的图像线稿处理,以及实际在跨境参考选品的当中看到别人老外对中国元素的落地,变现应用.有人将青花瓷印制在了如马克杯,或者宠物碗上面.
## 使用方式
   具体思路：用户上传头像,自动生成黑白线稿,然后具体画风学习生成具有中国元素的青花瓷图案,具体是建议后续有单帧的绘画过程,然后可以生成案例视频,上传到不同社交平台引流. 
## 目前进度
   1.因为队员都是新手,初始学习成本思路错了,参考官网的Github教程走了弯路,偏程序猿的思路和文档.本地部署以及配置Git或者python还有编译器,操作命令行等等;以及特别是算力的部署关于GPU的,还需要去官网Download查询对应的版本信息,所谓3行代码这个时间基本耗了很多.
   2.根据文档信息本地部署是不行了,于是在B站找到官方关于口罩的案例,直接通过实例看到Aistudio是直接部署好的线上环境.并不需要配置太多.便直接入手,同时参考了B站百年老视频上色处理案例.基本知道是怎样操作.后续根据PaddleGan的文档,基本实现了老照片的上色,超分,画风迁移的API调用处理学习.（PS:队员部分第一次接触代码,概念有些不是程序猿角度,比如实例化、面向对象等等说法不是新手马上能理解上手的,官方而且很多是项目案例形式,对学习查检索和解决问题较高,新手很容易有挫败感特别第一点的坑.)
