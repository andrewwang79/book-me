# excel

## 使用
* =VLOOKUP(A1, 'sheetX'!$A$1:$B$10000, 2, False) // 按照A1去精确匹配range('sheetX'!$A$1:$B$10000)的第1列(默认，无法配置)，显示range的第2列
  * 参数1：匹配的cell
  * 参数2：区域，默认匹配第一列
  * 参数3：显示区域的第几列
  * 参数4：模糊匹配flag
## Excel计算时间差（精确到分钟、秒）
* 设置单元格格式为常规，时间形式为“2017-9-28 18:14:49”
* 精确到分钟:ABS(J1-K1)*1440 或者INT(K1-J1)*1440
* 精确到秒:ABS(J1-K1)*1440*60

## 透视图表
* https://www.zhihu.com/question/22484899
* https://www.jianshu.com/p/23c8984f7cc7
* [公式.xlsx](https://me.wangyaqi.cn/kb/excel/公式.xlsx)
* [快速复制多行或整列公式](http://blog.sina.com.cn/s/blog_14e89401f0102wnzk.html)方法1
