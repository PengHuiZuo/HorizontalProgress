# HorizontalProgress
这是一款封装好的自定义横向进度
@property(nonatomic, copy) UIColor *unachievedColor; // 进度条默认颜色

@property(nonatomic, copy) UIColor *achievedColor;   //进度条渲染颜色

@property CGFloat pointMaxRadius;                    //圆点大小

@property NSUInteger lineMaxHeight;                  //线的高度

@property NSInteger currentLevel;                    //当前进度

@property CFTimeInterval animationDuration;          //动画时间

@property ProgressLevelTextPosition textPosition;    //描述内容的位置 (线上或者线下)

@property(nonatomic, copy) NSArray *progressLevelArray; // 进度条的多少段
