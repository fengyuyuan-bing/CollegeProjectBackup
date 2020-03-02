# 简介


[这个油猴脚本](https://greasyfork.org/zh-CN/scripts/395847-%E6%96%B0%E7%89%88%E6%AD%A3%E6%96%B9%E6%95%99%E5%8A%A1%E7%B3%BB%E7%BB%9F%E5%AF%BC%E5%87%BA%E8%AF%BE%E7%A8%8B%E8%A1%A8)主要是针对新版的正方教务系统，实现将课程表转化为一个 ``courses.ics`` 文件，这样就可以 **愉快** 的使用 ``Google Calendar`` 来看课程表了，~~（唉，我好像快毕业了哎，，，~~ ，

# 食用方法

安装油猴扩展，然后安装脚本

在使用前进入到要导出课程表的页面，![](https://raw.githubusercontent.com/31415926535x/CollegeProjectBackup/master/ZhengfangClassScheduleToICS/img/1.PNG)

然后确定这学期开学的第一周的周一的日期，![](https://raw.githubusercontent.com/31415926535x/CollegeProjectBackup/master/ZhengfangClassScheduleToICS/img/2.PNG)

点击 ``生成课表`` 然后就会提示导出成功，这时点击旁边的 ``下载ics文件`` 即可下载 ``course.ics`` 文件，![](https://raw.githubusercontent.com/31415926535x/CollegeProjectBackup/master/ZhengfangClassScheduleToICS/img/3.PNG)

之后怎么使用就看你了，，这样可以不再使用各种 **课程表 等看个课程表还要等半天，看半天广告，而且还占空间。。~~（深受其害.jpg）~~

# 总结

第一次写脚本，js用的也不熟练，这个脚本参照了一个学长之前根据旧版教务系统的课程表导出脚本写的，一直想自己写一个，一直拖到了新版教务系统，，，无聊时练下手，所以脚本的只是一个可以使用的状况，其中的一些处理没有考虑效率的问题~~（数据量又不大，暴力就完事了嘛）~~ ，其中可能还存在一些bug每一处理，希望遇到的朋友可以提个issues，嘿嘿。

# TODO

有时间将考试信息也加上。。。

# 参考

https://gist.github.com/yulanggong/be953ffee1d42df53a1a