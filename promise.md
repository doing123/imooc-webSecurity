## Promise
* 异步操作避免界面冻结
    * 事件侦听与响应
    * 回调：Ajax、FileAPI

* 回调 4 个问题
    * 嵌套层次很深，难以维护
    * 无法正常使用return和throw
    * 无法正常检索堆栈信息
    * 多个回调之间难以建立联系

* 执行器

* Promise 3 个状态
    * pending
    * fulfill
    * rejected

* promise状态改变，就会触发.then()里面的响应函数处理后续步骤
* promise状态一经改变，不会再变

* then展开使用，避免嵌套
* 错误处理： 建议 catch， 也可以reject