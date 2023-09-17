# RSSC合作规范

### API First
api工具：apifox。

教学视频：https://www.bilibili.com/video/BV1ae4y1y7bf/?spm_id_from=333.788&vd_source=106148829f4208e816e76f0b673079ad

先商量api再写代码，提升效率

后端、前端、测试团队可以同步开始工作，而不需要互相等待；

使用基于API的自动Mock、代码自动生成和自动化测试工具，大幅提升开发效率；

开发的各个角色都会获得更好的工作体验；

API可以在不同的项目中重复使用，提高开发效率；

新人更容易熟悉项目，方便团队规模的扩大；

与外部团队的协作也更加顺畅

### 设计阶段

根据需求文档讨论确定接口设计思路。

接口设计者在Apifox上定好接口文档初稿。

接口评审环节，前后端一起评审、完善接口文档，定好接口用例。

### 开发阶段

  #### 前端

  ·Apifox会根据接口文档自动生成Mock数据，直接可以进入开发，无需手写mock规则。

  #### 后端

  使用Apifox直接根据接口定义来调试接口，每次调试一个功能就保存一个接口用例，方便自己反复调试。
  
  如果开发过程中接口有变化，调试的时候修改接口定义就自动更新了文档，零成本地保障了接口维护的及时性。

  ### 测试
  
  直接使用后端调试时保存的接口用例生成讽测试用例。
  
### 联调和测试阶段

所有接口开发完成后，测试人员（也可以是后端）使用集合测试功能进行多接口集成测试，完整测试整个接口调用流程。

前后端都开发完，前端从Mock数据切换到正式数据，联调通常都会非常顺利。因为联调周过程中最经常出现的问题就是前后端双方的数据定义不一致，而使用Apifox进行开发保证了所有人都完全遵守接口定义的规范，以前存在的很多令人头大的问题就不存在了。

### 业务逻辑

先画逻辑流程图再实现，流程图保存到自己负责板块的文档里。方便后续问题解决和优化。

