# 在线购物中心商城系统
## 技术栈
Docker Compose + FastAPI后端 + Nginx静态前端 + MySQL数据库
包含完整功能：
1. 用户注册、登录身份校验
2. 50件10大类商品，30秒自动随机刷新、AI导购推荐、关键词搜索
3. 购物车增删、库存扣减、一键结算下单
4. 历史订单查看、订单明细展示

## 本地启动
```bash
docker compose down
docker volume rm mall_mysql-data
docker compose up --build -d
访问地址：http://localhost
