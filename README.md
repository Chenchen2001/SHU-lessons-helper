# SHU-lessons-helper
上海大学选课助手，让你不用时刻坐在电脑前等心仪的课有空缺，不再受被占课之苦，而且不会导致账号被ban，请放心使用：）

############################天下苦占课久矣！！！############################


1、配置Python环境:
    selenium、bs4
  
2、更改学号、密码、课程号、教师号，然后可以开始尝试抢课了

3、本脚本适用某课已经被选满并且限制人数的情况下，类似列车抢票的原理，有人退课则立马抢进，并不是使用就一定会抢课成功哦。

4、在抢课过程中可以做其他任何事，但请不要换校园网。

5、脚本写的较为匆忙，没有加入异常处理，请见谅。

6、小脚本有很多问题，经过尝试已经抢到几门课，欢迎大家改进、指导、斧正。邮箱：silicon@shu.edu.cn

7、此脚本仅可用于学习用途，其余做法产生的结果本人概不负责。

8、（1）有同学反映会无限打开浏览器，本人发现原因是第70行的解析器设置为lxml，可能因为版本问题不适用，将其改成html.parser即可
   （2）有同学反映更改driver路径会报错，请在路径前加一个r即可解决      例：r"C:\Users\xxxxxx"

9、先尝试是否能使用，不能使用再进行以下配置

请先安装谷歌浏览器chrome和配置chrome的chromedriver

chromedriver下载地址http://npm.taobao.org/mirrors/chromedriver/

请按照浏览器版本下载，下载好后请将其放到谷歌浏览器根目录和python根目录下

将webdriver在浏览器目录中的绝对地址复制到py文件中，覆盖掉之前存在的示例地址
