# 关于本页的一些说明
1. Java 是 Oracle 的商标
2. 本页对版权的有关说明，仅作为参考，以 Oracle 等相关发行方解释为准。
3. Java 目前版本演进很快，而高校环境下的厂商使用的 JDK/JRE 往往严重过时，需要校方和厂商从安全和合规性角度出发沟通协调。

## 关于 Oracle Java SE 产品的授权
自 Java 8 和 Java 11 发布以来，Oracle 禁止在商业环境中未授权地使用其 Java 运行时。个人用户、开发用途可以使用 Oracle 发布的 Java 运行时二进制。

请参考：
1. [Oracle Java SE Licensing FAQ](https://www.oracle.com/technetwork/java/javase/overview/oracle-jdk-faqs.html)
2. [Oracle Technology Network License Agreement for Oracle Java SE](https://www.oracle.com/downloads/licenses/javase-license1.html)

# 常见的 Java 发行版一览

1. [Oracle Java SE](https://www.oracle.com/java/technologies/javase-downloads.html)
2. [IBM SDK, Java Technology Edition](https://developer.ibm.com/javasdk/downloads/)
3. [Red Hat build of OpenJDK](https://developers.redhat.com/products/openjdk)
3. [Oracle OpenJDK（仅提供最新版，旧版本缺少安全补丁）](https://openjdk.java.net/install/)
4. [AdoptOpenJDK](https://adoptopenjdk.net/)
5. [Azul Zulu](https://www.azul.com/downloads/zulu-community/)
6. [Amazon Corretto](https://aws.amazon.com/corretto/)

# 几个典型 Java 发行版的支持周期快照（2020 年 5 月）

## Oracle Java SE

出处：https://www.oracle.com/java/technologies/java-se-support-roadmap.html

|版本|首发时间|标准支持服务结束|扩展支持结束|维持型支持|
|--- |--- |--- |--- |--- |
|7|2011 年 7 月|2019 年 7 月|2022 年 7 月|无限期|
|8**|2014 年 3 月|2022 年 3 月|2030 年 12 月|无限期|
|9 (非长期支持版)|2017 年 9 月|2018 年 3 月|不适用|无限期|
|10 (非长期支持版)|2018 年 3 月|2018 年 9 月|不适用|无限期|
|11 (长期支持版)|2018 年 9 月|2023 年 9 月|2026 年 9 月|无限期|
|12 (非长期支持版)|2019 年 3 月|2019 年 9 月|不适用|无限期|
|13 (非长期支持版)|2019 年 9 月|2020 年 3 月|不适用|无限期|
|14 (非长期支持版)|2020 年 3 月***|2020 年 9 月|不适用|无限期|
|15 (非长期支持版)|2020 年 9 月***|2021 年 3 月|不适用|无限期|

注：

1. 以上日期仅仅是示例，Oracle 客户（花钱买支持的）应该参考[Oracle Lifetime Support Policy](https://www.oracle.com/support/lifetime-support/)
2. ** 仅适用于 Java 客户端和服务器部署，不包括 Web Deployment Technology 和 JavaFX
3. *** 是否是长期支持版，以及长期支持版相关的日期未来可能会有变动。

## Red Hat OpenJDK 生命周期

出处：https://access.redhat.com/articles/1299013

OpenJDK 的使用权包含在 RHEL 订阅内。Red Hat 中间件的订阅包括给 Windows 平台的使用权。其他 Windows 平台上的应用，需要额外的 OpenJDK on Windows 订阅。

### OpenJDK 生命周期和 RHEL 的版本

||始于此版本 RHEL 5|始于此版本 RHEL 6|始于此版本 RHEL 7|始于此版本 RHEL 8|结束支持|
|--- |--- |--- |--- |--- |--- |
|OpenJDK 6 (1.6)|5.3|6.0|7.0|不适用|2016 年 12 月|
|OpenJDK 7 (1.7)|5.9|6.3|7.0|不适用|2020 年 6 月|
|OpenJDK 8 (1.8)|不适用|6.6|7.1|8.0|2026 年 5 月*|
|OpenJDK 11|不适用|不适用|7.6|8.0|2024 年十月|

### OpenJDK 生命周期和 Windows 的版本

||增加了 Windows Server 2012 R2 支持|增加了 Windows Server 2016 支持|增加了 Windows 7,8, and 10 支持|增加了 Windows Server 2019 支持|结束支持|
|--- |--- |--- |--- |--- |--- |
|OpenJDK 8 (1.8)|2018 年 8 月|2018 年 8 月|2018 年 12 月|2020 年 2 月|2026 年 5 月|
|OpenJDK 11|2018 年 8 月|2018 年 8 月|2018 年 12 月|2020 年 2 月|2024 年10 月|
