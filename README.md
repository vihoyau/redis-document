# redis的工作原理和机制（外部）

**说明** ：该文档用于记录开发中遇到的问题，如有需要协助或不规范的地方，请联系工作人员邱伟豪，为了您的阅读便利，我们会及时更正错误。感谢您的阅读。注：redis是一个非常优秀的非关系型数据库，我们现在详细探讨一下redis的应用场景和工作原理，希望这些笔记能帮到您更好的理解redis。

## 1.Redis的使用

**使用的功能分别有**：Redis命令、管道、redis发布订阅、内存优化、过期、把redis当缓存、Redis事务、大量插入数据、从文件中批量插入数据、分区、分布式锁、key事件通知、创建二级索引

### 1.1 Redis命令

**微注**：一共14个命令组，组成200多个命令。Cluster、Sets、Lists、Pub\Sub、Scripting、Server、Strings、Hashes、Connection、Keys、HyperLogLog、Transations、Sorts sets
