<img src="https://user-images.githubusercontent.com/9434884/43697219-3cb4ef3a-9975-11e8-9a9c-73f4f537442d.png" alt="Sentinel Logo" width="50%">

# Sentinel Nacos 双向同步持久化版本

## 打包命令

mvn clean package -DskipTests

然后将 sentinel-dashboard.jar 改名为 sentinel-dashboard-nacos-1.8.6.jar

## 启动命令参考

java -Dserver.port=8080 -Dcsp.sentinel.dashboard.server=localhost:8080 -Dproject.name=sentinel-dashboard -DserverAddr=localhost:8848 -Dnamespace=@namespace@ -jar ./sentinel/sentinel-dashboard-nacos-1.8.6.jar

## [Sentinel原项目地址](https://github.com/alibaba/Sentinel)

## Documentation

See the [Sentinel Website](https://sentinelguard.io/) for the official website of Sentinel.

See the [中文文档](https://sentinelguard.io/zh-cn/docs/introduction.html) for document in Chinese.

See the [Wiki](https://github.com/alibaba/Sentinel/wiki) for full documentation, examples, blog posts, operational details and other information.

Sentinel provides integration modules for various open-source frameworks
(e.g. Spring Cloud, Apache Dubbo, gRPC, Quarkus, Spring WebFlux, Reactor) and service mesh.
You can refer to [the document](https://sentinelguard.io/en-us/docs/open-source-framework-integrations.html) for more information.

If you are using Sentinel, please [**leave a comment here**](https://github.com/alibaba/Sentinel/issues/18) to tell us your scenario to make Sentinel better.
It's also encouraged to add the link of your blog post, tutorial, demo or customized components to [**Awesome Sentinel**](./doc/awesome-sentinel.md).
