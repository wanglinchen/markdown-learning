# **markdown learning**
[TOC]

## *斜体字*  

## **加粗**

## 分隔线
*******************************************************  

## 引用
> 引用1
>>引用2

## Emoji 表情
:smile:
:sunny:
:cloud:

## 选项框
- [x] 选项一
- [ ] 选项二  

## markdown注释
<pre>
## 这是一个不起作用的标题
</pre>

## 键盘按钮
<kbd>Enter</kbd>

## 无序列表
* 1级无序列表  
    * 2级无序列表  
        * 3级无序列表3级   

## 有序列表
1. 有序列表  
2. 有序列表  

## 区块
> 区块  
>> 嵌套区块  

## 代码
``` C
int main(void)
{
    printf("hello\n");
    return 0;
}
```  
## 链接
[百度链接](https://www.baidu.com/):`https://www.baidu.com/` 

## 图片
![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)  

## 表格
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟  

[^注脚]

## 引用符号
\*  
\\
\? 

## 数学表达式
积分运算  
$\int^{\infty}_{0}{xdx}$

平均数运算  
$\overline{xyz}$  

开方运算  
$\sqrt[3]{x+y}$

## 流程图
```flow
st=>start: start
op=>operation: handle
cond=>condition: judge
sub1=>subroutine: subroute
io=>inputoutput: input&output
e=>end: end
st->op->cond
cond(yes)->io->e
cond(no)->sub1(right)->op
```

```sequence
对象A->对象B: 对象B你好吗?（请求）
Note right of 对象B: 对象B的描述
Note left of 对象A: 对象A的描述(提示)
对象B-->对象A: 我很好(响应)
对象A->对象B: 你真的好吗？
```

[^注脚]:在文档中添加补充说明  

