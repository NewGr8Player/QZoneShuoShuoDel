# QZoneShuoShuoDel
QQ空间删除脚本

修改自[这个项目](https://github.com/aqiongbei/qq_zone_delete)

> 说说删除有限制，每天删除一定数量之后就会出现验证码。

### 说说删除
打开空间，选择**说说**Tab页，使页面处于如下图所示状态

![说说Tab页面](https://github.com/aqiongbei/qq_zone_delete/blob/master/readme_img/2018-01-03_231036.png)

然后在当前页面打开控制台，在控制台选择**index.html**这个`iframe`

![index.html](https://github.com/aqiongbei/qq_zone_delete/blob/master/readme_img/2018-01-03_231229.png)

这时候页面的说说内容部分应该处于选中状态

![说说内容部分状态](https://github.com/aqiongbei/qq_zone_delete/blob/master/readme_img/2018-01-03_231256.png)

选择好之后就可以在这里注入说说删除脚本了，把这个文件的内容复制、丢进控制台执行即可。脚本执行过程中在左侧页面区域会看到控制台提示

> 请忽略数量上的不一致

删除完成的时候会自动刷新页面。这时候说说一般都删完了，整个过程不需要用户交互。
