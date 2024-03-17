# UnionDB
一个低成本高性能的地图数据存储引擎，可以替代传统PG的集中式存储
1.能力尤其适用于海量（百万）小数据文件（百万级数据）的查询检索和更新
2.不适合需要长时间存储的大数据集（超过千万），虽然可以支持，但这种情况下最好选用PG

主要模块：
百万级数据源的驱动和连接池
文件锁的增强读写协议
底层存储调度和高可用设计
读写接口API
