1. 使用volatile变量的场景
  * 对变量的写入操作不依赖变量的当前值，或者确保只有单个线程更新变量的值
  * 该变量不会与其他状态变量一起纳入不变性条件中
  * 在访问变量时不需要加锁
