# 服务描述文件
> - 服务介绍,维护者信息,如何部署,监控,设置警告机制
> - Date:2017-08-14 23:32:00 星期一
> - Author: guanzhenxing

我们应该为每个服务添加一些描述信息，包括服务的介绍、维护者的信息，以及如何部署、监控和设置警告机制。这样，能够帮助团队更好地理解和快速运行服务。建议，这样的描述文件可以写在项目的README.md中。

下面是一个比较通用的模板：

    # 服务介绍

    * 服务名称
    * 服务介绍

    # 维护者信息

    * 记录服务的维护者，需要能够直接联系到这个人

    # 服务的可用期

    * 服务的客用期（如：周一到周五，9:00~19:00）

    # 运行环境

    * 生产环境：
    * 地址：
    * 依赖：
    * 预生产环境：

    # 开发

    通常描述开发信息，包含但不限于以下：

    * 如何搭建开发环境
    * 如何运行服务
    * 如何调试

    # 测试

    描述测试相关的信息，包含但不限于以下：

    * 测试策略
    * 如何运行测试
    * 如何查看测试统计结果，譬如覆盖率、运行时间

    # 构建

    描述持续集成以及构建的信息，包含但不限于以下：

    * 持续集成环境
    * 持续集成流程描述
    * 构建后的部署包发布

    # 部署

    描述部署相关信息，包含但不限于以下：

    * 如何部署到不同的环境
    * 部署后的功能验证

    # 运维

    描述运维相关信息，包含但不限于以下：

    * 日志聚合的访问URL
    * 监控信息的访问URL