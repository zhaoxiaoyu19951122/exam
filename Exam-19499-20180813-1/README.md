项目运行流程：
首先要在本地新建一个数据库，名称为sakila，username为root，password为admin，再通过sql脚本导入数据。
1.检查tomcat配置信息，设置默认跳转路径为 http://localhost:8080/index.jsp
2.启动tomcat
3.index界面，点击登录链接就能跳转到登录界面，在未登录状态下点击进入主页会延时1s跳转到登录界面并给出友好提示。
4.登录界面，输入用户ID和名称，正确即可登录。例如：id为1 名称为MARY
5.主界面 点击显示列表展示数据，并加载出功能键（新建、删除、修改）
6.点击新建按钮弹出新建菜单，填写完毕后点击保存即可保存。
7.选中一行要删除的数据，点击删除按钮进行删除，否则会弹出提示框提示选择一行。
8.同删除一样，修改需要点击一行要修改的数据进行修改，不点击则会提示并不做操作。
github链接 https://github.com/zhaoxiaoyu19951122/exam.git
