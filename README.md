# README

从雷池获取每日的统计数据并且推送到飞书机器人，雷池的社区版（免费版）不支持

[官方的API文档](https://docs.waf-ce.chaitin.cn/zh/%E6%9B%B4%E5%A4%9A%E6%8A%80%E6%9C%AF%E6%96%87%E6%A1%A3/OPENAPI)

需要设定3个变量

- ${{ secrets.WAF_HOST }} 形如`https://waf.xx.com:9443`
- ${{ secrets.WAF_TOKEN }}
- ${{ secrets.FEISHU_URL }}

## TODO

- [ ] 定时攻击信息推送