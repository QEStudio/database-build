# database-build

## 关于此仓库
用于database-daemon的数据库构建下载源

### 这个仓库构建和支持什么了什么数据库相关软件?
``` bash
CloudBeaver # 开源的 Web 版数据库管理工具，无需安装客户端，通过浏览器直接连接 MySQL、PostgreSQL、Oracle 等多种数据库。支持 SQL 编辑、数据导入/导出、多用户协作，适合远程管理和团队共享。

MySQL # 最流行的开源关系型数据库，使用 SQL 语言，支持事务、索引，广泛用于 Web 应用（如 WordPress、电商平台），性能稳定，社区生态成熟，适合中小型项目

PostgreSQL # 功能强大的开源对象关系型数据库，支持复杂查询、JSON、全文搜索、自定义类型，标准 SQL 兼容性极高，适合对数据完整性和复杂业务要求较高的企业级应用

Redis # 基于内存的 Key-Value 存储数据库，读写速度极快（微秒级），支持字符串、Hash、List、Set 等多种数据结构，常用于 缓存、Session管理、消息队列、排行榜 等高并发场景

MongoDB # 主流的 NoSQL 文档型数据库，数据以 BSON（类 JSON）格式存储，无需固定 Schema，横向扩展能力强，适合 非结构化数据、快速迭代开发 和大数据量的读写场景
```

### 数据库管理面板支持
有cloudbeaver和mongo-express

其中mongo-express由于所使用nodejs编写，无需编译且开源可单独下载 此只做缓存
## 关于贡献
暂不支持贡献，如果有需要请你反馈给我们，我们会顺带更新database-daemon支持