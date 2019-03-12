## 运行spring cloud 例子  

相关镜像git仓库:https://github.com/openedbox/zolppop  

本地部署:  
git clone https://github.com/openedbox/zolppop-demo  
cd zolppop-demo/deploy/local  
docker-compose up -d  

启动成功后 访问http://localhost:8500查看consul ui确认相关服务（configserver,gateway）是否启动