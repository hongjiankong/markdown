# markdown 语法
## 1. 标题
    在想要设置为标题的文字前面加#来表示一个#是一级标题，二个#是二级标题，以此类推.支持六级标题.
> # 这是一级标题(H1)
> ## 这是二级标题(H2)
> ### 这是三级标题(H3)
> #### 这是四级标题(H4)
> ##### 这是五级标题(H5)
> ###### 这是六级标题(H6)

## 2. 字体
+ 加粗 左右两个**
    > **Example**
+ 斜体 左右一个*
    > *Example*
+ 斜体加粗 左右三个*
    > ***Example***
+ 删除线
    > ~~Example~~

## 3.引用
    在引用的文字前加>即可。引用也可以嵌套
> **Example**
>>**Example**
>>>**Example**
>>>>**Example**
>>>>>**Example**
>>>>>>**Example**
>>>>>>>**Example**
>>>>>>>>**Example**
>>>>>>>>>**Example**
>>>>>>>>>>**Example**
>>>>>>>>>>>**Example**
## 4.分割线
    三个或者三个以上的 - 或者 * 都可以

---
----
***
*****

## 5.图片
    ![图片alt](图片地址 ''图片title'')

**图片alt就是显示在图片下面的文字，相当于对图片内容的解释。**
**图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加**

![aaa](https://ss0.baidu.com/6ONWsjip0QIZ8tyhnq/it/u=2795980557,2077253840&fm=58&bpow=1024&bpoh=1664 'Markdown')




## 6.超链接
    [超链接名](超链接地址 "超链接title")
[Google](https://wwww.google.com)

## 7.列表
+ 无序列表用 - + * 任何一种都可以
    + 1
    + 2  
    + 3
+ 有序列表数字加点
    1. A
    2. B
    3. C
 
## 8.表格
    表头|表头|表头
    ---|:--:|---:
    内容|内容|内容
    内容|内容|内容

    第二行分割表头和内容。
    - 有一个就行，为了对齐，多加了几个
    文字默认居左
    -两边加：表示文字居中
    -右边加：表示文字居右

A|B|C
---|:--:|---:
1|2|3
4|5|6
7|8|9
## 9.代码
    单行代码：代码之间分别用一个``包起来

`code content`

    代码之间分别用三个反引号包起来，且两边的反引号单独占一行

```
 public partial class Emui_WPWG : BasePage
    {
        public string ot = "pt";
        protected void Page_Load(object sender, EventArgs e)
        {
            ot = Request.QueryString["ot"];
        }
    }
```
## 10.流程图
    ```flow
    st=>start: 开始
    op=>operation: My Operation
    cond=>condition: Yes or No?
    e=>end
    st->op->cond
    cond(yes)->e
    cond(no)->op
    &```


