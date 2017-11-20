# MongoDB 3.4


## new feature

- 全量同步（initial sync）改进，目前如果initial sync中间断开了，需要整个重来，改进后并行度提高，而且断开后能够接着上次的进度继续同步。
- 支持自定义文档排序规则（比如按ascii、utf8来排序）
- 只读视图（readonly view）
- recursive lookup，目前只支持简单的left join
- mongodb compass（企业版）在geo index、explain、crud操作上有很大的改进
- bi connector功能提升（企业版）