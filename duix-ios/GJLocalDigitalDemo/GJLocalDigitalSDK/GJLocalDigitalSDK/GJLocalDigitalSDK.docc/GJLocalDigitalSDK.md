## GJLocalDigitalSDK(1.0.1)使⽤⽂档
    
### ⼀. 物料准备
 GJLocalDigitalSDK.framework  (-Embed & Sign)
 下载：<a href="https://duix.guiji.ai/document/demo/ios/GJLocalDigitalSDKDemo.zip"
      download="https://duix.guiji.ai/document/demo/ios/GJLocalDigitalSDKDemo.zip">下载Demo</a>

### ⼆. 开发环境
开发⼯具: Xcode  ios12.0以上 iphoneX及以上

### SDK回调
```
/*
*数字人渲染报错回调 50009 资源超时或未配置
*/
@property (nonatomic, copy) void (^playFailed)(NSInteger code,NSString *errorMsg);

/*
*音频播放结束回调
*/
@property (nonatomic, copy) void (^audioPlayEnd)(void);

/*
*播放进度回调
/
@property (nonatomic, copy) void (^audioPlayProgress)(float current,float total);
```

### SDK关键接口
```
/*
*appId
*appKey
*return 1 返回成功
*/
- (void)initWithAppId:(NSString *)appId appKey:(NSString *)appKey block:(void (^) (BOOL isSuccess, NSString *errorMsg))block;

/*
*basePath 底层通用模型路径-保持不变
*digitalPath 数字人模型路径- 替换数字人只需要替换这个路径
*return 1 返回成功 0未授权 -1 基本模型路径错误 -2 基本模型路径错误 -3 数字人模型路径错误 -4 数字人模型路径错误 -5数字人模型配置文件错误 -6数字人模型配置文件错误 -7数字人帧数错误 
*showView 显示界面
*/
-(NSInteger)initBaseModel:(NSString*)basePath digitalModel:(NSString*)digitalPath showView:(UIView*)showView;

/*
*bbgPath 替换背景 -jpg格式 ----背景size等于数字人模型的getDigitalSize-----------
*/
-(void)toChangeBBGWithPath:(NSString*)bbgPath;

/*
*wavPath 音频的本地路径 
*/
-(void)onewavWithPath:(NSString*)wavPath;

/*
*开始
*/
-(void)toStart:(void (^) (BOOL isSuccess, NSString *errorMsg))block;

/*
*结束
*/
-(void)toStop;

/*
*初始化模型过后才能获取
*getDigitalSize 数字人模型的宽度 数字人模型的高度
*/
-(CGSize)getDigitalSize;

/*
*取消播放音频
*/
-(void)cancelAudioPlay;
```
