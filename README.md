# 学习列表 
github排名 [https://github.com/trending](https://github.com/trending),github搜索：[https://github.com/search](https://github.com/search)

###  目录
- [UI](#UI)
    - [下拉刷新](#下拉刷新)
    - [模糊效果](#模糊效果)
    - [AutoLayout](#AutoLayout)
    - [富文本](#富文本)
    - [图表](#图表)
    - [表相关与Tabbar](#表相关与Tabbar) 
    - [隐藏与显示](#隐藏与显示)
    - [HUD与Toast](#HUD与Toast)
    - [对话框](#对话框)
    - [其他UI](#其他UI)
- [动画](#动画)
    - [侧滑与右滑返回手势](#侧滑与右滑返回手势)
    - [gif动画](#gif动画)
    - [其他动画](#其他动画)
- [网络相关](#网络相关)
    - [网络连接](#网络连接)
    - [图像获取](#图像获取)
    - [网络聊天](#网络聊天)
    - [网络测试](#网络测试)
    - [WebView](#WebView)
- [Model](#Model)
- [通讯录](#通讯录)
- [其他](#其他)
- [数据库](#数据库)
- [缓存处理](#缓存处理)
- [PDF](#PDF)
- [图像浏览及处理](#图像浏览及处理)
- [摄像照相视频音频处理](#摄像照相视频音频处理)
- [响应式框架](#响应式框架)
- [消息相关](#消息相关)
    - [消息推送客户端](#消息推送客户端)
    - [消息推送服务器端](#消息推送服务器端)
    - [通知相关](#通知相关)
- [版本新API的Demo](#版本新API的Demo)
- [代码安全与密码](#代码安全与密码)
- [测试及调试](#测试及调试)
- [AppleWatch](#AppleWatch)
- [完整项目](#完整项目)
- [好的文章](#好的文章)
- [VPN](#VPN)
- [Xcode插件](#Xcode插件)
- [美工资源](#美工资源)
- [开发资源](#开发资源)
    - [开发资料](#开发资料)
    - [swift](#swift)
    - [他人开源总结](#他人开源总结)
    - [开发博客列表](#开发博客列表)

========
### 具体内容 =============================
========
#### UI
##### 下拉刷新
 * [EGOTableViewPullRefresh](https://github.com/enormego/EGOTableViewPullRefresh) - 最早的下拉刷新控件。
 * [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh) - 下拉刷新控件。 
 * [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - 仅需一行代码就可以为UITableView或者CollectionView加上下拉刷新或者上拉刷新功能。可以自定义上下拉刷新的文字说明。具体使用看“使用方法”。 （国人写）
 * [XHRefreshControl](https://github.com/xhzengAIB/XHRefreshControl) - XHRefreshControl 是一款高扩展性、低耦合度的下拉刷新、上提加载更多的组件。（国人写）
 * [CBStoreHouseRefreshControl](https://github.com/coolbeet/CBStoreHouseRefreshControl) - 一个效果很酷炫的下拉刷新控件。
 * [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - 一个下拉刷新打砖块的开源 Swift 库，能让用户在等待下拉刷新的时候边玩撞球游戏边等待。
 * [KYJellyPullToRefresh](https://github.com/KittenYang/KYJellyPullToRefresh) - 实现弹性物理效果的下拉刷新，神奇的贝塞尔曲线，配合UIDynamic写的一个拟物的下拉刷新动画。
 * [MHYahooParallaxView](https://github.com/michaelhenry/MHYahooParallaxView) - 类似于Yahoo Weather和News Digest首屏的视差滚动。 
 * [SDRefreshView](https://github.com/gsdios/SDRefreshView) - 简单易用的上拉和下拉刷新（多版本细节适配）。
 * [ZLSwiftRefresh](https://github.com/MakeZL/ZLSwiftRefresh) - swift下拉刷新/上拉加载更多，支持自定义动画，集成简单，兼容UITableView/CollectionView/ScrollView/WebView。
 * [BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh) - swift，上拉和下拉刷新。
 * [GearRefreshControl](https://github.com/andreamazz/GearRefreshControl) -  swift，上拉和下拉刷新。
 * [refresher](https://github.com/jcavar/refresher) -  swift，上拉和下拉刷新。
 * [可展开/收缩的下拉菜单--SvpplyTable](http://d.cocoachina.com/code/detail/237753) -  一个可展开可收缩的下拉菜单，类似Svpply app。
 * [ODRefreshControl](https://github.com/Sephiroth87/ODRefreshControl) - 原iOS6上的橡皮糖刷新样式，很有意思。现在也很多大的 App 在用，比如虾米音乐和 QQ 客户端。
 * [PullToMakeSoup](https://github.com/Yalantis/PullToMakeSoup) - PullToMakeSoup, 自定义下拉刷新的动画效果：煮饭, Yalantis新作！
 * [TwitterCover](https://github.com/cyndibaby905/TwitterCover) -  Twitter iOS客户端的下拉封面模糊效果。
 * [Replace-iOS](https://github.com/MartinRGB/Replace-iOS) - Replace-iOS 让人眼前一亮的下拉刷新（iOS）。
 * [Animations](https://github.com/KittenYang/Animations) - 封装了一下，使用的时候只要两行代码。一些动画的飞机稿，都是一些单独分离出来的用于测试的子动画，现在统一归类一下。
 * [PullToBounce](https://github.com/entotsu/PullToBounce) - 下拉刷新的动画 for UIScrollView。
 * [WaterDropRefresh](https://github.com/li6185377/WaterDropRefresh) - 仿Path 水滴的下拉刷新效果 还有视差滚动。
 * [ESRefreshControl](https://github.com/EnjoySR/ESRefreshControl) - 仿新浪微博、百度外卖、网易新闻下拉刷新样式Demo（仅供参考）。
 * [WaveRefresh](https://github.com/alienjun/WaveRefresh) - 下拉刷新水波纹动画。
 * [DGElasticPullToRefresh](https://github.com/gontovnik/DGElasticPullToRefresh) - 是一款带有弹性效果的 iOS 下拉刷新组件。
 * [CALayerAnimationDemoh](https://github.com/wuwen1030/CALayerAnimationDemoh) - 双向注水动画下拉刷新组件,使用CALayer的mask实现。

##### 模糊效果
 * [FXBlurView](https://github.com/nicklockwood/FXBlurView) - 是一个UIView子类，支持iOS5.0以上版本，支持静态、动态模糊效果，继承与UIView的模糊特效。
 * [VVBlurPresentation](https://github.com/onevcat/VVBlurPresentation) -很简单易用的在原来viewconntroller基础上做模糊，然后present新的viewcontroller的。
 * [UICustomActionSheet](https://github.com/pchernovolenko/UICustomActionSheet) - 通过模糊背景来着重强调与菜单相关的元素--对话框 里面已经收藏。
 * [SABlurImageView](https://github.com/szk-atmosphere/SABlurImageView) - 支持渐变动画效果的图像模糊化类库。P.S. 与前几天推存类库 SAHistoryNavigationViewController 是同一位作者。
 * [Blurable.swift](https://github.com/FlexMonkey/Blurable) - swift模糊组件。

##### AutoLayout
 * [Masonry](https://github.com/Masonry/Masonry) - Masonry是一个轻量级的布局框架，拥有自己的描述语法，采用更优雅的链式语法封装自动布局，简洁明了并具有高可读性（ [使用介绍1](http://adad184.com/2014/09/28/use-masonry-to-quick-solve-autolayout/)  [使用介绍2](http://ios.jobbole.com/81483/)），[iOS自适应前段库-Masonry的使用](http://www.cocoachina.com/ios/20150702/12217.html)），[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。[使用DEMO](https://github.com/lcddhr/DDMasonryTest) 视图居中显示、子视图含边距、视图等距离摆放、计算ScrollView的contentsize。
 * [Classy](https://github.com/cloudkite/Classy/) - Classy是一个能与UIKit无缝结合stylesheet(样式)系统。它借鉴CSS的思想，但引入新的语法和命名规则，[Classy官网](http://classy.as/getting-started/)，[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。
 * [ClassyLiveLayout](https://github.com/olegam/ClassyLiveLayout) - ClassyLiveLayout通过结合Classy stylesheets与Masonry一起使用，能够在运行的模拟器中微调Auto Layout约束实时显示效果的工具，[Masonry、Classy、ClassyLiveLayout介绍](http://www.jianshu.com/p/2ed5f7444900)。
 * [Snap](https://github.com/Masonry/Snap) - Snap是Masonry Auto Layout DSL的Swift版本，是一款轻量级的布局框架，使用了更良好的语法封装了AutoLayout。Snap支持iOS和OS X。
 * [SnapKit](https://github.com/SnapKit/SnapKit) - 就是“snap”， --swift 喜欢自动布局吗？当然喜欢！至少在storyboard中创建时会喜欢。 在代码中纯手工创建约束灰常痛苦，但幸运的是我们有了SnapKit，在board中用上它，你可以简单直观地编写约束了。。
 * [PureLayout](https://github.com/smileyborg/PureLayout) - PureLayout 是 iOS & OS X Auto Layout 的终极 API——非常简单，又非常强大。PureLayout 通过一个全面的Auto Layout API 扩展了 UIView/NSView, NSArray 和 NSLayoutConstraint，仿照苹果自身的框架。
 * [UIView-AutoLayout](https://github.com/smileyborg/UIView-AutoLayout) - 
Deprecated in favor of PureLayout, which includes OS X support:https://github.com/smileyborg/PureLayout。
 * [Cartography](https://github.com/robb/Cartography) - Cartography 是用来声明 Swift 中的 Auto Layout，无需输入任何 stringly 就可设置自己 Auto Layout 的约束声明。
 * [Auto-Layout-Showcase](https://github.com/philcn/Auto-Layout-Showcase) - swift,AutoLayout 进阶 Demo，宽高比约束、比例约束、不等约束、视差约束、低优先级约束等高级用法，无需写码即可进行复杂页面布局，Demo 还动态模拟了各屏幕下的效果。来自百度知道 iOS 小组的内部分享。
 * [UIView-FDCollapsibleConstraints](https://github.com/forkingdog/UIView-FDCollapsibleConstraints) - 一个AutoLayout辅助工具，最优雅的方式解决自动布局中子View的动态显示和隐藏的问题。第二个Demo模拟了一个经典的FlowLayout，任意一个元素隐藏时，底下的元素需要自动“顶”上来，配合这个扩展，你可以在IB里连一连，选一选，不用一行代码就能搞定。
 * [Autolayout_Demo](https://github.com/luodezhao/Autolayout_Demo) - 在项目中用自动布局实现的类似抽屉效果。
 * [当view隐藏的时候也隐藏其autolayout的NSLayoutAttribute](http://code.cocoachina.com/detail/320405/) - 当view隐藏的时候也隐藏其autolayout的NSLayoutAttribute，从而不用大量的代码工作。
 * [SDAutoLayout](https://github.com/gsdios/SDAutoLayout) - AutoLayout 一行代码搞定自动布局！支持Cell、Label和Tableview高度自适应，致力于做最简单易用的AutoLayout库。
 * [Neon.swift](https://github.com/mamaral/Neon) - 功能强大的 UI 布局神器。

##### 富文本
 * [RTLabel](https://github.com/honcheng/RTLabel) - RTLabel 基于UILabel类的拓展,能够支持Html标记的富文本显示，它是基于Core Text,因此也支持Core Text上的一些东西。32位，很久没有更新了。
 * [RTLabel](https://github.com/bingxue314159/RTLabel) - 富文本，RTLabel支持64位。 
 * [TYAttributedLabel](https://github.com/12207480/TYAttributedLabel) -  TYAttributedLabel。 简单易用的属性文本控件(无需了解CoreText)，支持富文本，图文混排显示，支持添加链接，image和UIView控件，支持自定义排版显示。
 * [TQRichTextView](https://github.com/TinyQ/TQRichTextView) - 用于做富文本视图控件显示，用于即时通讯的表情显示，以及资源评论的富文本显示。
 * [TTTAttributedLabel](https://github.com/mattt/TTTAttributedLabel) - 一个文字视图开源组件，是UILabel的替代元件，可以以简单的方式展现渲染的属性字符串。另外，还支持链接植入，不管是手动还是使用UIDataDetectorTypes自动把电话号码、事件、地址以及其他信息变成链接。[用TTTAttributedLabel创建变化丰富的UILabel](http://blog.csdn.net/prevention/article/details/9998575) - 网易新闻iOS版使用。
 * [MLEmojiLabel](https://github.com/molon/MLEmojiLabel) - 自动识别网址、号码、邮箱、@、#话题#和表情的label。可以自定义自己的表情识别正则，和对应的表情图像。(默认是识别微信的表情符号)，继承自TTTAttributedLabel，所以可以像label一样使用。label的特性全都有，使用起来更友好更方便。
 * [FXLabel](https://github.com/nicklockwood/FXLabel) - FXLabel是一个功能强大使用简单的类库，通过提供一个子类改进了标准的UILabel组件，为字体增加了阴影、内阴影和渐变色等，可以被用在任何标准的UILabel中。FXLabel还提供了更多控件，可以对字体行距、字体间距等进行调整。
 * [WFReader](https://github.com/TigerWf/WFReader) - 一款简单的coretext阅读器，支持文本选择、高亮以及字体大小选择等。
 * [WPAttributedMarkup](https://github.com/nigelgrange/WPAttributedMarkup) - WPAttributedMarkup is a simple utility category that can be used to easily create an attributed string from text with markup tags and a style dictionary。
 * [KMPlaceholderTextView](https://github.com/MoZhouqi/KMPlaceholderTextView) - 可显示多行 placeholder 的 textView，可以在IB里面设置 -- swift。
 * [HHFlashSwitch](https://github.com/mrchenhao/HHFlashSwitch) - 一个另类的UISwitch，选择后，背景水波扩散变色效果。 
 * [UUColorSwitch](https://github.com/zhangyu9050/UUColorSwitch) - Switch 开关动画效果,当打开开关时，Switch可实现平滑渲染过渡到父视图的效果。
 * [UITextViewDIYEmojiExample](https://github.com/zekunyan/UITextViewDIYEmojiExample) - [UITextView编辑时插入自定义表情-简单的图文混编](http://tutuge.me/2015/03/07/UITextView%E7%BC%96%E8%BE%91%E6%97%B6%E6%8F%92%E5%85%A5%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A1%A8%E6%83%85-%E7%AE%80%E5%8D%95%E7%9A%84%E5%9B%BE%E6%96%87%E6%B7%B7%E7%BC%96/)。 
 * [Shimmer](https://github.com/facebook/Shimmer) - BlingBling闪光效果，酷炫的Label的效果，可以用于加载等待提示。
 * [ZSSRichTextEditor](https://github.com/nnhubbard/ZSSRichTextEditor) - 适用于iOS的富文本WYSIWYG编辑器，支持语法高亮和源码查看。ZSSRichTextEditor包含所有WYSIWYG标准的编辑器工具。
 * [RichEditorView](https://github.com/cjwirth/RichEditorView) - swift，一套可定制富文本编辑器组件及示例。功能完整、代码简练、实现逻辑巧妙（编辑器核心与 WebView 结合，采用 HTML5 contentEditable 编辑模式，执行JS 配套命令 execCommand 实现富文本编辑功能）。
 * [DTCoreText](https://github.com/Cocoanetics/DTCoreText) - 可以解析HTML与CSS最终用CoreText绘制出来，通常用于在一些需要显示富文本的场景下代替低性能的UIWebView。[DTCoreText源码解析](http://blog.cnbang.net/tech/2630/)。
 * [CSGrowingTextView](https://github.com/cloverstudio/CSGrowingTextView) - 用作即时通讯文本框和评论文本框使用，可以显示多行输入。 
 * [MarkdownTextView](https://github.com/indragiek/MarkdownTextView) - 显示Markdown的TextView。 
 * [高仿微信限定行数文字内容](http://d.cocoachina.com/code/detail/300299) - 采用Autolayout高仿微信纯文字限定行数。
 * [FuriganaTextView](https://github.com/lingochamp/FuriganaTextView) - 实现复杂的日文韩文排版。
 * [ParkedTextField](https://github.com/gmertk/ParkedTextField) - 带固定文本的输入组件。 
 * [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) - swift 能够实现文字变形动画效果的Label，用Swift写的一个能够实现文字变形动画效果的Label，很炫。
 * [GJCFCoreText](https://github.com/zyprosoft/GJCFCoreText) - 图文混排。
 * [AttributedLabel](https://github.com/KyoheiG3/AttributedLabel) - 显示性能数量级 UILabel 的 AttributedLabel。无畏无惧、挑战权威。
 * [FFLabel](https://github.com/liufan321/FFLabel) - 自动检测 URLs, @username, #topic# 等关链词（提供响应扩展）。实用的标签文本小组件。
 * [TextFieldEffects](https://github.com/raulriera/TextFieldEffects) - 标准的UITextField有些枯燥么？来认识一下TextFieldEffects吧！废话不多说，只要看几个例子,是啊，都是些简单的dropin控制器。甚至可以在storyboard中使用IBDesignables。
 * [AutocompleteField](https://github.com/filipstefansson/AutocompleteField) - 可应用于 iOS 应用中文字输入框自动补全的场景, 兼容到 iOS 8。
 * [Splitflap.swift](https://github.com/yannickl/Splitflap) - 可用于快速给 iOS 应用创建文字翻转的动画效果。
 * [WordPress-Editor-iOS](https://github.com/wordpress-mobile/WordPress-Editor-iOS) - 一个文本编辑器 简书和新浪博客都在用。
 * [YYText](https://github.com/ibireme/YYText) - 功能强大的 iOS 富文本框架。

##### 图表
 * [PNChart](https://github.com/kevinzhow/PNChart) - 国内开源作者，动态的图表。
 * [swift-linechart](https://github.com/zemirco/swift-linechart) - 功能完整、实用的折线图组件。使用方便，参数配置简单。是不可多得的优质组件--swift。
 * [ios-charts](https://github.com/danielgindi/ios-charts) - 一款优秀 Android 图表开源库 MPAndroidChart 的 Swift 语言实现版（支持 Objective-C 和 Swift 调用）。缺省提供的示例代码为 Objective-C。
 * [TEAChart](https://github.com/xhacker/TEAChart) - xhacker/TEAChart 一个简洁的 iOS 图表库，支持柱状图、饼图以及日历等。
 * [YOChartImageKit](https://github.com/yasuoza/YOChartImageKit) - 支持在watchOS上绘制图表，看它最近更新挺勤快的，可以关注一下。
 * [RealtimeGradientText](https://github.com/kevinzhow/RealtimeGradientText) - Fun With CALayer Mask 刚好今天开源了一个有趣的项目 RealtimeGradientText，所以也好聊一下 CALayer 的 Mask，[说明](http://blog.zhowkev.in/2015/07/06/fun-with-mask/)。

##### 表相关与Tabbar
 * [SWTableViewCell](https://github.com/onevcat/SWTableViewCell) - 国内开源作者，带很多手势的表单元格。
 * [MCSwipeTableViewCell](https://github.com/alikaragoz/MCSwipeTableViewCell) - 带很多手势的表单元格。
 * [TMQuiltView](https://github.com/1000Memories/TMQuiltView) - 瀑布流。
 * [WaterfallFlowDemo](https://github.com/lengmolehongyan/WaterfallFlowDemo) - 一个简单的UICollectionView瀑布流布局演示demo。
 * [XLForm](https://github.com/xmartlabs/XLForm) - 很多表格类的table,写法更高冷一点，推荐使用。
 * [Eureka.swift](https://github.com/xmartlabs/Eureka) - Eureka 是 XLForm 的 Swift 的移植版本, 一个可以帮助开发者们快速构建 iOS 各种复杂表单的库, 具有较高的可扩展性, 方便自定制样式。
 * [RETableViewManager](https://github.com/romaonthego/RETableViewManager) - 可以十分方便地生成各种样式、各种功能的TableView。只要开发者能想到的列表效果或者功能，都可以利用这份代码迅速编写出来。比如，之前要实现一个填写各种资料的列表，可能需要很多代码，现在只需要几行代码就可以实现。 
 * [UIScrollSlidingPages](https://github.com/TomThorpe/UIScrollSlidingPages) - 允许添加多视图控件，并且可以横向滚动。有点类似于Groupon app。
 * [HBHorizontalTableView](https://github.com/izyhuang/HBHorizontalTableView) - swift，TableView 横向滚动小示例（仿照 AppStore 应用展示）。
 * [HorizontalScrollCell](https://github.com/mcelayir/HorizontalScrollCell) - HorizontalScrollCell是一款使用方便的水平方向可滚动的单元格，适用于UICollectionView中实现水片方向滚动视图。 。
 * [SYJiugonggeTableView](https://github.com/shiyuan17/SYJiugonggeTableView) - tableView封装的九宫格。
 * [UUChatTableView](https://github.com/ZhipingYang/UUChatTableView) - UUChatTableView 气泡聊天界面，支持文本、图片以及音频的气泡聊天界面。[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。
 * [Chats](https://github.com/acani/Chats) - 聊天 UI 示例程序。此项目应该只为演示或学习之用，没有服务器 -- swift。 
 * [Atlas-iOS](https://github.com/layerhq/Atlas-iOS) - 快速在iOS里集成聊天功能，类似开源版本的环信。Layer家开源了一套聊天app界面的解决方案.看起来很赞，很多蛮复杂的东西直接都帮封好了。不得不说现在做app开发真是很简单，大部分时间搭积木就可以了。[官方网站](https://atlas.layer.com/)。
 * [Chatto.swift](https://github.com/badoo/Chatto) - Chatto.swift:轻量级聊天应用框架及示例。文字及图片可扩展输入栏，汽泡效果等聊天核心特性，分页及自动布局完善。
 * [DLSlideView](https://github.com/agdsdl/DLSlideView) - DLSlideView对常见的顶部Tab页点击、滑动分页做了封装。它使用基于ViewController的container特性（而不是scrollview）来管理各个子页面，以支持无限分页，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。
 * [VOVCManager](https://github.com/pozi119/VOVCManager) - 页面管理器:1.跳转指定页面,只需要知道viewController的Class名,如果有storyboard,则需要指定storyboard名；2.无需添加基类；3.支持URLScheme跳转指定页面。
 * [MBXPageViewController](https://github.com/Moblox/MBXPageViewController) - 简洁快速的页面切换--MBXPageViewController，带有按钮控件的UIPageController，非常整洁、简单以及快速。该项目通过三种形式展示页面之间的切换，比如导航栏上的多个tab切换、页面左右两端箭头指示切换，以及使用分段控件。
 * [PagerTab](https://github.com/ming1016/PagerTab) - UIScrollView实现滑动转换页面，类似网易云音乐iOS版的页面滑动切换效果。
 * [GUITabPagerViewController](https://github.com/guilhermearaujo/GUITabPagerViewController) - 多个tab滑动切换。
 * [VOMetroLayoutDemo](https://github.com/pozi119/VOMetroLayoutDemo) - Metro风格的UICollectionView, 目前只支持横向布局,仅在iPad上应用。
 * [KYCellAnimation](https://github.com/KittenYang/KYCellAnimation) - 给UITableViewCell增加进入的动画。
 * [COBezierTableView](https://github.com/knutigro/COBezierTableView) - swift，通过编辑 Bezier 曲线四点位置设置 TableView 内 Cell 及对应按扭位置。实验效果很赞。
 * [RDVTabBarController](https://github.com/robbdimitrov/RDVTabBarController) - 一个TabBar组件，可以方便设置底部菜单的文字图片，点击效果，小红点提示等。
 * [LxTabBarController](https://github.com/DeveloperLx/LxTabBarController) - 改变了原生tabbar切换tab时的生硬效果，并加入滑动切换手势（有和界面上的其它手势发生冲突的风险，可根据具体项目予以关闭），[swift版本](https://github.com/DeveloperLx/LxTabBarController-swift)。
 * [WXTabBarController](https://github.com/leichunfeng/WXTabBarController) - 在系统 UITabBarController 的基础上完美实现了安卓版微信 TabBar 的滑动切换功能，单手操作 iPhone 6 Plus 切换 TabBar 一直是一件很痛苦的事情，而滑动切换是一种不错的解决方案，支持屏幕旋转。
 * [GooeyTabbar](https://github.com/KittenYang/GooeyTabbar) - 皮筋式弹性缩放工具栏示例及演示。
 * [横向展示文本内容的自定义cell](http://d.cocoachina.com/code/detail/298409) - 可以横向展示文本内容的自定义cell，根据文本无限滚动。
 * [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - UITableView-FDTemplateLayoutCell 是一个方便缓存 UITableViewCell 的高度的框架。
 * [ExpandingStackCells](https://github.com/jozsef-vesza/ExpandingStackCells) - 采用 UIStackView 实现表格单元格扩展内容显示示例及解决方案。
 * [FDStackView](https://github.com/forkingdog/FDStackView) - 可以将 UIStackView 的最低支持版本拉低到 iOS6，无需配置，没有代码侵染，扔到工程里后直接用系统 UIStackView 的 API 即可，同时兼容 Storyboard。 
 * [Sapporo](https://github.com/nghialv/Sapporo) - swift 单元格模型驱动的集合视图管理器组件。又一个超实用的“轮子”。
 * [MDIHorizontalSectionTableViewController](https://github.com/WeeTom/MDIHorizontalSectionTableViewController) - 根据产品需求开源了一个交互项目，可以理解为横向Section的TableView，section和cell同时支持拖拽，后续安卓版本也会开源出来。
 * [JZNavigationExtension](https://github.com/JazysYu/JZNavigationExtension) - 多功能导航控制器，可以透明返回栏。
 * [QuickRearrangeTableView](https://github.com/okla/QuickRearrangeTableView) - 基于 UITableView 的快速重排功能扩展子类。通过长按选定单元格然后滚动移动到指定位置。
 * [uicollectionview-reordering](https://github.com/nshintio/uicollectionview-reordering) - UICollectionViews的拖拽(拖动、移动)效果,[实例教程](http://nshint.io/blog/2015/07/16/uicollectionviews-now-have-easy-reordering/).
 * [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) - DZNEmptyDataSet算是一个很标准的iOS内建方式，适合用来处理空的table view和collection view。会自动将collection view处理完善，并将用户消息以合适美观的方式显示出来。每个iOS项目都可以自动处理。
 * [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell) - 另一个常见于很多应用中的UI组件，苹果应该考虑在标准的iOS SDK中加入一些类似的内容。Swipeable表格cell是这个pod的最佳描述，也是最好的。
 * [XLPlainFlowLayout](https://github.com/HebeTienCoder/XLPlainFlowLayout) - 可以让UICollectionView的header也支持悬停效果，类似于tableView的Plain风格。
 * [WMPageController](https://github.com/wangmchn/WMPageController) - 一个方便的 pageContrller 的控件，里面还包括滚动视图。
 * [PSTCollectionView](https://github.com/steipete/PSTCollectionView) - PSTCollectionView。
 * [LLRiseTabBar-iOS](https://github.com/lianleven/LLRiseTabBar-iOS) - 直接使用系统的特性实现的tabbar，比较简单。
 * [MTMaterialDelete](https://github.com/MartinRGB/MTMaterialDelete) - 非常有趣的Material Design动画，动画删除表里面的单元格。
 * [BusyNavigationBar](https://github.com/gmertk/BusyNavigationBar) - 进度条式NavigationBar导航条。
 * [ReorderableGridView-Swift](https://github.com/cemolcay/ReorderableGridView-Swift) - 拖拽排序卡片。
 

##### 隐藏与显示
 * [SlideTapBar](http://d.cocoachina.com/code/detail/286102) - 滚动栏菜单，向上滚动时隐藏tabbar，向下滚动马上显示tabbar。
 * [FoldingTabBar.iOS](https://github.com/Yalantis/FoldingTabBar.iOS) - 可折叠Tab Bar和Tab Bar Controller。
 * [LTNavigationBar](https://github.com/ltebean/LTNavigationBar) - LTNavigationBar为app导航栏添加动态着色效果，可自定义其背景色。Demo包含：1.变换背景色；2.滚动视图，导航栏和状态栏重叠。
 * [BLKFlexibleHeightBar](https://github.com/bryankeller/BLKFlexibleHeightBar) - 固定Header的效果库，一个拥有非常灵活高度的标题栏，可以为使用软件的用户提供更多的阅读和滑动空间，现在已经被众多app所采用。

##### HUD与Toast
 * [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - 最多人用的loading。
 * [EBuyCommon](https://github.com/LvJianfeng/EBuyCommon) - 1.基于MBProgressHUD实现得图形加载提示方式，及其它标题方式提醒。2.弹窗。
 * [SVProgressHUD](https://github.com/TransitApp/SVProgressHUD) - SVProgressHUD的loading，如果你需要定制化的等待提示器，这个就是了（也许是最好的）。
 * [ProgressHUD](https://github.com/relatedcode/ProgressHUD) - ProgressHUD的loading，使用最简单。
 * [MMProgressHUD](https://github.com/mutualmobile/MMProgressHUD) - 设置HUD出现和消失的方式（包括上下、左右、淡入淡出、放大缩小等等），设置HUD的内容（可以在HUD中加入帧动画、动态图片等等），设置HUD出现时的底部覆盖层颜色，等等。总而言之，这是一份集大成的HUD代码。慢慢看视频吧，囊括了所有效果。
 * [WSProgressHUD](https://github.com/devSC/WSProgressHUD) - 一个小巧精致的HUD,支持添加到自定义View上, 还有更多小细节.。

##### 对话框
 * [WCAlertView](https://github.com/m1entus/WCAlertView) - 自定义的对话框。
 * [IOS7AlertView](https://github.com/wimagguc/ios-custom-alertview) - IOS7AlertView的对话框。
 * [AMSmoothAlert](https://github.com/mtonio91/AMSmoothAlert) - 动画效果不错，最多star，但不支持arm64。
 * [DQAlertView](https://github.com/dinhquan/DQAlertView) - 扁平化的样式不错。
 * [HHAlertView](https://github.com/mrchenhao/HHAlertView) - 一个简易的alertview  有三种样式，有成功，失败，和警告三种样式，支持Delegate和block两种回调。
 * [MJPopupViewController](https://github.com/martinjuhasz/MJPopupViewController) - 实现弹出视图的各种弹出和消失效果，包括淡入淡出（fade in，fade out），从屏幕上方飞进，下方飞出，从屏幕左方飞进，右方飞出等等效果，弹窗。
 * [MMPopupView](https://github.com/adad184/MMPopupView) - 弹出框的基类组件（弹窗）。
 * [Menu](https://github.com/fengchuanxiang/Menu) - 项目中可能会用到的常用菜单，以后有时间会继续补充，弹窗。 
 * [EasyTipView](https://github.com/teodorpatras/EasyTipView) - 弹出提示框类及演示示例。同样地，API 简单、易用。好“轮子”，弹窗。  
 * [kxmenu](https://github.com/kolyvan/kxmenu) - kxmenu弹出菜单，点击视图上任意位置的按钮，会弹出一个菜单，并且有个小箭头指向点击的按钮，类似气泡视图。弹出的菜单位置会根据按钮的位置来进行调整。 
 * [QBPopupMenu](https://github.com/questbeat/QBPopupMenu) - QBPopupMenu弹出菜单，实现类似 UIMenuItem 的弹出菜单按钮。点击按钮，会弹出一个菜单，上面可以排列多个按钮。纯代码实现，不需要任何图片。
 * [STModalDemo](https://github.com/zhenlintie/STModalDemo) - 弹出视图（通知，提示，选择，窗口）。
 * [TAOverlay](https://github.com/TaimurAyaz/TAOverlay) - TAOverlay可通过叠加层展示有用的信息，可自定义文本和背景色，添加阴影和模糊效果，以及更改字体大小或者用自定义图片替换页面上的icon。
 * [UICustomActionSheet](https://github.com/pchernovolenko/UICustomActionSheet) - 通过模糊背景来着重强调与菜单相关的元素--模糊效果 里面已经收藏。
 * [ActionSheetPicker-3.0](http://code.cocoachina.com/detail/232178) - 该项目是此前热门项目ActionSheetPicker的新版本，快速复制了iOS 8上的下拉 UIPickerView/ActionSheet功能。
 * [MJAlertView](https://github.com/mayuur/MJAlertView) - 3D效果转场效果警示图--MJAlertView。
 * [SwiftyDrop](https://github.com/morizotter/SwiftyDrop) - 轻量、易用的小清新弹出列表及信息提示组件真心不错。
 * [PSTAlertController](https://github.com/steipete/PSTAlertController) - 兼容 iOS7的 XXAlertController，接口跟UIAlertController 一模一样，做到高低版本通用。
 * [PCLBlurEffectAlert.swfit](https://github.com/hryk224/PCLBlurEffectAlert) - 细节定制较丰富的弹出警报窗口组件。
 * [GSAlert.swfit](https://github.com/wxxsw/GSAlert) - 苹果在iOS8推出了全新的UIAlertController，旧的UIAlertView和UIActionSheet渐渐被废弃，但如果你仍然支持iOS7系统，你将不得不写两套代码。GSAlert解决了这个问题。

##### 其他UI
 * [AwesomeMenu](https://github.com/levey/AwesomeMenu) - 最多人用的Path菜单。
 * [DCPathButton](https://github.com/Tangdixi/DCPathButton) - Path，4.0的弹出菜单，呼出或者关闭菜单时，多个小图标会分别按照逆时针和顺时针的方向进行滚动。
 * [SphereMenu](https://github.com/itouch2/SphereMenu) - 利用UIDynamicAnimator的有趣的菜单，path类似。 
 * [KYGooeyMenu](https://github.com/KittenYang/KYGooeyMenu) - KYGooeyMenu 是一个具有 Gooey Effects 带粘性的扇形菜单控件(卫星菜单、path)。
 * [LiquidFloatingActionButton](https://github.com/yoavlt/LiquidFloatingActionButton) - 卫星弹出菜单。
 * [JZMultiChoicesCircleButton](https://github.com/JustinFincher/JZMultiChoicesCircleButton) - 三维多选按钮。
 * [TwitterPaggingViewer](https://github.com/xhzengAIB/TwitterPaggingViewer)  - 多个Tableview，左右滑动。
 * [CircularProgressControl](https://github.com/carantes/CircularProgressControl) - Circular Progress Control using CAShapeLayer ，环形进度控制条。
 * [KDCircularProgress](https://github.com/kaandedeoglu/KDCircularProgress) -  KDCircularProgress是使用swift制作的色彩炫丽的进度条，可以加入多种颜色来控制进度条的渐变效果。 
 * [TextProgress](https://github.com/cgwangding/TextProgress) - 自定义实现数字进度条：1、可以自定义数字（0-100），填充的比例为当前设置的数字，2、可以实现自定义填充颜色，上下部分都可以，3、可以自定义边界的颜色4、实现了水波动画，可以设置打开或关闭。
 * [SDProgressView](https://github.com/gsdios/SDProgressView) - 简便美观的进度指示器，此系列共有六种样式的进度指示器。
 * [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) -  loading 进度条动画，有20-30多种，是在此[DGActivityIndicatorView](https://github.com/gontovnik/DGActivityIndicatorView) 基础上做得修改。
 * [LoopProgressDemo](https://github.com/saitjr/LoopProgressDemo) - 环形渐变进度条。
 * [环形渐变进度条实现](http://www.superqq.com/blog/2015/08/12/realization-circular-gradient-progress/)， 
 * [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) - 做的很棒的iOS下的PagerTabStrip。 
 * [ASProgressPopUpView](https://github.com/alskipp/ASProgressPopUpView) - 弹出的进度条显示进度。
 * [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - 一个自动生成好看的颜色的 Swift 库，RandomColorSwift。
 * [HexColorService](https://github.com/ChangweiZhang/HexColorService) - 将16进制颜色字符串转成UIColor。
 * [Rainbow](https://github.com/NorthernRealities/Rainbow) - 旨在提高代码可读性及易用性的 UIColor 扩展，它使原先有限的预定义颜色（方法）选择，扩展至超过 1200 种。
 * [UIColor-ChineseTraditionalColors](https://github.com/zhxnlai/UIColor-ChineseTraditionalColors) - 中国传统颜色引用 UIColor 扩展。“UIColor.桃红()，UIColor.竹青() ...”，共158种。 
 * [类似美团的下拉菜单](http://code.cocoachina.com/detail/284158) - 类似美团的下拉菜单，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。 
 * [类似美团的下拉选项](http://code4app.com/ios/%E7%B1%BB%E4%BC%BC%E7%BE%8E%E5%9B%A2%E7%9A%84%E4%B8%8B%E6%8B%89%E9%80%89%E9%A1%B9/538606d4933bf06e0a8b496e) -  类似于美团、大众点评的下拉菜单选项，code4app代码，评论代码有瑕疵。
 * [CRMediaPickerController](http://code.cocoachina.com/detail/284267) - 一个简单易用的图片/视频选择器。1.可同时选择照片和视频。 2.挑选范围有Camera、Camera Roll、Photo Library以及最近拍摄的照片和视频。3.可自定义UIImagePickerController属性（Camera Overlay、Camera Device、Camera View Transform以及allowsEditing）。4.支持横屏和竖屏5.原生的iOS UI。，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。 
 * [MDCSwipeToChoose](https://github.com/modocache/MDCSwipeToChoose) - MDCSwipeToChoose可简单地添加滑动手势来调用UIView，并使用该行为提供了一个组件以创建类似Tinder app的like或者dislike界面的轻扫。基于轻扫的方向，你可以决定执行什么样的行为，并且你可以自定义文本颜色和图片。该项目适用于教学用的抽认卡、图片查看器以及其他等。 
 * [iOS Material Design库](http://d.cocoachina.com/code/detail/285611) - 该项目借鉴于谷歌的Material Design guideline，用户可自定义背景色。 
  * [Material-Controls-For-iOS](https://github.com/fpt-software/Material-Controls-For-iOS) - Material Design风格的各种控件，非常完整全面。 
 * [ZMaterialDesignUIButton](https://github.com/richzertuche/ZMaterialDesignUIButton) - Swift Material Design UIButton。
 * [MediumScrollFullScreen](https://github.com/pixyzehn/MediumScrollFullScreen) - Medium的可扩展滚动页面，上下滚动时，全屏显示内容，并自然消隐上下菜单。由此项目感知，作者是一位很注重细节的开发者，他的另外[几个菜单类项目](https://github.com/pixyzehn)也都不错，值得参考，比如：PathMenu, MediumMenu 等。
 * [WZFlashButton](https://github.com/SatanWoo/WZFlashButton) - WZFlashButton，点击后button里面出现水波扩散效果。
 * [Twinkle](https://github.com/piemonte/Twinkle) - 为字体加上钻石版闪耀的效果。使用Swift编写。 
 * [ios-multi-back-button](https://github.com/palmin/ios-multi-back-button) - 可替换内置的UInavigationController返回按钮，长按左上角的返回按钮，实现多层级的快速返回。
 * [ASDayPicker](http://code.cocoachina.com/detail/226543) - 适用于iOS (iPhone)的日期选择器(时间选择器)，类似于Calendar app的周视图。
 * [today extension](http://adad184.com/2014/10/29/2014-10-29-how-to-setup-today-extension-programmatically/) - 用纯代码构建一个Widget(today extension) 。
 * [FSCalendar](https://github.com/f33chobits/FSCalendar) - 日历视图，带有微妙和平滑的滚动效果，可自定义外观--国人。
 * [CVCalendar](https://github.com/Mozharovsky/CVCalendar) - 是一个方便开发者集成自定义日历视图到自己 iOS 应用的项目, 支持 Storyboard 和手动配置, 使用 CocoaPods 进行安装, 提供了丰富的 API 供开发者使用。
 * [HSDatePickerViewController](https://github.com/EmilYo/HSDatePickerViewController) - 带有Dropbox Mailbox感觉的时间日期选择器(时间选择器)。启动是背景被模糊化。界面也是主流的扁平化风格。 
 * [HZQDatePickerView](https://github.com/huzhiqin/HZQDatePickerView) - 自定义时间选择器(日期选择器)，包括开始日期和结束日期两种类型。
 * [CFCityPickerVC](https://github.com/nsdictionary/CFCityPickerVC) - 城市选取控制器。
 * [JTCalendar](https://github.com/jonathantribouharet/JTCalendar) - iOS下优美的 Calendar 组件，做 GTD 类 App 必备。
 * [Persei](https://github.com/Yalantis/Persei) - 动画隐藏或显示顶部菜单支持库及示例项目。--swift
 * [PDTSimpleCalendar](https://github.com/jivesoftware/PDTSimpleCalendar) - 是iOS最棒的日历组件了。你可以在各个方面对它进行定制，无论是运行逻辑还是外观方面。
 * [Form](https://github.com/hyperoslo/Form) - JSON 驱动的 Form表单系统，复杂的表单填写类 App 极其需要（比如淘宝呢！）。
 * [SwiftyFORM](https://github.com/neoneye/SwiftyFORM) - swift 表单输入框架（亮点是表单验证规则引擎），是我见过地最易用的 Swift 表单组件。
 * [SwiftSpinner](https://github.com/icanzilb/SwiftSpinner) - SwiftSpinner是使用swift制作的一款精致带感的指示器，并且连带有字体信息显示，模糊背景，半透明，扁平化等IOS8的效果。
 * [AKPickerView-Swift](https://github.com/Akkyie/AKPickerView-Swift) - 一款小而美的 3D 效果选择器。
 * [ImagePickerSheet](https://github.com/larcus94/ImagePickerSheet) - 图片或视频选择器（可多选）组件及其示例项目。
 * [iOS-RatingBar](https://github.com/saiwu-bigkoo/iOS-RatingBar) - iOS-RatingBar swift版的评分控件,跟Android的RatingBar一样有两种模式，评分模式和只读模式'支持视图编辑，自定义星星数量，评分等级,另外还能支持非整数星，0.5颗星，0.1颗星,可以开启动画效果。
 * [RKNotificationHub](https://github.com/cwRichardKim/RKNotificationHub) - 快速给 UIView 添加上炫酷的通知图标（Badge、红点、提示）。 
 * [WZLBadge](https://github.com/weng1250/WZLBadge) - Badge，支持横竖屏支持iOS5~iOS8允许高度定制化，包括“红点”的背景颜色，文字(字体大小、颜色)，位置等。[说明](http://code.cocoachina.com/detail/316890/%E4%B8%80%E8%A1%8C%E4%BB%A3%E7%A0%81%E5%AE%9E%E7%8E%B0%E5%A4%9A%E9%A3%8E%E6%A0%BC%E7%9A%84%E6%8E%A8%E9%80%81%E5%B0%8F%E7%BA%A2%E7%82%B9/). 
 * [BubbleTransition](https://github.com/andreamazz/BubbleTransition) - 以气泡膨胀和缩小的动画效果来显示和移除 controller，Uber的就是这种取消操作的方式。
 * [KYFloatingBubble](https://github.com/KittenYang/KYFloatingBubble) - 类似iOS7中Game Center浮动气泡的效果。
 * [DKNightVersion](https://github.com/Draveness/DKNightVersion) - DKNightVersion 是一个支持夜间模式切换的框架。
 * [EasyUIControl](https://github.com/sx1989827/EasyUIControl) - 一个可以简化界面ui的控件框架。
 * [LxGridView-oc](https://github.com/DeveloperLx/LxGridView) [LxGridView-swift](https://github.com/DeveloperLx/LxGridView-swift) - 利用UICollectionView模仿iOS系统桌面图标的交互，作用如动图。
 * [QQBtn](https://github.com/ZhongTaoTian/QQBtn) - 仿QQ未读消息弹性按钮动画，达到和手机QQ未读信息一样的动画效果，效果基本实现。
 * [GMStepper](https://github.com/gmertk/GMStepper) - swift 带动画效果、支持手势滑动操作的步进标签。
 * [TZStackView](https://github.com/tomvanzummeren/TZStackView) - OS 9 UIStackView 功能模拟实现于 iOS 7/ iOS 8 内。
 * [LayoutTrait](https://github.com/441088327/LayoutTrait) - swift 一个小类库。 做iPad 多任务分屏 适配的同学可以看一下。
 * [HACursor](https://github.com/HAHAKea/HACursor) - HACursor，是一个对横向ScrollView中的视图进行管理的UI控件。只要几行代码就可以集成类似于网易新闻对主题页面进行排序，删除操作的功能。
 * [ZTPageController](https://github.com/IOStao/ZTPageController) - 模仿网易新闻和其他新闻样式做的一个菜单栏，栏中有各自的控制器，其中有4中展示样式’网易style' ’搜狐style' ’腾讯style1' ’网易style2' 。 
 * [Ruler](https://github.com/nixzhu/Ruler) - 尺子。
 * [HUMSlider](https://github.com/justhum/HUMSlider) - HUMSlider是一款能够自动显示刻度记号的滑竿，滑动到某处，该处的刻度会自动上升，两边还能配置图像。支持代码或storyboard中实现。
 * [JDSelectedDemo](https://github.com/zhangli4659507/JDSelectedDemo) - 仿京东筛选菜单实现。
 * [BTNavigationDropdownMenu](https://github.com/PhamBaTho/BTNavigationDropdownMenu) -  下拉列表暨导航标题组件。简单、直接、易用 -swift。
 * [3DTouchDemo](https://github.com/luzefeng/3DTouchDemo) - 详细介绍了每个参数的含义和3Dtouch的入口，保证包学包会。
 * [3DTouchSample](https://github.com/RichardLeung/3DTouchSample) - 3D-Touch的功能分为两个部分：Shortcut和Preview。
 * [SBShortcutMenuSimulator](https://github.com/DeskConnect/SBShortcutMenuSimulator) - 教你如何在模拟器上测试 3D Touch 功能!
 * [InceptionTouch.swift](https://github.com/richzertuche/InceptionTouch) - 让没有 3D Touch 设备也有类似交互体验的 InceptionTouch 类（基于 UITextView 实现，支持日期，链接，电话号码，地址触摸响应）。
 * [仿LOL滚动视图](http://code.cocoachina.com/view/128287) - 仿LOL滚动视图。
 * [答题选择切换页](http://code.cocoachina.com/view/128281) - 将scrollview和tableview封装在一起，在初始化的时候简单的将数据带上，就可以一页一页的左右来回滑动。
 * [CharacterPickerView](https://github.com/alafighting/CharacterPickerView) - 可实现三级联动的选择器，高仿iOS的滚轮控件,可实现单项选择，并支持一二三级联动效果。
 * [SCTrelloNavigation](https://github.com/SergioChan/SCTrelloNavigation) - 类似trello的导航动效控件实现。
 * [XTPaster](https://github.com/Akateason/XTPaster) - 贴纸功能出现在很多图片社交中, 就是图片上面贴图片, 对贴纸而言就是需要控制贴纸的位置,旋转,大小,[如何使用](http://www.jianshu.com/p/d873d348bbfb)。
 * [RGCategoryView](https://github.com/refinemobi/RGCategoryView) - 仿了个苏宁易购的分类页面。
 * [TWControls.swift](https://github.com/txaidw/TWControls) - 简单的开关和按钮控制器,使用闭包来执行由控件触发的操作。
 * [Instructions.swift](https://github.com/ephread/Instructions) - 可定制嵌入式操作指引框架及演示。
 * [LLPieCharts](https://github.com/Lves/LLPieCharts) - LLPieCharts iOS 绘制饼图，[教程](http://www.lvesli.com/?p=339)。
 * [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) - BEMCheckBox 是一个用于 iOS 应用上构建漂亮, 高度可定制化动画效果的复选框类库, 最低支持到 iOS 7 系统, 有多种不同风格的动画效果可供选择。
 * [STPopup](https://github.com/kevin0571/STPopup) - 提供了一个可在 iPhone 和 iPad 上使用的具有 UINavigationController 弹出效果的 STPopupController 类, 并能在 Storyboard 上很好的工。
 * [VBFPopFlatButton](https://github.com/victorBaro/VBFPopFlatButton) - 通过几条线段实现的非常Q萌的动画按钮效果。
 * [ZSeatSelector](https://github.com/richzertuche/ZSeatSelector) - 电影院位置排座位。
 * [CustomSearchBar](https://github.com/zangqilong198812/CustomSearchBar) - 自定义searchbar,类似于instagram的搜索框效果。
 * [LNPopupController](https://github.com/LeoNatan/LNPopupController) - AppleMusic式pop up，弹出是页面，可以上下拉动。
 * [DGRunkeeperSwitch](https://github.com/gontovnik/DGRunkeeperSwitch/) - 动画segment，节选器。

========
#### 动画
 * [Core Animation笔记，基本的使用方法](http://www.starming.com/index.php?v=index&view=62) - Core Animation笔记，基本的使用方法：1.基本动画，2.多步动画，3.沿路径的动画，4.时间函数，5.动画组。
 * [awesome-ios-animation](https://github.com/sxyx2008/awesome-ios-animation) - [iOS Animation 主流炫酷动画框架(特效)收集整理](https://github.com/sxyx2008/DevArticles/issues/91) 收集整理了下iOS平台下比较主流炫酷的几款动画框架。
 * [awesome-animation](https://github.com/Animatious/awesome-animation) -  在内的十多位童鞋们一起发起的一起动画开源组正式成立啦~Github组织名称：Animatious，这是我们第一期成员先前开源的一些动效库，我们的第一个合作开源项目正在紧锣密鼓的准备~请大家期待设计和代码的碰撞吧。

##### 侧滑与右滑返回手势
 * [SloppySwiper](https://github.com/fastred/SloppySwiper) - iOS系统自带的UINavigationController要7.0才支持，但不过该手势只能从屏幕左侧边缘识别，如果要扩大到整个屏幕范围怎么办？配合一个SloppySwiper无需代码就可以轻松实现。此库支持iOS5.0以上版本（另外：Nav的title滑动不明显，本人写了2个类似的控件），[SloppySwiper-demo](https://github.com/Tim9Liu9/SloppySwiper-Example) ：代码方式与storyboard方式。
 * [SCNavigation](https://github.com/singro/SCNavigation) - UINavigation可以右滑返回，隐藏UINavigationBar。
 * [UINavigationController-YRBackGesture](https://github.com/YueRuo/UINavigationController-YRBackGesture) - 支持右滑返回手势，标题栏不动。
 * [GHSidebarNav](https://github.com/gresrun/GHSidebarNav) - 现在比较流行使用侧开(侧滑)菜单设计。试了不少控件，感觉GHSidebarNav最成熟，尤其对纯代码创建的界面兼容性最好。[在Storyboard中使用GHSidebarNav侧开菜单控件](http://www.cnblogs.com/zyl910/archive/2013/06/14/ios_storyboard_sidemenu.html)。
 * [iOS-Slide-Menu](https://github.com/aryaxt/iOS-Slide-Menu) - 能够类似Facebook和Path那样弹出左右边栏侧滑菜单,还支持手势。多种可以自定义的属性 (非常不错)。
 * [ECSlidingViewController](https://github.com/ECSlidingViewController/ECSlidingViewController) - 侧滑菜单。
 * [JASidePanels](https://github.com/gotosleep/JASidePanels) - 侧滑菜单,有左右菜单，有pop功能，支持手势侧滑,本人使用中：简单。
 * [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) - 让 Tabbar items能显示萌萌的动画。
 * [tabbar图标动画](http://code.cocoachina.com/detail/284346) - tabbar上图标的动画实现，[源码推荐说明](http://www.cocoachina.com/ios/20150205/11116.html)。
 * [SideMenu](https://github.com/Yalantis/Side-Menu.iOS/tree/master/SideMenu) - swift实现，一款带动画效果可定制 Slide Menu，可以学习其动画实现思路。P.S. 对于Hamburger式菜单，虽然很常用，不过，苹果并不鼓励使用，甚至有开发小组对其弊病用自家上线应用前后数据对比进行了抨击。
 * [RESideMenu](https://github.com/romaonthego/RESideMenu) - 侧开菜单，qq类似。
 * [JHMenuTableViewDemo](https://github.com/Jiahai/JHMenuTableViewDemo) - 仿网易邮箱列表侧滑菜单。
 * [SlideMenuView](https://github.com/xudafeng/SlideMenuView) - 炫酷侧滑菜单布局框架，[Android版本的一致实现](Android 版本的一致实现请见：https://github.com/xudafeng/SlidingMenu)。
 * [QQConfiguration](https://github.com/shinept/QQConfiguration) - swift，QQ-iPhone端框架，左侧菜单栏拖动手势。
 * [KGFloatingDrawer](https://github.com/KyleGoddard/KGFloatingDrawer) - 侧滑菜单，qq类似，KyleGoddard/KGFloatingDrawer：一款适合于大屏手机或平板的浮动抽屉式导航界面组件。效果很赞- 侧开菜单，qq类似（与RESideMenu类似）。
 * [AIFlatSwitch](https://github.com/cocoatoucher/AIFlatSwitch) - 一款带平滑过渡动画的 Switch 组件类，类相同风格的 Menu/Back[HamburgerButton](https://github.com/fastred/HamburgerButton),类似相同风格的 Menu/Close[hamburger-button](https://github.com/robb/hamburger-button).
 * [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) - 在应用中采用链式写出酷炫的动画效果, 使代码更加清晰易读，利用block实现的链式编程。
 * [WXGSlideMenuDemo](https://github.com/WXGBridgeQ/WXGSlideMenuDemo) - 个简单实现侧拉（侧滑）菜单的小demo，供初学者共同学习、练习使用。
 * [PKRevealController](https://github.com/pkluz/PKRevealController) - PKRevealController是一个可以滑动的侧边栏菜单（可向左、向右或者同时向两侧），只需手指轻轻一点（或者按一下按钮，但是这样滑动时不够炫酷），这类控制的其他库，而PKRevealController是最棒的。安装简便，高度定制且对手势识别良好。可以当做一个标准控件用在iOS SDK中。
 * [SwiftPages](https://github.com/GabrielAlva/SwiftPages) - 高可定制类似 Instagram 视图滑动切换功能类库。API 简单、易用。
 * [FlipBoardNavigationController](https://github.com/michaelhenry/FlipBoardNavigationController) - FlipBoardNavigationController。
 * [MMDrawerController](https://github.com/mutualmobile/MMDrawerController) - 最多人用的一个有关侧边“抽屉”导航框架，里面还有很多你意想不到的交互效果，侧滑。
 * [UIWebView翻页返回效果](http://code.cocoachina.com/detail/316925/UIWebView%E7%BF%BB%E9%A1%B5%E8%BF%94%E5%9B%9E%E6%95%88%E6%9E%9C%EF%BC%88%E5%8F%98%E9%80%9A%E6%96%B9%E6%B3%95%EF%BC%89/) - UIWebView翻页返回效果（变通方法）。
 * [LLSlideMenu](https://github.com/lilei644/LLSlideMenu) - 一个弹性侧滑菜单,弹性动画原理借鉴该项目中阻尼函数实现。


##### gif动画
 * [UIImageView-PlayGIF](https://github.com/yfme/UIImageView-PlayGIF) - UIImageView-PlayGIF。
 * [YLGIFImage](https://github.com/liyong03/YLGIFImage) - YLGIFImage。
 * [YLGIFImage-Swift](https://github.com/liyong03/YLGIFImage-Swift) - YLGIFImage-Swift。
 * [droptogif](https://github.com/mortenjust/droptogif) -  droptogif视频拖拽到应用窗口后自动转换为 GIF 动画（其转换进程动画效果也超赞）。

##### 其他动画
 * [popping](https://github.com/schneiderandre/popping) - popping是一个POP 使用实例工程 
 * [SinaMenuView](https://github.com/xhzengAIB/SinaMenuView) - 用POP动画引擎写的Sina微博的Menu菜单。
 * [MMTweenAnimation](https://github.com/adad184/MMTweenAnimation) - facebook POP的自定义动画扩展(基于POPCustomAnimation) 提供10种函数式动画。
 * [ZQLRotateMenu](https://github.com/pingguo-zangqilong/ZQLRotateMenu) - 这是一个旋转视图的选择器。
 * [CoolLoadAniamtion](https://github.com/pingguo-zangqilong/CoolLoadAniamtion) - 一个简单但是效果不错的loading动画。
 * [SequenRotateAnimation](https://github.com/pingguo-zangqilong/SequenRotateAnimation) - 一个简单的loading次序动画。
 * [SYAppStart](https://github.com/441088327/SYAppStart) - App启动插画的自定义过度。
 * [VJDeviceSpecificMedia](https://github.com/victorjiang/UIImage-VJDeviceSpecificMedia/) - [如何根据设备选择不同尺寸的图片](http://www.imooc.com/wenda/detail/249271) 可以通过设置不同尺寸设备的LaunchImage，来使得App适配这些设备，要是在不同不同尺寸设备上使用不同大小的图片，则需要在代码中一一判断，然后加载。 
 * [RMParallax](https://github.com/michaelbabiy/RMParallax) - RMParallax是一个app启动页引导开源项目，除了细微的翻页视差效果，描述文本的过渡也非常美观（版本新特性、导航页、引导页）。
 * [ADo_GuideView](https://github.com/Nododo/ADo_GuideView) - 转动的用户引导页(模仿网易bobo) 因为没有从app包里抓到@3x的图片,建议在iPhone5模拟器运行,保证效果~ （版本新特性、导航页、引导页）。
 * [CoreNewFeatureVC](https://github.com/nsdictionary/CoreNewFeatureVC) - 版本新特性（引导页），1.封装并简化了版本新特性启动视图！2.添加了版本的本地缓存功能，3.集成简单，使用方便，没有耦合度，4.支持block回调（版本新特性、导航页、引导页）。
 * [MZGuidePages](https://github.com/MachelleZhang/MZGuidePages) - 自己写的通用导航页，可以直接引入工程使用，请参考案例（版本新特性、导航页、引导页）。
 * [ABCIntroView](https://github.com/AdamBCo/ABCIntroView) - ABCIntroView是一个易于使用的入门类，让你到达主屏幕之前介绍你的应用程序（版本新特性、导航页、引导页）。
 * [Spring](https://github.com/MengTo/Spring) - Spring是一个Swift编写的开源库，可简化Swift编写的iOS动画。支持shake、pop、morph、squeeze、wobble、swing、flipX、flipY、fall、squeezeLeft、squeezeRight以及squeezeDown等多种动画形式，用 IBDesignable 让使用者可以在 Xcode 中快速设置动画效果。
 * [KYBezierBounceView](https://github.com/KittenYang/KYBezierBounceView) - 手势控制贝塞尔曲线，取消手势贝塞尔曲线会有反弹效果。
 * [cadisplaylinkanduibezierpath](http://kittenyang.com/cadisplaylinkanduibezierpath/) - CADisplayLink结合UIBezierPath的神奇妙用。
 * [KYCuteView](https://github.com/KittenYang/KYCuteView) - 实现类似QQ消息拖拽消失的交互+GameCenter的浮动小球效果，[分析](http://kittenyang.com/drawablebubble/)。
 * [KYWaterWaveView](https://github.com/KittenYang/KYWaterWaveView) - 一个内置波浪动画的UIView，里面有鱼跳跃水溅起来的效果。
 * [KYPingTransition](https://github.com/KittenYang/KYPingTransition) - 实现圆圈放大放小的转场动画，可以根据自己的需要使用Paper中的弹性效果，有Material风格。
 * [KYNewtonCradleAnimiation](https://github.com/KittenYang/KYNewtonCradleAnimiation) - 牛顿摆动画。
 * [LayerPlayer](https://github.com/scotteg/LayerPlayer) - 一款全面展示核心动画 API 示例项目（上架应用）。包括 CALayer, CAScrollLayer, CATextLayer, AVPlayerLayer, CAGradientLayer, CAReplicatorLayer, CATiledLayer, CAShapeLayer, CAEAGLLayer, CATransformLayer, CAEmitterLayer 等使用的互动演示。
 * [JGTransitionCollectionView](https://github.com/JayGajjar/JGTransitionCollectionView) - swift，基于集合视图扩展实现完成自动布局及单元项 Flip式动画效果（效果很赞）。组件使用方便、自然（只需设置集合视图数据源的标准方式即可）。
 * [KYShareMenu](https://github.com/KittenYang/KYShareMenu) - 带弹性动画的分享菜单。
 * [Context-Menu.iOS](https://github.com/Yalantis/Context-Menu.iOS) - 可以为app的菜单添加漂亮的动画内容，可自定义icon，并可根据自己的喜好设计单元格和布局。
 * [DeformationButton](https://github.com/LuciusLu/DeformationButton) - 一个简单的变换形状动画按钮。
 * [UnReadBubbleView](https://github.com/heroims/UnReadBubbleView) - UnReadBubbleView是一个能够拖拽并拉长的气泡视图。拖拽到一定的长度会消失，可以通过系数设置来控制拖拽的长度。气泡也支持多种属性设置。 
 * [PPDragDropBadgeView](https://github.com/smallmuou/PPDragDropBadgeView) - 实现了类似于QQ 5.0 水滴拖拽效果. 支持iOS 5.0+ ARC，气泡能够带有数字标识，同时支持消失block方法。消失时还带有消失效果动画。
 * [GiftCard-Implementation](https://github.com/MartinRGB/GiftCard-Implementation) - 购买的炫酷动画。
 * [SDCycleScrollView](https://github.com/gsdios/SDCycleScrollView) - 无限循环自动图片轮播器(一步设置即可使用)。
 * [BuildAnInfiniteCarousel](https://github.com/johnlui/Swift-On-iOS/tree/master/BuildAnInfiniteCarousel) - 自己动手造无限循环图片轮播，[教程](https://autolayout.club/2015/10/29/%E8%87%AA%E5%B7%B1%E5%8A%A8%E6%89%8B%E9%80%A0%E6%97%A0%E9%99%90%E5%BE%AA%E7%8E%AF%E5%9B%BE%E7%89%87%E8%BD%AE%E6%92%AD/)。
 * [iCarousel](https://github.com/nicklockwood/iCarousel) - iCarousel是一个类，它继承于UIView。用于简化实现各种类型的旋转木马(分页滚动视图），无限轮播 ，[iOS开发之多图片无缝滚动组件封装与使用](http://www.cocoachina.com/ios/20150828/13198.html)。
 * [KIPageView](https://github.com/smartwalle/KIPageView) - 无限循环PageView，横向TableView，无限轮播。
 * [简单实用的无限循环轮播图](http://code.cocoachina.com/view/128288) - 简单实用的无限循环轮播图 。
 * [XTLoopScroll](https://github.com/Akateason/XTLoopScroll) - 用两个 timer 三个重用的 view 实现无限循环 scrollView，1自动轮播 2点击监听回调当前图片 3手动滑动后重新计算轮播的开始时间, 良好的用户体验。
 * [HotGirls](https://github.com/zangqilong198812/HotGirls) - 卡片动画。
 * [tispr-card-stack](https://github.com/tispr/tispr-card-stack) - swift 卡片风格动画切换组件及完整交互示例。
 * [ZLSwipeableViewSwift](https://github.com/zhxnlai/ZLSwipeableViewSwift) - swift 卡片堆叠效果的实现（ZLSwipeableView)】可实现类似Tinder和Potluck应用程序的卡片堆叠效果，该项目基于[ZLSwipeableView objective-c](https://github.com/zhxnlai/ZLSwipeableView/)实现。1.自定义动画。2.自定义滑动切换。3.自定义方向。4.撤销。
 * [Koloda](https://github.com/Yalantis/Koloda) - 基于卡片的 Tinder-style 动画效果示例。精细绝人。更赞的是额外附了详细开发教程 How We Built Tinder-Like Koloda Animation in Swift [网页链接](https://yalantis.com/blog/how-we-built-tinder-like-koloda-in-swift/) 。Yalantis 出品动画程序款款精品。
 * [QQPersonalInfoTransition](https://github.com/zangqilong198812/QQPersonalInfoTransition) - 仿照QQ的转场。
 * [KYAnimatedPageControl](https://github.com/KittenYang/KYAnimatedPageControl) - 除了滚动视图时PageControl会以动画的形式一起移动，点击目标页还可快速定位。支持两种样式：粘性小球和旋转方块。
 * [KDIntroView](https://github.com/likedan/KDIntroView) - swift 动态介绍视图框架及演示。另外两个相似的类库是 RazzleDazzle和 Presentation，择需使用。 
 * [RazzleDazzle](https://github.com/IFTTT/RazzleDazzle) - 【IFTTT开源Swift编写的帧动画框架--RazzleDazzle】RazzleDazzle 是IFTTT开源的一个iOS帧动画框架，非常适用于APP初次使用时的介绍和引导信息。JazzHands是UIKit一个简单的关键帧基础动画框架，可通过手势、scrollview、KVO等控制动画，被IFTTT应用在IFTTT for iPhone上。
 * [Presentation](https://github.com/hyperoslo/Presentation) - 一个类似RazzleDazzle的框架。
 * [FillableLoaders](https://github.com/poolqf/FillableLoaders) - 基于 CGPaths 可定制个性化填空式装载类库。附水波上涨式示例。
 * [SXWaveAnimate](https://github.com/dsxNiubility/SXWaveAnimate) - 实现非常美观的灌水动画。
 * [LSPaomaView](https://github.com/liusen001/LSPaomaView) - 可循环滚动的较长文字，跑马灯，效果很好，一句话集成。
 * [SIFloatingCollection_Swift](https://github.com/ProudOfZiggy/SIFloatingCollection_Swift) - 可定制的 Apple Music 风格浮动形状动画组件及演示。
 * [Cheetah](https://github.com/suguru/Cheetah) - 易用、高可读链式动画类库。另一个类似类库是 [DKChainableAnimationKit](https://github.com/Draveness/DKChainableAnimationKit)。
 * [CKWaveCollectionViewTransition](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - swift， UICollectionViewController之间切换的动画。
 * [TKSubmitTransition](https://github.com/entotsu/TKSubmitTransition) - 基于 UIButton 的登录加载、返回按钮转场动画组件及示例。
 * [ARAnimation](https://github.com/AugustRush/ARAnimation) - ARAnimation 对 Core Animation 进行了封装, 帮助 iOS 开发者能更加便捷的在项目中使用动画。
 * [CardsAnimationDemo]https://github.com/adow/CardsAnimationDemo) - swift， [《使用 UICollectionView 实现的一个卡片动画》](http://swiftcn.io/topics/64?f=w)不是直接操作所有 UIView 和 CALayer 的 transform3D 属性来实现整个效果的，而是使用 UICollectionView 来完成所有的视图管理和实现。。
 * [TKRubberIndicator.swift](https://github.com/TBXark/TKRubberIndicator) - 一个很不错的 page control。
 * [渐变特效文字](http://code.cocoachina.com/view/127174) - 做了一个仿iPhone的移动滑块来解锁的渐变特效文字,还有一个类似ktv歌词显示的文字特效。
 * [TTGEmojiRate.swift](https://github.com/zekunyan/TTGEmojiRate) - TTGEmojiRate.swift以Emoji表情为基础绘图，[Swift开源项目: TTGEmojiRate的实现](http://tutuge.me/2015/10/25/ttgemojirate-lib/)。
 * [HYAwesomeTransition](https://github.com/nathanwhy/HYAwesomeTransition) - 模仿格瓦拉的转场效果。
 * [CardAnimation.swift](https://github.com/seedante/CardAnimation) - CardAnimation 是国人开发的一个用 Swift 实现卡片垂直翻转动画的 Demo, [实现思路](http://www.jianshu.com/p/286222d4edf8)。
 * [TaskSwitcherDemon](https://github.com/Glow-Inc/TaskSwitcherDemon) -  是仿造iOS9的Task Switcher做出来的动画效果, 具体的实现思路可参照[这篇文章](http://tech.glowing.com/cn/implement-ios9-task-switcher-animation/)。
 * [CoreAnimationCode.swift](https://github.com/lzwjava/CoreAnimationCode) - 提供了 "iOS Core Animation Advanced Techniques" 书籍中的代码实例, 方便开发者们进行参考学习。
 * [UIViewXXYBoom.swift](https://github.com/xxycode/UIViewXXYBoom) - 一个炫酷好玩的爆炸效果，[如何实现这个效果](http://xxycode.com/ru-he-zhi-zuo-ge-xuan-ku-hao-wan-de-bao-zha-xiao-guo-2/)。
 * [ZLSwipeableViewSwift](https://github.com/zhxnlai/ZLSwipeableViewSwift) - [ZLSwipeableView](https://github.com/zhxnlai/ZLSwipeableView) - ZLSwipeableViewSwift在Tinder and Potluck中的动画效果实现思路（连续卡片翻页效果），最贴心的是作者提供了OC和Swift两个版本来供开发者使用，非常丝滑顺畅的效果。

========
#### 网络相关
##### 网络连接
* [AFNetworking](https://github.com/AFNetworking/AFNetworking) - ASI不升级以后，最多人用的网络连接开源库，[iOS网络编程之AFNetworking使用](http://www.superqq.com/blog/2014/11/07/ioswang-luo-bian-cheng-zhi-afnetworkingshi-yong/),[iOS开发下载文件速度计算](http://www.superqq.com/blog/2015/01/29/ioskai-fa-xia-zai-wen-jian-su-du-ji-suan/) , [AFNetworking 3.0迁移指南](http://www.cocoachina.com/ios/20151022/13831.html) , [AFNetworking2.0源码解析<一>](http://www.cocoachina.com/ios/20140829/9480.html) 、[AFNetworking2.0源码解析<二>](http://www.cocoachina.com/ios/20140904/9523.html)、[AFNetworking源码解析<三>](http://www.cocoachina.com/ios/20140916/9632.html)、[AFNetworking源码解析<四>](http://www.cocoachina.com/ios/20141120/10265.html)。
* [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。
* [YTKNetwork](https://github.com/yuantiku/YTKNetwork) - 是基于 AFNetworking 封装的 iOS网络库，提供了更高层次的网络访问抽象。相比AFNetworking，YTKNetwork提供了以下更高级的功能：按时间或版本号缓存网络请求内容、检查返回 JSON 内容的合法性、文件的断点续传、批量的网络请求发送、filter和插件机制等。
* [LxFTPRequest](https://github.com/DeveloperLx/LxFTPRequest) - 支持获取FTP服务器资源列表，下载/上传文件，创建/销毁ftp服务器文件/目录，以及下载断点续传，下载/上传进度，自动判断地址格式合法性跟踪等功能！国人开发，QQ：349124555。
* [HSDownloadManager](https://github.com/HHuiHao/HSDownloadManager) - HSDownloadManager，下载音乐、视频、图片各种资源，支持多任务、断点下载。
* [MutableUploadDemo](https://github.com/HHuiHao/MutableUploadDemo) - 模拟需求：图文混编，要求用户选择图片后就上传，可选择多图，并行上传，用户确定提交后后台执行，必须全部图片上传完才能提交文字。
* [WTRequestCenter](https://github.com/swtlovewtt/WTRequestCenter) - 方便缓存的请求库，提供了方便的HTTP请求方法，传入请求url和参数，返回成功和失败的回调。 UIKit扩展提供了许多不错的方法，快速缓存图片，图片查看，缩放功能， 颜色创建，设备UUID，网页缓存，数据缓存等功能。 无需任何import和配置，目前实现了基础需求。
* [MMWormhole](https://github.com/mutualmobile/MMWormhole) - Message passing between iOS apps and extensions 2个iOS设备之间通信。 
* [socket.io-client-swift](https://github.com/socketio/socket.io-client-swift) - WebSockect 客户端类库。开放的通讯协议，有利于构建强大地跨平台应用。 
* [Transporter](https://github.com/nghialv/Transporter) - swift， 短小、精悍、易用的多文件（并发或顺序）上传和下载传输库。还支持后台运行、传输进程跟踪、暂停/续传/取消/重试控制等功能。 
* [STNetTaskQueue](https://github.com/kevin0571/STNetTaskQueue) - STNetTaskQueue Objective-C 可扩展网络请求管理库。
* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - 在iOS开发中使用socket，一般都是用第三方库AsyncSocket，不得不承认这个库确实很强大，[使用教程](http://www.superqq.com/blog/2015/04/03/ioskai-fa-zhi-asyncsocketshi-yong-jiao-cheng/)。
* [AsyncSocket](https://github.com/roustem/AsyncSocket) - AsyncSocket。
* [Socket通信](http://code.cocoachina.com/view/128711) - 通过AsyncSocket封装的Socket通讯方法，简单实用，通俗易懂，初学者不能错过 。
* [GCDAsyncSocket](https://github.com/eugenehp/GCDAsyncSocket) - GCDAsyncSocket ， [不错的Demo](https://github.com/smalltask/TestTcpConnection)。
* [Just](https://github.com/JustHTTP/Just) - 小而美的 HTTP 类。功能简单、直接、完整且健壮性高-- swift。
* [Future](https://github.com/nghialv/Future) - 基于微框架设计思想的异步执行及结果响应类，代码即简单又干净-- swift。
* [MZDownloadManager](https://github.com/mzeeshanid/MZDownloadManager) - 下载管理。 
* [DVR](https://github.com/venmo/DVR) - 针对网络请求的测试框架，超实用的工具。且支持 iOS, OSX, watchOS 全平台。
* [HFDownLoad](https://github.com/hongfenglt/HFDownLoad) - iOS开发网络篇之文件下载、大文件下载、断点下载:NSData方式、NSURLConnection方式、NSURLSession下载方式 [下载方式具体的思路、区别见Blog](http://blog.csdn.net/hongfengkt/article/details/48290561) 。
* [Pitaya.swift](https://github.com/johnlui/Pitaya) - Pitaya 是纯 Swift 写的 iOS 网络库，支持 Basic Authorization、SSL 钢钉、HTTP raw body / JSON body、快速文件上传等特性，并通过内置 JSONNeverDie 实现了对 JSON 的完全支持，开箱即用。 [中文文档](https://github.com/johnlui/Pitaya/wiki/%E4%B8%AD%E6%96%87%E6%96%87%E6%A1%A3)

##### 图像获取
* [SDWebImage](https://github.com/rs/SDWebImage) - SDWebImage 网络图片获取及缓存处理。
* [Kingfisher](https://github.com/onevcat/Kingfisher) - 纯 Swift 实现的类 SDWebImage 库，实现了异步下载和缓存图片。
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - Swift，一个图像缓存加载库。 
* [FastImageCache](https://github.com/path/FastImageCache) - FastImageCache 网络图片获取及缓存处理，[iOS图片加载速度极限优化—FastImageCache解析](http://www.imooc.com/wenda/detail/247239)。
* [EGOCache](https://github.com/enormego/EGOCache) - 十分知名的第三方缓存类库，可以缓存NSString、UIImage、NSImage以及NSData。除此，如果还可以缓存任何一个实现了<NSCoding>接口的对象。所有缓存的数据都可以自定义过期的时间，默认是1天。EGOCache 支持多线程（thread-safe），[UITableView加载多张照片导致内存上涨的问题](http://www.superqq.com/blog/2014/11/06/ioskai-fa-:uitableviewjia-zai-duo-zhang-zhao-pian-dao-zhi-nei-cun-shang-zhang-de-wen-ti/)。
 * [YYWebImage](https://github.com/ibireme/YYWebImage/) - 一个图片加载库 YYWebImage，支持 APNG、WebP、GIF 播放，支持渐进式图片加载，更高性能的缓存，更多图像处理方法，可以替代 SDWebImage 等开源库，[相关文章](http://blog.ibireme.com/2015/11/02/mobile_image_benchmark/)。

##### 网络聊天
* [XMPPFramework](https://github.com/robbiehanson/XMPPFramework) - XMPPFramework openfire聊天。
* [SXTheQQ](https://github.com/dsxNiubility/SXTheQQ) - 用xmppFramework框架编写QQ程序，主要为了练习通讯的一些原理，界面比较渣 必须要先在本地配置好环境才可以运行。
* [环信](http://www.easemob.com/) - 给开发者更稳定IM云功能。8200万用户考验，好用！（暂无及时语音、视频通话）
* [融云](http://www.rongcloud.cn/) - 即时通讯云服务提供商。（暂无及时语音、视频通话）
* [容联云通讯](http://www.yuntongxun.com) - 提供基于互联网通话,视频会议,呼叫中心/IVR,IM等通讯服务。
* [chatsecure](https://github.com/ChatSecure/ChatSecure-iOS) - 基于XMPP的iphone、android加密式聊天软件， [chatsecure官网](https://chatsecure.org/) 。 [iOS代码1](https://github.com/chrisballinger/Off-the-Record-iOS)，[iOS代码2](https://github.com/chrisballinger/ChatSecure-iOS)， [iOS中文版](http://www.cocoachina.com/bbs/read.php?tid=153156)。
* [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit) - 仿微信聊天，参考JSQMessagesViewController。（国人写）
* [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) - 聊天 。 
* [SunFlower](https://github.com/HanYaZhou1990/-SunFlower) - 环信聊天demo，比较多功能 。
* [BlueTalk蓝牙聊天](http://code4app.com/ios/BlueTalk%E8%93%9D%E7%89%99%E8%81%8A%E5%A4%A9-%E6%89%8B%E6%9C%BA%E4%B9%8B%E9%97%B4/552b8190933bf0291e8b4748) - 以MultipeerConnectivity为基础， 实现了简单的蓝牙聊天。


##### 网络测试
 * [Reachability](https://github.com/tonymillion/Reachability) - 苹果提供过一个Reachability类，用于检测网络状态。但是该类由于年代久远，并不支持ARC。该项目旨在提供一个苹果的Reachability类的替代品，支持ARC和block的使用方式。[iOS网络监测如何区分2、3、4G](http://www.jianshu.com/p/efcfa3c87306)   
 * [Reachability.swift](https://github.com/ashleymills/Reachability.swift) - 用于替换苹果的 Reachability 类，可以方便地检测当前是否联网以及具体的联网状态。 
 * [SimpleCarrie](https://github.com/crazypoo/SimpleCarrie) - 简单的运营商信息获取!。
 * [NetReachability](https://github.com/crazypoo/SimpleCarrie) - swift2.0 简单的方法检查网络连接的连通性，提供通知中心集成接口。 
 * [NetworkEye](https://github.com/coderyi/NetworkEye) - 一个网络调试库，可以监控App内HTTP请求并显示请求相关的详细信息，方便App开发的网络调试。 
 * [SimpleBS.swift](https://github.com/bin1991/SimpleBS) - 网络测试小工具。

##### WebView
* [MGTemplateEngine](https://github.com/mattgemmell/MGTemplateEngine) - MGTemplateEngine比较象 PHP 中的 Smarty、FreeMarker 和 Django的模版引擎，是一个轻量级的引擎，简单好用。只要设置很多不同的HMTL模版，就能轻松的实现一个View多种内容格式的显示，对于不熟悉HTML或者减轻 工作量而言，把这些工作让设计分担一下还是很好的，也比较容易实现设计想要的效果。
* [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) - 一个 UIWebView 的进度条接口库,UIWebView 本身是不提供进度条的。 
* [GTMNSString-HTML](https://github.com/siriusdely/GTMNSString-HTML) - 谷歌开源的用于过滤HTML标签。 

========
#### Model
 * [JSONKit](https://github.com/johnezang/JSONKit) - JSONKit库是非常简单易用而且效率又比较高的，重要的JSONKit适用于ios 5.0以下的版本,使用JSONKit库来解析json文件，只需要下载JSONKit.h 和JSONKit.m添加到工程中；然后加入libz.dylib即可。
 * [JSONModel](https://github.com/icanzilb/JSONModel) - 解析服务器返回的Json数据的库,[JSONModel源码解析一](http://www.jianshu.com/p/3d795ea37835)。
 * [Mantle](https://github.com/Mantle/Mantle) - Mantle主要用来将JSON数据模型化为OC对象, 大系统中使用。[为什么选择Mantle](http://www.iwangke.me/2014/10/13/Why-Changba-iOS-choose-Mantle/)。
 * [RFJModel](https://github.com/refusebt/RFJModel) - RFJModel是一个IOS类库，可以将JSON字典自动装填到OBJC对象。相比JSONModel有一些非常好的特性，使用上也比较简单。
 * [XMLDictionary](https://github.com/nicklockwood/XMLDictionary) - ios与mac os平台下xml与NSDictionary相互转化开源类库。
 * [MJExtension](https://github.com/CoderMJLee/MJExtension) - 用于json转model进行使用，转换效率很高，使用也比较简单，只要前后台约定好，json直接就转成了model。
 * [CFRuntime](https://github.com/CoderMJLee/MJExtension) - “Swift 版的 MJExtension，运行时、反射与一键字典模型互转”。 
 * [DDModel](https://github.com/openboy2012/DDModel) - 快速搭建项目Model层，支持ORM映射关系，能从JSON/XML直接实例一个Model对象。支持SQLite本地数据持久化，封装了HTTP， 减少HTTP代码与UIViewController的代码耦合，支持Cache；类似RESTKit、Mantle的功能；使用该类库以后简化了网络层的开发工作，把更多的精力放在UI上面；目前只支持GET/POST方法的请求。使用到的第三方库有：1.SQLitePersistentObject; 2.JTObjectMapping; 3.AFNetworking; 4.XMLDictionary;
 * [protobuf-swift](https://github.com/alexeyxo/protobuf-swift) - Protocol Buffers 的 Swift 语言实现库。P.S. Protocol Buffers 是 Google 开源项目，主要功能是实现直接序列化结构化的对象数据，方便跨平台快速传递，开发者也可以直接修改 protobuf 中的数据。相比 XML 和 JSON，protobuf 解析更快，存储更小。
 * [JSONCodable](https://github.com/matthewcheok/JSONCodable) - 基于 Swift 2.0 新特性（Protocol Extensions and Error Handling）的JSON 解析类。
 * [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - 使Swift的JSON解析变得简单。
 * [JSONNeverDie.swift](https://github.com/johnlui/JSONNeverDie) - JSON 到 Model 类的自动映射工具。
 * [Fuzi.swift](https://github.com/cezheng/Fuzi) - Swift实现的轻量快速的 XML/HTML 解析器。
 * [SWXMLHash.swift](https://github.com/drmohundro/SWXMLHash) - 易用的 XML 解析类库。非常实用的“轮子”。
 * [YYModel](https://github.com/ibireme/YYModel) - 高性能的 iOS JSON 模型框架。

========
#### 通讯录
* [快速查找联系人](http://code.cocoachina.com/view/128245) - 类似微信联系人搜索的界面,快速查找联系人,并支持点击查询结果 。


========
#### 其他
 * [DateTimeKit](https://github.com/exsortis/DateTimeKit) - 一个超赞的时间处理的库，Joda-Time ！ 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题。
 * [SwiftDate](https://github.com/malcommac/SwiftDate) - 特别完整、强大的日期时间操作管理类库。它几乎涵盖了已知开源日期类库所有优秀特性。 他能帮你轻松处理时区，处理时间加减，计算到期时间等等场景下的问题。
 * [iOS私有API](https://github.com/nst/iOS-Runtime-Headers) - 私有API，绿色 == public，红色 == private，蓝色 == dylib。
 * [iOS源代码](http://opensource.apple.com/source/CF/) - iOS源代码。
 * [libfacedetection](https://github.com/ShiqiYu/libfacedetection) - C++ 人脸识别 包含正面和多视角人脸检测两个算法.优点:速度快(OpenCV haar+adaboost的2-3倍), 准确度高 (FDDB非公开类评测排名第二），能估计人脸角度。 
 * [Slidden](https://github.com/Brimizer/Slidden) - 一个老外开源的开发自定义键盘的库，利用这个开源库，可以方便的配置键位、颜色以及键位对应的图片。
 * [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) - 用户键盘弹出自动计算高度，进行屏幕滚动操作。
 * [CDPMonitorKeyboard](http://d.cocoachina.com/code/detail/298267) - CDPMonitorKeyboard封装,可以解决输入视图(例如textField,textView等)被键盘覆盖问题，并可设置高于键盘多少。 
 * [自动监听键盘高度](http://code.cocoachina.com/detail/297973/%E8%87%AA%E5%8A%A8%E7%9B%91%E5%90%AC%E9%94%AE%E7%9B%98%E9%AB%98%E5%BA%A6/) - 自动监听键盘高度，初始界面，输入框在屏幕最下方，当键盘出现时，输入框随即移动到键盘上方。 
 * [KeyboardToolBar](https://github.com/Jiar/KeyboardToolBar/) - 从此不再担心键盘遮住输入框，[文档](http://www.jianshu.com/p/48993ff982c1)。
 * [SYKeyboardTextField](https://github.com/441088327/SYKeyboardTextField) - SYKeyboardTextField 是一个轻巧,简单,非侵入式的键盘附随输入框! 采用Swift编写。
 * [BlocksKit](https://github.com/zwaldowski/BlocksKit) - block框架，为 OC 常用类提供了强大的 Block 语法支持，使得编写 OC 代码变得舒适、快速、优雅。
 * [KVOController](https://github.com/facebook/KVOController) - 在项目中有使用 KVO ，那么 KVOController 绝对是个好选择。它是 facebook 开源的一个 KVO 增强框架。 
 * [appirater](https://github.com/arashpayan/appirater) - 用于提醒用户给你的 APP 打分的工具。
 * [MotionKitr](https://github.com/MHaroonBaig/MotionKitr) - 为核心运动框架（The Core Motion framework）提供友好的类库封装，以更方便使用三轴陀螺仪和加速感应器特性。
 * [Review Monitor](https://launchkit.io/reviews/) -  第一时间自动推送 Apple Store 的用户评论到你的邮件箱或者 Slack，第一时间跟进用户反馈，打造优秀 App 必备工具！类似的有：App annie 的类似功能。
 * [WBWebViewConsole](https://github.com/Naituw/WBWebViewConsole) - 类似微博iPhone客户端的 “调试选项” 吗？把其中的 “内置浏览器网页调试” 开源在 Github 上了。
 * [ios-good-practices](https://github.com/futurice/ios-good-practices) - ios-good-practices iOS 开发最佳实践。
 * [iOS开发最佳实践](http://ios.jobbole.com/81830/) - iOS 开发最佳实践 -- 中文。
 * [TodayExtensionSharingDefaults](http://code.cocoachina.com/detail/232160) - TodayExtensionSharingDefaults是一个iOS 8 Today扩展示例，可以使用NSUserDefaults与其containing app分享数据。
 * [QRCodeReader.swift](https://github.com/yannickl/QRCodeReader.swift) - QRCodeReader.swift一款简单的 QR 二维码阅读组件及示例，提供前后相机切换功能。
 * [swiftScan](https://github.com/MxABC/swiftScan) - 具有丰富功能的二维码扫描组件及类库。[对应OC版本LBXScan](https://github.com/MxABC/LBXScan)。
 * [QR-Code-Generator.swift](https://github.com/appcoda/QR-Code-Generator) - 生成二维码。
 * [QRCatcher](https://github.com/100mango/QRCatcher) - 一个简洁美观的二维码扫描应用， [iOS学习：AVFoundation 视频流处理--二维码扫描](https://github.com/100mango/zen/blob/master/iOS%E5%AD%A6%E4%B9%A0%EF%BC%9AAVFoundation%20%E8%A7%86%E9%A2%91%E6%B5%81%E5%A4%84%E7%90%86/iOS%E5%AD%A6%E4%B9%A0%EF%BC%9AAVFoundation%20%E8%A7%86%E9%A2%91%E6%B5%81%E5%A4%84%E7%90%86%20.md)。
 * [MQRCodeReaderViewController](https://github.com/zhengjinghua/MQRCodeReaderViewController) - 二维码扫描控件, UI 做了优化, 仿造微信, 直接拖进项目就可使用。
 * [Parsimmon](https://github.com/ayanonagon/Parsimmon) - swift，小而美的语言学类库封装工具包。提供分词、标记词性、词形归并、朴素贝页斯分类、决策树等自然语言分析小工具。P.S. 英语分词效果好于中文，感兴趣的同学可以针对中文做一些优化开发。参考译文 NSHipster - [NSLinguistic​Tagger](http://nshipster.cn/nslinguistictagger/)。
 * [Password-keyboard](https://github.com/liuchunlao/Password-keyboard) - 随机变换数字位置的密码键盘。 模仿银行类应用在付款时输入的随机密码键盘。
 * [MKMapView-Extension](https://github.com/SemperIdem/MKMapView-Extension) - 这是关于 MKMapView 写的一个基于swift的扩展，可以扩展 MKMapView 的相关功能，减少复用代码量。
 * [SemverKit](https://github.com/nomothetis/SemverKit) - 针对符合『语义化版本规范 2.0.0』版本号的解析、比较运算类库。不仅支持 Major, Minor, Patch，还支持 Alpha 和 Beta 预发布版本，以及相应地递增运算扩展。
 * [SwiftValidator](https://github.com/jpotts18/SwiftValidator) - 基于规则的输入验证类库。项目良好的面向对象设计思想，使规则的扩展及自定义非常方便。更专业的规则引擎（甚至是基于自然语言的规则配置）解决方案，比如：开源的 Drools，商用的 ILOG 等。
 * [Tesseract-OCR-iOS](https://github.com/gali8/Tesseract-OCR-iOS) - 有关OCR文字识别项目。
 * [Screenotate](https://github.com/osnr/Screenotate) - 支持 OCR 文字识别的载屏笔记 Mac 完整应用。
 * [cocoacats](http://cocoacats.com/) - 【分类汇总】里面收集了 iOS 中常用的分类文件，一直在更新。。
 * [Olla4iOS](https://github.com/nonstriater/Olla4iOS) - 过去积累的一些方便复用的类和方法，还在整理中。
 * [DKNightVersion](https://github.com/Draveness/DKNightVersion) - 用最快的方式给你的应用加上夜间和白天的切换效果。 
 * [TouchVisualizer](https://github.com/morizotter/TouchVisualizer) - 实用的多点触摸可视化组件。扩展并作用于 UIWindows，结构上提供了简单地针对触摸显示定制，比如触摸点的颜色。
 * [RegexKitLite](https://github.com/wezm/RegexKitLite) - 用来处理正则表达式。 
 * [Regex.swift](https://github.com/sharplet/Regex) - 实用的正则表达式微框架类库。
 * [PySwiftyRegex.swift](https://github.com/cezheng/PySwiftyRegex) - 像Python一样简洁高效地作正则处理。
 * [PhoneNumberKit.swift](https://github.com/marmelroy/PhoneNumberKit) -  解析、格式化及验证国际电话号码工具库（相当于 Google 的 libphonenumber 库的 Swift 版本）。
 * [XcodeServerSDK](https://github.com/czechboy0/XcodeServerSDK) - 非官方 Xcode Server SDK 封装库。 P.S. 该 SDK 分离自之前推荐的由该作者开发的自动测试框架 [Buildasaur](https://github.com/czechboy0/Buildasaur)。
 * [BFKit-Swift](https://github.com/FabrizioBrancati/BFKit-Swift) - BFKit-Swift 这套工具库可以提高应用开发效率。 
 * [CKSIncrementalStore](https://github.com/CloudKitSpace/CKSIncrementalStore) - 基于 CloudKit 服务器实现多终端数据同步。
 * [SwiftSequence](https://github.com/oisdk/SwiftSequence) - 简洁、灵活、多变的操作 SequenceType 的类库（基于微框架（μframework）设计思想）。
 * [IDNFeedParser](https://github.com/photondragon/IDNFeedParser) - 一个简单易用的Rss解析库。
 * [CoreUmeng](https://github.com/nsdictionary/CoreUmeng) - 简单：友盟分享封装。
 * [openshare](https://github.com/100apps/openshare) - 不用官方SDK，利用社交软件移动客户端(微信/QQ/微博/人人/支付宝)分享/登录/支付。
 * [Swifternalization](https://github.com/tomkowz/Swifternalization) - 一套实用的本地化工具库。使用教程及 API 文档完整。值得收入项目的“轮子”。
 * [apous](https://github.com/owensd/apous) - 一款有趣的 Swift 应用 － 让 Swift 成为脚本语言。
 * [Mirror](https://github.com/kostiakoval/Mirror) - 通过反射（Refection）实现镜像对象封装库。从而可以更轻松获取（或输出）对象属性名、类型及值变量。
 * [Proposer](https://github.com/nixzhu/Proposer) - Proposer 用单个 API 处理 iOS 上的权限请求，以便使用前确认可访问“相册”、“相机”、“麦克风”、“通讯录”或“用户位置”。 
 * [PermissionScope](https://github.com/nickoneill/PermissionScope) - 用这个库可以在询问用户前，就告知用户所需的系统权限，为用户带来更好的体验。接受度更高—>更多活跃用户->更高的留存率->数据更好->下载率更高。 
 * [LocationManager](https://github.com/intuit/LocationManager) - CoreLocation使用起来还是比较麻烦的，需要授权，判断系统版本等等，所以推荐使用第三方框架LocationManager，使用Block，十分简单！[iOS-CoreLocation：无论你在哪里，我都要找到你！](http://www.cocoachina.com/ios/20150721/12611.html) 。
 * [pangu.objective-c](https://github.com/Cee/pangu.objective-c) - 有多种语言实现版本～ Pangu.Objective-C：格式化中英文之间的空格（OC）。
 * [objection](https://github.com/atomicobject/objection) - 一个轻量级的依赖注入框架Objection。
 * [ControlOrientation](https://github.com/johnlui/Swift-On-iOS/tree/master/ControlOrientation/ControlOrientation) - 如何用代码控制以不同屏幕方向打开新页面【iOS】， [使用说明](http://lvwenhan.com/ios/458.html)。
 * [iRate](https://github.com/nicklockwood/iRate) - 问卷调查。
 * [GameCenterManager](https://github.com/nihalahmed/GameCenterManager) - 在iOS上管理GameCenter vanilla并不算难，但是有了这个库会更简单也更快。好上加好不是更好么。
 * [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) - 用作极佳、定制的文本输入控制时，自适应文本区域，手势识别、自动填充、多媒体合并，快速drop-in解决方案。
 * [IAPHelper](https://github.com/saturngod/IAPHelper) - 应用内付费给我们提供了很多样本代码，而这个库丢掉了那些代码，将金钱交易相关的大多通用任务做了简单的封装。
 * [TAPromotee](https://github.com/JanC/TAPromotee) - 交叉推广应用是你可以免费实现的最佳市场推广策略之一。使用这个库做起来非常简单，不用都不可能——将TAPromotee加入你的podfile中，免费配置与享受更多下载吧。
 * [DownloadFontOnline](https://github.com/cgwangding/DownloadFontOnline) - 实现了在线下载一些字体的功能，不用在工程中导入字体库，下载的字体也不会保存在你的应用中，所以可以放心使用。修复了一下崩溃的bug。
 * [STClock](https://github.com/zhenlintie/STClock) - 仿锤子时钟。
 * [GitUp](https://github.com/git-up/GitUp) - GitUp是一个可视化的Git客户端，能够实时的进行编辑、合并、回滚等多种操作，更多功能，请下载体验。
 * [获取联系人信息，通讯录](http://code.cocoachina.com/detail/320392/) - 获取联系人信息，通讯录。
 * [Universal-Jump-ViewController](https://github.com/HHuiHao/Universal-Jump-ViewController) - 根据规则跳转到指定的界面(runtime实用篇一)。
 * [Device-swift](https://github.com/Ekhoo/Device) - 可以非常方便的获取设备型号和屏幕尺寸，实现起来难度不大，大家可以学习一下源码。
 * [RunKit.swift](https://github.com/khoiln/RunKit) - 针对 GCD 框架的一个友好访问封装库（支持方法链式调用）。
 * [Plum-O-Meter](https://github.com/FlexMonkey/Plum-O-Meter) - swift 称重应用， (3D Touch之我见)[http://swift.gg/2015/10/23/3d-touch-impressions-and-thoughts/]。
 * [打开自带地图、百度地图、腾讯地图](http://code.cocoachina.com/view/128249) - 打开自带地图、百度地图、腾讯地图。
 * [batteryLevelTest](https://github.com/colin1994/batteryLevelTest) - runtime精准获取电池电量，[文档](http://www.jianshu.com/p/11c1afdf5415)。
 * [openshare](https://github.com/100apps/openshare) - 不用官方SDK，利用社交软件移动客户端(微信/QQ/微博/人人/支付宝)分享/登录/支付。。
 * [DateTools](https://github.com/MatthewYork/DateTools) - 用于提高Objective-C中日期和时间相关操作的效率。灵感来源于 DateTime和Time Period Library。
 * [DDSlackFeedback](https://github.com/deepdevelop/DDSlackFeedback) - 用这个接口实现的摇一摇上传文字或者截屏反馈到你的 Slack channel，特别适合测试 app 的时候用，集成也很简单。
 * [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 是一个非常容易使用的蓝牙库, 适用于 iOS 和 Mac OS, 基于原生 CoreBluetooth 框架封装, 可以帮开发者们更简单地使用 CoreBluetooth API, 使用链式方法体, 使得代码更简洁、优雅。
 * [BluetoothKit.swift](https://github.com/rasmusth/BluetoothKit) - 基于 CoreBluetooth API 实现iOS/OS X 设备间蓝牙通讯封装类库。功能强大、传输稳定，示例完整，很酷。
 * [CoreDataStack.swift](https://github.com/bignerdranch/CoreDataStack) - 存储栈。
 * [SYNQueue.swift](https://github.com/THREDOpenSource/SYNQueue) - 执行队列类库。
 * [DDMathParser.swift](https://github.com/davedelong/DDMathParser) - 相比 NSExpression 和 GCMathPaser，功能更强大的数学表达式解析器。
 * [RateLimit.swift](https://github.com/soffes/RateLimit) - 简单、实用定时执行任务工具类库。
 * [iOS-Categories](https://github.com/shaojiankui/IOS-Categories) - 收集了许多有助于开发的iOS扩展,各种category分类。
 * [YYCategories](https://github.com/ibireme/YYCategories) - 功能丰富的 Category 类型工具库。
 * [YYAsyncLayers](https://github.com/ibireme/YYAsyncLayers) -  iOS 异步绘制与显示的工具。
 * [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) -  iOS 全局并发队列管理工具。
 * [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) -   iOS 键盘监听管理工具。
 * [shoppingCart.swift](https://github.com/6ag/shoppingCart) - swift的购物车demo，采用纯代码UI，autolayout自动布局，core animation动画效果。
 * [ShoppingCartExample](https://github.com/gbaldera/ShoppingCartExample) - 购物车最多star demo。
 * [shoppingCart1](https://github.com/yhangeline/shoppingCart) - 仿美团购物车效果。
 * [ZFShoppingCart](https://github.com/WZF-Fei/ZFShoppingCart) - 仿照美团外卖加入购物车的动态效果。
 * [shoppingCart2](https://github.com/spxvszero/ShoppingCart) - 一个购物车demo，包含购物车动画效果、购物车多选、删除、编辑等功能。
 * [s
