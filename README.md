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
            - 英式理发店
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
    - 剑桥大学技术服务使用指北
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
        - CamSIS (剑桥大学学生信息系统)
            - 在读证明开具
            
- [colleges.md](colleges.md)
    - 31个学院信息汇总
        - Trinity College
        - St John's College
        - King's College
- [application.md](utils.md)
    - 本科申请
    - 硕士申请
    - 博士申请


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
