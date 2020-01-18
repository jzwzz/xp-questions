# xp-questions

## 典型问题

<details><summary>1. 推广与落地：怎么在项目里向同事推广/落地TDD？</summary>
<ul>使用TDD会在前期耗费许多时间，当项目工期很紧时，如何协调好时间？</ul> 
<ul>这种方式得不到认可又怎么推进TDD工作？</ul>
<ul>自己如何判断一个团队或者一个项目是否适合TDD？/ 什么样的团队适合TDD？</ul>
<ul>具体怎样在实际项目中落实TDD？/ 如何去从0开始推行TDD？</ul>
</details>

<details><summary>2. 任务拆分：怎么更有效地拆分Task？在需求不明确的情况下如何开始？</summary>
<ul>重构到什么程度？</ul>
<ul>怎么避免过度设计</ul>
</details>

<details><summary>3. 场景与边界：常用的CRUD怎么写测试？TDD需要覆盖哪些代码？TDD在任何时候都合适吗？</summary>
<ul>TDD适合多大的项目规模？</ul>
<ul>TDD的最佳实践是什么？</ul>
</details>

<details><summary>4. 测试的粒度：Task/Test Case如何做到不大不小？TDD的步子多大合适？</summary>
<ul>怎么更好地控制测试驱动的步伐？</ul>
<ul>如何把握小步快跑的尺度？</ul>
<ul>步子太小的话，不是会出现时间长忘记整体的情况吗？</ul>
<ul>简单需求可以驱动，复杂需求的时候驱动的代码感觉缺少连贯性？</ul>
</details>

<details><summary>5. TDD即设计：“驱动”到底是内心早已拥有的思路或答案，还是真的通过测试驱动出代码实现？</summary>
<ul>TDD驱动开发如何区分是驱动出代码，还是设计代码？</ul>
</details>

<details><summary>6. 遗留系统落地：已有系统怎么落地TDD？如果需要修改原逻辑，而原逻辑没有单元测试，怎么TDD？</summary>
<ul>祖传代码如何TDD新功能？</ul>
<ul>当面对复杂业务的时候如何更好地实践TDD？</ul>
</details>

## 其他问题

### TDD与其他开发方式

* 如果在概要设计之后，已有清晰的思路，一小步一小步的TDD是否仍有必要？
* TDD如何与架构师设计出来的结果结合？
* TDD只是敏捷的一小部分，一个团队是怎么样实践敏捷开发的？
* 测试用例需要仔细设计可能需要一些测试经验。开发人员如何获取这些经验用来完善测试用例设计？
* 测试跑通了真的代表业务没问题了吗？

### TDD实践/效率

* TDD在设计演进过程中会冲掉之前的case导致重复工作吗？
* 如果TDD到一半发现自己写的不合理，是推翻前面的test case，还是在前面的基础上修改？
* 跑单元测试启动整个项目太慢，如何避免？
* 如何让测试类更好维护？
* 为什么测试一定要有assert？
* UI实现用TDD驱动是否太繁琐且不好测试？
* 驱动时，怎么知道简单实现还是创建对象？（比如停车场的例子，`Car`应该是`string`还是`Car`类型）

### Tasking

* 对于Task的划分在业务和技术的分界线在哪里？

### 真的是其他

* 如果完全没有数据建模，怎么多人协作？
* 感觉简单的demo并不能反映真实的业务场景？

## 
