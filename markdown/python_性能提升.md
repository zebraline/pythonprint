## python 性能提升

* 字典读取是O（1），列表读取是O（n），尽量使用字典
* 使用内置函数，比如add，join,format，比+要快速
* 使用字符串属性，isdigital，isalpha
* 使用列表解析，代替for循环
* 使用集合求解交集并集，代替for循环比较
* 使用if判断，减少执行
* 使用生成器代替列表，xrang等
* 减少函数调用次数，在函数内部实现循环