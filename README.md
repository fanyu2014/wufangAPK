# wufangAPK

### 正式版链接：
教育+：
[[二维码]](https://github.com/fanyu2014/wufangAPK/blob/master/img/教育家QRCode.png)
[[下载链接]](https://a.app.qq.com/o/simple.jsp?pkgname=com.hj.education)

百纪成长：
[[二维码]](https://github.com/fanyu2014/wufangAPK/blob/master/img/百纪成长QRCode.png)
[[下载链接]](https://a.app.qq.com/o/simple.jsp?pkgname=com.wufang.mall)

<!-- 百纪成长畅玩版：
[[二维码]](https://github.com/fanyu2014/wufangAPK/blob/master/img/百纪成长畅玩版QRCode.png)
[[下载链接]](https://a.app.qq.com/o/simple.jsp?pkgname=com.wufang.mall.mail) -->

### 提测地址：
教育+：
[[ apk ]](https://www.pgyer.com/gb3Q)

百纪成长：
[[ apk ]](https://www.pgyer.com/05UL)
[[ iOS ]](https://www.pgyer.com/gsvh)
[[ ipa ]](https://www.pgyer.com/manager/dashboard/app/1fcd94b39ee3d61337b8e94ccec48870)
[[推送专用]](https://www.pgyer.com/4y1O)

扫码枪：
[[ apk ]](https://github.com/fanyu2014/wufangAPK/blob/master/md/scan_gun_download_address.md)

### 提测日志：
3月27日教育加_2.8.10(apk)：正式环境：解决的问题如下：

    [x]edu2.8.11：私信右上角改成popupWindow
    [x]edu2.8.11：升级微信开放平台sdk到最新版本
    [x]edu2.8.11：跑通APP唤起小程序
    [x]edu2.8.11：bug：班级圈头像判空、加try…catch
    [x]edu2.8.11：失物招领列表item样式调整
    [x]edu2.8.11：合并edu2810分支
    [x]edu2.8.11：地址查看与地址新增去除邮政编码项
    [x]edu2.8.11：app关联艾道小程序
    [x]edu2.8.11：视频列表的布局、样式更改
    [x]edu2.8.11：关联艾道小程序家长端
    [x]edu2.8.11：首页小程序接口调试（电子班牌）
    [x]edu2.8.11：通讯录头部字母变低
    [x]edu2.8.11：请假时审批人达到4人时，隐藏+号
    [x]edu2.8.11：bug：请假时会出现已删除的审批人无法再选的问题（已解决）
    [x]edu2.8.11：请假界面的UI调整
    [x]edu2.8.11：调通现有银联支付
    [x]edu2.8.11：艾道小程序参数对接
    [x]edu2.8.11：银联升级（从3.1.1升到3.4.6）
    [x]edu2.8.11：请假确认与请假状态显示（学生123456789000、班主任15974271145）

2月14日教育加_2.8.10(apk)：正式环境：解决的问题如下：

    [x]edu2.8.10：bug：班级圈主页显示和更多中显示不正确：发布的第一条如果是图片班级圈。第二条发布文字班级圈，第二个文字班级圈就会带有第一条发布的图片班级圈中的图片
    [x]edu2.8.10：bug：相册选取图片时图片旋转问题
    [x]edu2.8.10：bug：家庭作业图片顺序问题（先放着，后台暂未判断图片顺序）
    [x]edu2.8.10：bug：家庭作业日期选择，不会根据选择的日期显示当天的作业（先放着）
    [x]edu2.8.10：bug：通知公告点进去后，小米6 自动弹出输入法
    [x]edu2.8.10：bug：失物招领 上拉加载 更多数据会影响到其他 失物招领的图片 下拉刷新后正常

1月29日教育加_2.8.10(apk)：正式环境：解决的问题如下：

    [x]edu2.8.10：需求：一卡通挂失
    [x]edu2.8.10：HttpUtil的细节优化
    [x]edu2.8.10：闪退时从缓存中恢复用户数据（刘振早前bug）
    [x]edu2.8.10：去除接口XjzButton的调用：http://sc.jk.wufangedu.com/api/Util/XjzButton/?access_token=9e0c609fade840ea85e6d0a9db335ff1
    [x]edu2.8.10：整体换用新框架（失败，还是使用现有框架，以后可针对单独接口做特别处理）
    [x]edu2.8.10：轻量级封装okhttp
    [x]edu2.8.10：HttpUtil试用：跑通/api/Banner/接口（四川账号）
    [x]edu2.8.10：优化：发现页：下拉刷新改成统一风格
    [x]edu2.8.10：安卓四川用户登录需要点几下（四川接口随机报错）：去掉这句能避免：connection.setRequestProperty("Connection", "close");
    目前状况：四川的用户去掉了这句代码。
    [x]edu2.8.10：bug：调查海柯webView页面打开错误问题（js.creatDatabase报错）
    [x]edu2.8.10：优化：班级圈/相册：只有一张图的时候的显示优化
    [x]edu2.8.10：优化：通讯录老师页：下拉刷新改成统一风格
    [x]edu2.8.10：优化：通讯录学生页：下拉刷新改成统一风格
    [x]edu2.8.10：优化：首页-更多：icon间距调整
    [x]edu2.8.10：优化：一卡通：actionbar的pupup图
    [x]edu2.8.10：bug：聊天记录之前的信息拿不到（已解决）
    [x]edu2.8.10：优化：进入一卡通界面时响应慢的问题（弹loading框）
    [x]edu2.8.10：/api/onecardbalance/listdepositproductV2/接口商品列表为空时，做相应的处理
    [x]edu2.8.10：优化：一卡通界面fragment的切换逻辑
    [x]edu2.8.10：优化：一卡通界面fragment增加懒加载
    [x]edu2.8.10：优化：一卡通界面fragment增加切换时的渐入渐出效果
    [x]edu2.8.10：优化：一卡通界面fragment第一次加载时去除“暂无数据”文字
    [x]edu2.8.10：优化：实现碎片界面的懒加载基类：LazyFragment
    [x]edu2.8.10：跟踪：一卡通消费记录分页问题（已解决）
    [x]edu2.8.10：bug：找出问题接口：一卡通消费记录分页问题（数据总量刚好等于10）
    [x]edu2.8.10：新增：baseFragment增加checkForPermissions的protected方法
    [x]edu2.8.10：新增：baseFragment增加onRequestPermissionsResult()的公共处理方法
    [x]edu2.8.10：优化：EducationMainActivity日志管理
    [x]edu2.8.10：优化：EducationMainActivity：selectTab方法、getHoliday方法
    [x]edu2.8.10：优化：首页tabbar点击最小间隔时间从1000ms调整为700ms
    [x]edu2.8.10：新增：baseActivity增加checkForPermissions的protected方法
    [x]edu2.8.10：新增：baseActivity增加onRequestPermissionsResult()的公共处理方法
    [x]edu2.8.10：新增：AppSizeCalUtil类：用于转换app尺寸，用于界面的适配
    [x]edu2.8.10：重构：修改MyApplication类名字为App
    [x]edu2.8.10：新增：ExceptionUtil类：用于统一处理项目的Exception

10月19日教育加_2.8.8(apk)：正式环境：解决的问题如下：

    [x]edu2.8.8：学校通知页面qq分享失败（动态权限问题，已解决）
    [x]edu2.8.8：微信分享：取消回到应用时提示语不对（无法解决，友盟回调返回的东西一样）
    [x]edu2.8.8：解决多商户（湘钢一中）小米6微信不能支付的问题
    [x]edu2.8.8：湘钢一中只使用微信支付

10月16日教育加_2.8.7(apk)：正式环境：解决的问题如下：

    [x]edu2.8.7：海涛：一卡通“出入记录”与“通话记录”切换界面的时候数据出错

10月15日教育加_2.8.7(apk)：正式环境：解决的问题如下：

    [x]edu2.8.7：班级圈图片浏览界面缺少保存图片功能
    [x]edu2.8.7：调整HomeFragment的代码
    [x]edu2.8.7：更改上拉下拉刷新样式：“一卡通-出入记录”界面
    [x]edu2.8.7：更改上拉下拉刷新样式：“一卡通-通话记录”界面
    [x]edu2.8.7：更改上拉下拉刷新样式：“一卡通-消费记录”界面（已放弃更改）
    [x]edu2.8.7：“一卡通-消费记录”界面：列表不显示最后一条数据
    [x]edu2.8.7：家庭作业日期不能根据选择的日期显示（后端的问题）
    [x]edu2.8.7：更改项目debug时默认打包的key文件
    [x]edu2.8.7：湘钢一中一卡通支付异常账号调试（原因是微信appId不对）
    [x]edu2.8.7：配合微信支付业务逻辑更改（接口更改，微信动态appId注册）




10月12日百纪成长_1.6.2(apk、ipa)：正式环境

10月12日百纪成长_1.6.2(apk、iOS)：测试环境：解决的问题如下：

    [x]百纪1.6.2：秒杀活动不显示
    [x]百纪1.6.2：“关于我们”页面二维码不全：位置：http://bjcz.app.wufangedu.com:18081/WFvendition/design/book/index.html

10月8日扫码枪_1.2.0(apk)：正式环境：接口变动

10月8日扫码枪_1.2.0(apk)：测试环境：接口变动

9月30日扫码枪_1.2.0(apk)：正式环境

9月30日百纪成长_1.6.2(apk、ipa)：正式环境

9月28日百纪成长_1.6.2（apk）：测试环境：解决的问题如下：

    [x]百纪1.6.2：特价抢购订单去掉陪同人与预约时间，而是：份数 ==> 订单列表页
    [x]百纪1.6.2：特价抢购订单去掉陪同人与预约时间，而是：份数 ==> 订单详情页
    [x]百纪1.6.2：特价抢购订单去掉陪同人与预约时间，而是：份数 ==> 我的预约页
    [x]百纪1.6.2：后台接口版本改为v7

9月28日扫码枪_1.2.0(apk)：测试环境：解决的问题如下：

    [x]扫码枪1.2.0：debug模式下增加“重新登录”按钮
    [x]扫码枪1.2.0：核销平台通用错误处理代码
    [x]扫码枪1.2.0：核销平台扫码进馆
    [x]扫码枪1.2.0：核销平台验票打印
    [x]扫码枪1.2.0：已验票接口更改
    [x]扫码枪1.2.0：所有预约接口更改（合并各个来源的数据）

9月26日百纪成长_1.6.2（apk、ios）：测试环境：解决的问题如下：

    百纪1.6.2：抢购订单二维码进馆（二维码界面去除小孩信息，显示用户信息）
    百纪1.6.1：bug：推送的特价抢购，购买时出现“促销ID不能为空”
    百纪1.6.1：UI：“我的”界面更换默认头像
    百纪1.6.1：bug：百纪卡tab页本季热门数量判断
    百纪1.6.1：场馆分享
    百纪1.6.1：个推cId上传至后台
    百纪1.6.1：活动分享
    百纪1.6.1：场馆页接口重构（根据id查询详情）
    百纪1.6.1：活动页接口重构（根据id查询详情）
    百纪1.6.1：抢购页接口重构（根据id查询详情）
    百纪1.6.1：抢购分享
    百纪1.6.1：推送跳转
    百纪1.6.1：bug：本季热门数量小于3时的处理
    百纪1.6.1：首页刷新时去除“加载中”菊花

9月26日教育加_2.8.6(apk)：正式环境：解决的问题如下：

    edu2.8.6：萤石云视频播放不出来（播放器缺少CameraInfoList）
    edu2.8.6：bug：账号（138084111461）的空用户点进去闪退
    edu2.8.6：熟悉代码/小改代码：EducationWelcomePageActivity.java
    edu2.8.6：熟悉代码/小改代码：EducationStartPageActivity.java
    edu2.8.6：熟悉代码/小改代码：EducationMainActivity.java
    edu2.8.6：熟悉代码/小改代码：HomeFragment.java
    edu2.8.6：bug：清除缓存时，遍历文件夹时出现数组空指针问题
    edu2.8.6：添加BaseActivity公共动态权限申请代码
    edu2.8.6：萤石云视频播放界面闪退
    edu2.8.6：bug：首页班级圈闪退问题（空账号发班级圈）

9月19日百纪成长_1.6.1：线上环境：解决漏掉的bug：百纪卡页本季热门商品数量判断

9月14日百纪成长_1.6.1：解决bug：推送的特价抢购，购买时出现“促销ID不能为空”

9月13日百纪成长_1.6.1：分享（场馆、活动）；推送（场馆、活动、秒杀、链接）；本季热门数量小于3时bug修复。

9月6日(2)百纪成长_1.6.0：version code +1

9月6日百纪成长_1.6.0：iOS打app store签名包

9月5日百纪成长_1.6.0：去除百纪卡tab界面本季热门item标题调试内容
