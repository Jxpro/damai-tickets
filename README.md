# 大麦网抢票脚本案例

## 🛠️环境要求

- Python 3.6 +
- Chrome和[chromedriver.exe](http://chromedriver.storage.googleapis.com/index.html)（注意与chrome版本相匹配）
- `pip install -r requirements.txt`

## ❗️ 重要说明

参考代码1：[ticket1.py](https://github.com/Entromorgan/Autoticket)

通过selenium模拟点击，存在webdriver特征，无法通过滑块验证

> 参数说明：
>
> - `session`: 场次优先级列表
> - `price`: 票价优先级
> - `real_name`: [1,2], 实名者序号
> - `nick_name`: 用户在大麦网的昵称，用于验证登录是否成功
> - `ticket_num`: 购买票数
> - `damai_url`: [https://www.damai.cn](https://www.damai.cn/), 大麦网官网网址
> - `target_url`: https://detail.damai.cn/item.htm?id=599834886497 目标购票网址
>

参考代码2：[ticket2.py](https://github.com/MakiNaruto/Automatic_ticket_purchase)

通过selenium登录获得cookie后，使用requests直接发送请求，最后一步无法成功提交订单

## 📧联系方式

If you have any concerns here, please post as Github issues, or send an e-mail to Joker Xin by [jxpro@qq.com](mailto:jxpro@qq.com).