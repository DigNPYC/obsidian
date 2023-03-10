### 今天目标

- 执行用例（课上案例编写的用例）

- 缺陷相关知识

  ```
  能够说出软件缺陷判定标准
  能够说出项目中缺陷的管理流程
  能够使用Excel对于缺陷进行管理
  能使用工具管理缺陷
  ```

---

### 一、用例执行

> 说明：执行结果与用例的期望结果不一致（含义），为缺陷。

![image-20211027093138826](img/image-20211027093138826.png)

- 执行失败的用例

![image-20211027095615336](img/image-20211027095615336.png)

```
提示：用例执行不通过为缺陷，需要进行缺陷管理
```

### 二、缺陷

#### 2.1 定义

```
软件中存在的各种问题，都为缺陷，简称bug；
```

#### 2.2 缺陷标准

```
1、少功能
2、功能错误
3、多功能
4、缺少隐性功能
5、易用性（软件测试人员专业角度）
```

#### 3.3 缺陷产生的原因

```
1、需求文档
2、架构设计
3、编码实现
4、环境（硬件、软件）
```

#### 3.4 缺陷的生命周期

![image-20211027103536357](img/image-20211027103536357.png)

```
1、回归测试：
	①常规项目回归：项目本次发布新增2个模块，最基本要测新增模块功能及新增模块关联的旧模块。
	②非常规项目（银行、部队、航天）：新增功能，必须全部复测。
2、回归bug：上一个版本发现的缺陷，开发修复完毕，在下个版本进行重新验证。
```

#### 3.5 缺陷核心要素

![image-20211027110033840](img/image-20211027110033840.png)

#### 3.6 缺陷提交要素

![image-20211027110024249](img/image-20211027110024249.png)

#### 3.7 缺陷类型

```
1、功能错误
2、UI页面错误
3、兼容性
4、数据（数据库）
5、易用性
6、建议
7、架构缺陷
```

----

- 工作流程（小结）

```
设计用例->执行用例（执行测试）->缺陷（提交、验证、关闭）
缺陷定义：任何问题（Bug）
缺陷标准：多功能、少功能、错误、缺少隐性功能、易用性
描述缺陷重点：缺陷标题、前置条件、复现步骤、预期结果、实际结果、附件备注
提交缺陷信息：指派人、缺陷等级、修复优先级、类型、状态（统计缺陷）
```

----

### 三、缺陷管理

#### 3.1 excel示例

![image-20211027144614178](img/image-20211027144614178.png)

#### 3.2 缺陷跟踪流程

![image-20211027144711475](img/image-20211027144711475.png)

```
提示：知道测试和开发流程中涉及的工作即可。
```

#### 3.3 提交注意事项

![image-20211027144811825](img/image-20211027144811825.png)

```
面试题：发现缺陷后，首先回怎么办？--确定Bug可复现、确定是Bug。
提交时，要检查缺陷是否已存在。
```

#### 3.4 缺陷管理工具

```
1、项目管理工具-管理缺陷 (禅道、JIRA、TFS)
2、Excel管理缺陷
```

#### 3.5 禅道（项目管理工具）

- 地址：https://demo.zentao.net/user-login.html

- 特点：

  ![image-20211027150242321](img/image-20211027150242321.png)

- 使用流程图

  ![image-20211027150226237](img/image-20211027150226237.png)

- 使用禅道管理缺陷

  - 登录

  ![wecom-temp-733fc2924637799dc61c23b4020656c9](img/wecom-temp-733fc2924637799dc61c23b4020656c9.png)
  - 创建缺陷

  ![wecom-temp-6478a8fb72f4e88ff091ba184a3ec432](img/wecom-temp-6478a8fb72f4e88ff091ba184a3ec432.png)

  ![wecom-temp-e7efbcedba952aadb5a83e9b76ab65e0](img/wecom-temp-e7efbcedba952aadb5a83e9b76ab65e0.png)

  - 关闭缺陷

  ![wecom-temp-ead870780da1b3c9fbdc704a51706b3b](img/wecom-temp-ead870780da1b3c9fbdc704a51706b3b.png)

#### 3.6 缺陷标题扩展

![image-20211027170926652](img/image-20211027170926652.png)











### 作业讲解（day02）

![image-20211027121130395](img/image-20211027121130395.png)

### 今晚作业

![image-20211027182846022](img/image-20211027182846022.png)

```
将以上测试点/功能点，转为用例。
```

