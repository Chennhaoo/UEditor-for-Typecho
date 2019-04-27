# UEditor-for-Typecho
原地址：`https://github.com/chanshengzhi/UEditor-for-Typecho`

安装方法：<br>
下载压缩包 https://github.com/Chennhaoo/UEditor-for-Typecho/releases <br>
然后将`UEditor`文件夹全部上传到Typecho插件目录即可

配置文件：<br>
`\UEditor\ueditor\php\config.json`


主要修改内容：<br>
不知道是我的配置问题还是啥的，上传上去的图片地址不多，会显示成`//usr/uploads/`，前面多了一个杠，导致显示失败，所以修改了`action_crawler.php` `action_list.php` `action_upload.php`文件