

包信息获取依赖android sdk build tools，项目自带25.0.2版本sdk依赖工具

#### 生成签名包 
genChannelApk(input, output, channel_info)

##### 示例
```
 genChannelApk('sgame_self-lilith-0316.apk', 'test.apk',{'aos_channel': 'lilith', 'aos_adid': 1322212, 'game_id': 10004}) 
```

#### 获取包信息
```
getInfo('e:\\Walle\\sgame_self-lilith-0316.apk')
```
##### 返回 
```
{'name': 'com.lilithgame.sgame.android.cn', 'versionCode': '20180316', 'versionName': '1.16.16', 'platformBuildVersionName': '6.0-2438415'}
``` 

