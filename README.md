# YundongSports
基于Taro的体育赛事报名微信小程序


##	小程序开发的相关技术：
i.	小程序是基于`taro + taro-ui + redux + react + typescript`开发的体育赛事报名系统。
ii.	管理端采用了`react`框架 + `ant design` 编写



##	相关需求及功能分析：
- 赛事信息列表
  - 展示最新赛事（赛事名，创建日期）
  - 展示最近（一周内比赛）赛事
  - 搜索
- 赛事详情页
  - 赛事详情/介绍（赛事名称，开始时间，地点，类型，主办方）
  - 相关资讯列表（点击可打开外链页面）
  - 个人报名（填写报名表，提交支付）
  - 团队报名
    - 团队列表（团队名，团队图片，创建时间，人数限制，状态，参加人数）
    - 信息详细（赛事名，团队名称，发起人，状态，人数限制，发起时间）
    - 团队报名分享（分享专属图片：包含专属小程序码，跑团名称、赛事信息）
    - 报名（填写报名表，提交支付）
    - 发起团报（跑团需要提交基本信息：跑团名称、跑团负责人（录取微信头像、昵称）、跑团基本介绍）
- 个人中心
  - 登录（处理session_key 与 open_id, 获取用户基本信息加密生成token返回.）
  - 创建跑团（名称、logo、团长电话等）
  - 查看我的跑团
  - 我的订单
    - 订单列表
    - 点击进入订单详细（报名表，所属跑团）
- 跑团排名
  - 展示跑团排名
  - 点击进入跑团详情
## 安装运行

* #### 第一步
    * 克隆项目到本地`git clone https://github.com/Mercuriopu/YundongSports.git`
* #### 第二步
    * `cnpm i`安装依赖
* #### 第三步
    * 构建小程序运行服务 `npm run dev:weapp`
* #### 第四部
    * 在微信小程序开发工具中预览

