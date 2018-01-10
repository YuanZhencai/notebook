# Junit断言

[首页](http://junit.org/junit4/.md)


## 断言方法

1.检查两个变量或者等式是否平衡

    void assertEquals(boolean expected, boolean actual)

2.检查条件为真
    
    void assertTrue(boolean expected, boolean actual)

3.检查条件为假

    void assertFalse(boolean condition)

4.检查对象不为空

    void assertNotNull(Object object)

5.检查对象为空

    void assertNull(Object object)

6.*assertSame()*  方法检查两个相关对象是否指向同一个对象

    void assertSame(boolean condition)

7.*assertNotSame()*  方法检查两个相关对象是否不指向同一个对象

    void assertNotSame(boolean condition)

8.*assertArrayEquals()*  方法检查两个数组是否相等

    void assertArrayEquals(expectedArray, resultArray)




