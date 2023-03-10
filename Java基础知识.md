# 12. Java基础知识

- [12.1 Java 类型举例](#121-java-类型举例)

- [12.2 Java 数据类型的默认值](#122-java-数据类型的默认值)

## 12.1 Java 类型举例
        
  | 术语 | 中文含义 | 举例 |
  |:-------:|----------|:-------:|
  | Parameterized type |    参数化类型    |    `List<String>`    |
  | Actual type parameter    |    实际类型参数    |    String    |
  | Generic type  |    泛型类型    |    `List<E>`    |
  | Formal type parameter     |    形式类型参数    |    E    |
  | Unbounded wildcard type     |    无限制通配符类型    |    `List<?>`    |
  | Raw type     |    原始类型    |    List    |
  | Bounded type parameter |    限制类型参数    |    `<E extends Number>`    |
  | Recursive type bound |    递归类型限制    |    `<T extends Comparable<T>>`    |
  | Bounded wildcard type |    限制通配符类型    |    `List<? extends Number>`    |
  | Generic method |    泛型方法    |    `static <E> List<E> asList(E[] a)`    |
  | Type token |    类型令牌    |    `String.class`    |


## 12.2 Java 数据类型的默认值


  | Data Type | Default Value (for fields) |
  |-------|----------|
  | byte |    0    |
  | short    |    0    |
  | int  |    0    |
  | long |    0L    |
  | float    |    0.0f    |
  | double  |    0.0d    |
  | char |    `'\u0000'`    |
  | String (or any object)    |    null    |
  | boolean  |    false    |