# SAS_tidyverse

## 这是个啥
SAS_tidyverse提供类似于tidyverse包及R函数使用习惯的宏程序, 也是***a grammar of data manipulation*** ,***a grammar of data manipulation***.

## 为什么做
*好的设计让人爱不释手，它很美---***pipe philosophy ***!
*希望能帮助到工作做需要用SAS的码农们

**我们产生不了源代码，只是代码的搬运工**

## 目前已包含哪些内容
   *类似于dplyR的：*
   %filter(),  %select(),  %mutate(),  %group_by(),  %summarise(),  %count(), %summarise_all(),  %left_join(),%left_join_(),%rename().
   *类似于 R base的：*
   %nrow(),  %ncol(),  %names(),  %head(),  %extract(),  %view()
  *其他*
   %with(),  %as(),  %remove(), %sort(),  %sort_nodup(),  %contents(), %format(),%freq()

## 特点：
*类似于dplyR函数，可以输入不限定个数的参数
*通过数据操作指针，实现类似R 的pipe语法功能
*names,ncol,nrow,rename,format等函数采用了高效的处理方式，直接读取和直接改变属性
*extract,能看到python的影子（不谋而合而已）


