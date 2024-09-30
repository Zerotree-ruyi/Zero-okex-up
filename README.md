# OKX Trading Bot
简介
这是一个为 OKX 交易平台 设计的自动化交易机器人，支持最小交易金额为 15 USDT。该机器人基于用户自定义的交易策略自动执行买卖操作，帮助用户在市场波动中抓住机会。

# 核心交易策略：
涨跌幅策略：当市场价格波动超过设定的涨跌幅（默认2%）时，机器人会自动进行交易，用户可以根据个人需求调整这个值。
交易量检测：当前K线的交易量相较于上一根K线增长达到400%时，触发交易信号。用户可以自定义这个比例。
布林带中轨判断：当价格低于布林带中轨时，机器人会根据市场行情自动操作，帮助用户进行智能化决策。
自定义参数：用户可以自由设定涨跌幅和交易量的阈值，适应不同的交易策略和市场条件。
# 交易条件：
最低交易金额为 15 USDT。
支持涨跌幅、交易量及布林带策略的自定义设置。
适用于波动较大的市场，通过交易量监控捕捉短期机会。
# 使用说明：
注册 OKX API：确保你拥有有效的OKX API密钥，以便交易机器人能够连接并执行交易。

## 第一步
创建okex-API
![001](/doc/1.png)
## 第二步
把apikey以及密钥保存好到时候配置文件需要
![001](/doc/2.png)
## 第三步
添加收款人1076052961@qq.com
![001](/doc/4.png)
## 第四步
1.使用下载zero-okex主程序，
```php
sudo su
wget https://github.com/Zerotree-ruyi/Zero-oke-v1.0/releases/download/1.0-alpha/Zero-okx-v1.3.zip
sudo apt-get install unzip
unzip Zero-okx-v1.3.zip
chmod 777 Zero-okx-v1.3
chmod 777 oke.conf
```
2.更具okex.conf提示配置

3.运行主程序Zero-okx-v1.3
```php
./Zero-okx-v1.3
```
## 第五步
1.运行主程序。将会得到激活码，复制下来发给，管理员给你授权
![001](/doc/3.png)
2.再次运行，看到此界面就是运行成功了，### 祝大家发大财
![001](/doc/5.png)
配置策略参数：根据市场环境和个人偏好，调整机器人的涨跌幅、交易量变化比例等策略参数。
启动交易：运行机器人并监控实时交易情况。机器人将根据设定的策略条件自动进行买卖。
```php
123
```
# 安全与风险提示：
请确保你对市场行情有充分了解，本机器人仅为辅助工具，不构成投资建议。
强烈建议先在模拟环境中运行，测试机器人表现，再投入实际资金。
