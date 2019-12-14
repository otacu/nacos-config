nacos作为配置中心例子

启动
nohup>nohupGps java -jar nacos-config.jar 2>&1 &

linux 模拟请求测试
curl "http://127.0.0.1:18082/user"