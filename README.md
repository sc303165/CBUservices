# 剑桥常用信息/服务汇总

## 文件内容
- [accounts.md](https://github.com/sc303165/CBUservices/blob/master/docs/accounts.md)
    - 社交媒体
        - Twitter
        - Instgram
        - Facebook
        - 官方网站
        - 微信公众号
        - 小红书
        - 微博
        - 知乎
- [living.md](https://github.com/sc303165/CBUservices/blob/master/docs/camsis.md)
    - 剑桥市内生活信息集合
        - 超市
            - Co-op
            - Sainsbury's
            - TESCO
            - M&S
        - 就医
            - College Nurse
            - GP (General Practitioner)
            - 医院
        - 餐馆
            - 中餐
            - 外餐
        - 理发
            - 华人理发店
            - 英国理发店
        - 选课快捷方式
        - 选课系统相关说明
        - 期末考试时间/地点查询
        - 历年本科生开课目录
        - 清华大学迎新系统
        - 注册标志（用于学生火车票）
        - 校内校车
        - 校内地图（静态版）
        - 清华大学调查问卷系统
        - 清华紫荆码
        - eduroam
        - cksqs 查询GPA
        - 清华大学后勤综合服务平台
            - 校内各单位（包括校医院）电话号码
            - 校医院各科室挂号
            - 校园地图（动态版）
            - 网上报修
            - 客房服务
            - 订车服务
        - 邮编、邮寄地址及邮条
        - 清华大学校园一卡通自助查询系统
        - ACM/IEEE/知网等论文下载（Shibboleth或OpenAthens）
        - 火车票报销凭证
        - DIVI 注册设备
        - 清华大学邮箱
            - 清华大学校友邮箱
        - 清华大学 Overleaf 服务
        - LibGuides at Tsinghua University
        - 清新时报
        - 各食堂进入人数
- [services.md](services.md)
    - 剑桥大学技术性服务使用指北
        - Wi-Fi
            - eduroam
            - UniOfCam
            - UniOfCam-Guest
            - 学院Wi-Fi
        - OneDrive (剑桥云盘)
        - 正版软件下载与激活
            - Windows
            - Office 365
            - MATLAB
            - 杀毒软件
- [colleges.md](colleges.md)
    - 31个学院信息汇总
        - Trinity College
        - St John's College
        - King's College
- [utils.md](utils.md)
    - 一些脚本和工具
        - 校园网认证工具汇总
        - INFO/网络学堂 APP/插件
        - 选课冲突标记
        - INFO 网络学堂 Telegram 消息推送
        - 全校洗衣机状态
            - 全校洗衣机状态 - 洗衣机查询工具（有界面）
            - 清华大学洗衣房可用性查询
            - 全校洗衣机状态 - 官方小程序
            - 全校洗衣机状态 - API接口（文字版，已废弃）
            - 全校洗衣机状态 - iOS 快捷方式（不可用）
            - 全校洗衣机状态 - Telegram Bot 二哈（不可用）
            - 洗衣监控与提醒 - 微信小程序（不可用）
        - INFO GPA 计算器
        - 清华大学GPA查询
        - Rain Classroom Helper
        - 清华大学一体化平台视频自动播放
        - 学堂在线视频自动播放
        - 学堂在线字幕下载器
        - 雨课堂课件下载器
        - 清华教学参考书爬取
            - 清华大学教参服务平台
            - 文泉学堂
        - 课程地点分享
        - 注册标志（用于火车票）
        - 寝室电费查询
        - 寝室水电费查询
        - 清华上下课铃声
        - 随机选择校内餐厅 - 微信小程序
        - 随机选择校内餐厅 - Telegram Bot
        - 清华大学计算机系课程攻略
        - 清华软院课程攻略
        - 华清大学课程攻略共享计划
        - 校园评教平台
        - 有关计算机系的事实
        - NFSee 校园卡
        - 课程信息共享计划
        - 清华大学计算机专业912考研资料
        - 清华成绩刮刮乐
        - thuhole memories
        - thuhole database backup
        - 计算机系学生科协技能引导文档
        - 清华大学研究生社会实践系统爬虫
- [websites.md](websites.md)
    - 常用校外网站
        - thu.services
        - T大树洞
        - 闭社 - 清华站
        - 在线退学
        - 未名 BBS
        - 水木 BBS
        - 沙雕园的博客
        - PT 站
        - 星期四 Thursday

## 知道某个重要信息，但repo中未列出？

欢迎贡献！请 [PR](https://github.com/sc303165/cbuservices/pulls)！

需要注意的是[本 repo](https://github.com/ZenithalHourlyRate/thuservices) 中使用了 [pre-commit hook](https://github.com/ZenithalHourlyRate/thuservices/blob/master/pre-commit)，请[安装](https://git-scm.com/book/zh/v2/%E8%87%AA%E5%AE%9A%E4%B9%89-Git-Git-%E9%92%A9%E5%AD%90)，并在有 bash 与 python3 的环境中进行 commit。

在 pre-commit hook 的作用下，README.md 是自动生成的，故如果需要在 README.md 中修改，请在 [aux 文件夹](https://github.com/ZenithalHourlyRate/thuservices/tree/master/aux)下进行。

由于 Windows 文件系统的限制，文件夹名不能为 aux，请在非Windows环境（WSL也可以）下克隆该项目。

### 编译

```
python3 -m pip install --user -r requirements.txt # 安装 Python 依赖包
mkdocs serve # 直接在本地 serve，或者：
mkdocs build --clean # 生成于 site/ 文件夹中
```

## LICENSE

本站的文本遵循 CC BY-NC 4.0

本项目内的存放的代码遵循代码文件内自带的 LICENSE。若代码文件中未附带 LICENSE，则认为该文件暂无 LICENSE，有需求者可以联系相应 committer。
