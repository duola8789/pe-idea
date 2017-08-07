## PE-IEDA
The website for PE-IDEA industry design company which is established by my friends.

## 开发模式

运行：
``
gulp
``
## 版本迭代

#### 版本：V0.1

日期：2017.6.19

说明：按照我个人对需要文件的理解以及实际工作中的优化，将网站结构设置如下：

1. index-首页，首页分为五个模块（对应导航栏的五个链接），此时点击五个导航栏链接对应的是index首页内部五个模块的跳转，不会加载进入二级页面
2. 在index内各个模块内点击可跳转链接，将连接到二级页面，二级页面的导航与index页面的导航不同，将在各个二级页面和index之间相互跳转
3. index首页内案例展示模块点击案例图片，点击进入examle页面，为单独产品的页面，实际属性为案例展示页面的下一级页面（即三级页面）
4. 网站主要使用的框架为bootstrap，其他包括jQuery及插件等，针对移动端进行了适配和优化，理论上应该为响应式页面，兼容PC端、移动端；
5. 原网站加速速度慢的原因：fonts.useso.com(一个在线托管webfont的网站)， 由于对方服务器被限制，导致使用该网站托管字体的站点出现大面积的延缓；
6. 关于字体：需求中要求使用方正细黑简体，产品层面可以使用改字体，但是我认为网站有盈利性质，并且方正细黑简体并非免费开原字体，使用该字体有一定的风险，所以建议谨慎使该字体，目前网站使用的字体为微软雅黑字体，最终字体选择需要需求方决定；
7. 需要提供的素材尺寸：浏览器收藏夹及标题栏图片格式为ioc，尺寸为32*32， 其他大图尺寸均为1920x1080
8. 在线客服功能暂时无法添加；
9. 网站自行维护有一定难度;
10. 网站源码地址：https://github.com/duola8789/PE-IDEA

#### 版本：V0.2

日期：2017.6.20

修改内容：
1. 移动端导航栏点击空白收起
2. 移动端导航栏点击在本页跳转后收起
3. 二维码更换为需求方提供的真实二维码
4. 点击导航logo能够返回首页
5. 字体确认使用微软雅黑字体
6. 其余需求待确定

#### 版本：V0.3

日期：2017.8.6

修改内容：
1. 根据需求要求对网站宽度、页面布局进行更改

待做：
1. 主要客户的效果
2. 百度地图SDK
3. 分享至微博微信
4. 源文件不用传导网站
5. 字体改用rem
6. 自适应iphone6, iphone6+, ipad, ipadmini, pc