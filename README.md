
## changelog

### 12.08
bugfix
- testcaseid按照文件名填写即可
- nodeid重复写入问题
- 支持同步模式 --index -1，默认是并行
- setupClass支持延迟time.sleep、等待开始wait_to，其他关键词与框架一致
- session控制 http://127.0.0.1:20000/session?action=pause|start|stop