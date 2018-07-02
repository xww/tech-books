### 在线任务编排框架

####  `JOB`执行过程及其对应显示
#### 用户操作映射
| 用户操作 | `JOB`状态 | 页面显示 |
| -------- | ------- | -------- |
| 删除操作 | 无数据  | ——       |
| 停止操作 | 无数据  | 已停止   |
| 激活操作 | `READY`   | 准备中   |

#### JOB状态映射
| `JOB`状态 | `JOB`状态解释 | 页面显示 |
| --------- | ------------- | -------- |
| `READY`   | `JOB`执行结束 | 准备中   |
| `RUNNING` | `JOB`正在运行 | 正在运行 |
| `STOP`    | `JOB`异常停止 | 异常停止 |
| ——        | `JOB`不再运行 | 已停止   |

### JOB的状态转移图