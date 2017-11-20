# MongoDB 3.2


## new feature

- 默认的存储引擎从mmapv1切换为wiredtiger，提升性能的同时也能通过压缩降低存储成本
- 复制集的选举使用raft协议，可靠性进一步增强
- 支持文档校验功能（document validation）
- 支持left join（$lookup）
- 支持in memory存储引擎（企业版）