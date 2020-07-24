# input_search
原生dom编写的textarea 英文补全类输入法,

使用localStorage将词典中单个单词的使用次数进行统计,可以达到常用词在前的功能;

注: 默认词典包含专八专四的7k+词汇,可以自定义词典

使用:(改项目以下称之为"输入法")

1.初始化输入法:

$initInputSearch(DOM元素实例, 自定义词典id);

2.如果有自定义词典需要使用则引入:

$appendDiyWords(词典, 自定义词典id);

自定义词典 格式: \["a","b","c"\]

![1595553557573](https://github.com/17600774441/input_search/blob/master/readmeImg/1595553557573.png)





![1595553580228](https://github.com/17600774441/input_search/blob/master/readmeImg/1595553580228.png)

添加自定义词汇会检测该单词是否存在