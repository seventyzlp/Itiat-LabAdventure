# 实验室日记UE5开发日志

Developed with Unreal Engine 5
***

### 2022.7.12
1. 完成对话框的触发和剧本导入到窗体蓝图文件
   1. 通过设置actor碰撞事件来触发创建窗体事件，生成对话框
   2. 把创建完的对象添加到视口
   3. 设置actor结束碰撞事件来删除父类对象，设置父类为资源库中的窗体对象
   4. 创建结构体，存储表格标题行，并且设置存储数据类型
   5. 建立数据表格，在建立是选取结构体的行结构，根据结构体存储数据信息，方便导入到窗体控件中
   6. 把剧本输入到数据表格中，并且修改行命名为数字，用于跳转下一行输出
   7. 打开控件蓝图，需要先放置画板后才能自由操纵文本框什么的大小、位置
   8. 如果文本框需要换行，那么需要选择多行文本框，根据表格需求绘制
   9. 选中文本框，选择添加绑定，或者说是直接绑定对应的文本，需要自定义事件进行传递
   10. 传递文本的自定义事件需要在视口蓝图图标界面，事件图表下创建自定义事件，并且为自定义事件添加输入值，并且提升为变量
   11. 选中文本框也可以创建绑定，其实跟直接调用变量没什么区别
   12. 

