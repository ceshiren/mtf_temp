## changelog

### 0.2.0

- 增加shell mock
- 增加手工测试
- 增加--clean参数自动清理日志
- 支持单个串行suite的报告
- todo: mock日志
- session控制日志
- todo: 用例位置提示

### 0.1.5版本

- 重构了suite的大部分逻辑
- 修改了nodeid，可以在报告中直接展示suite套件的层次
- 端口默认读取suites.yaml中的config.server

### 12.08

bugfix

- testcaseid按照文件名填写即可
- nodeid重复写入问题
- 支持同步模式 --index -1，默认是并行
- setupClass支持延迟time.sleep、等待开始wait_to，其他关键词与框架一致
- session控制 http://127.0.0.1:20000/session?action=pause|start|stop