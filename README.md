# Python 期末合作项目 技术文档之总结说明
姓名：麦安琪

学号：181013118
## URL链接
GitHub代码URL展示链接：[https://github.com/181013118/final-project](https://github.com/181013118/final-project)
Pythonanywhere的URL展示链接：[http://aptx48697.pythonanywhere.com/](http://aptx48467.pythonanywhere.com/)

#### 介绍
18级《Python》与17级《交互式数据可视化》协作期末项目

#### 项目主题
主题是《中国各省城市生活垃圾清运和处理情况分析》，主要通过生活垃圾清运量、生活垃圾无害化处理量、处理率、处理能力、处理方式（填埋和焚烧）这五个方面进行分析。**本项目的意义在于对中国各省城市生活垃圾的清运和处理情况进行可视化分析，从可视化结果针对中国各省解决城市生活垃圾提出有效建议，从而达到缓解垃圾处理压力、促进循环经济和可持续发展的目的。**

#### 文档描述
在python中包含了一个aap.py，一个css文件，10个html文档，其中10个html文档中有一个是主页面（view.html），5个跳转页面内连接4个可视化页面。除开首页有5个url，分别是[各城市生活垃圾清运和处理情况分析](http://aptx48467.pythonanywhere.com/hurun)、[生活垃圾清运量可视化](http://aptx48467.pythonanywhere.com/clear)、[生活垃圾无害化处理量可视化](http://aptx48467.pythonanywhere.com/deal)、[生活垃圾无害化处理率可视化](http://aptx48467.pythonanywhere.com/with)、[填埋和焚烧两种方式对比可视化](http://aptx48467.pythonanywhere.com/way)

#### HTML档描述
* 所有的HTML文件放置在templates文件夹中，view.html为模板，展示首页表单和项目介绍。
* static文件夹中添加了css样式，调整了网页可视化图和表单的布局，增加了网页背景色和按钮交互样式

#### Python档描述
* 由app.py文件运行最终结果
* 安装并导入pandas、pyecharts、flask等模块，实现数据可视化，展示各样的图表
* Flask框架中运用@app.route加入可变参数url，用get或post展示页面，用with语句打开文件


#### Web App动作描述
首页有5个选项可以点击，表格下拉框选择搜索区域，确定按钮获取表单实现跳转，另外4选项个是查看可视化图表，进去二级界面后有返回首页的选项。
