# 课程内容

组件之间的通信：

​	1  父子之间通信

​		输入属性 @input
​			** 使用场景： 不关心属性变化，没有额外的操作

​		Setter 访问器属性 
​			** 使用场景： 希望对输入值进行额外的处理

​	2 子传父之间通信
​			@Output

​	3 兄弟节点通信
​			自定义一个全局的 `CommunicateService` 服务， 并实例化一个 Subject 类的实例，作为传输消息的载体   ； 通过 Subject 类实例中的两个方法：emit、subscribe   或实例化 EventEmitter 类

监听组件的变化： 

​	ngOnChanges 监听组件的变化  -  等价于 vue 中的 watch

​		** 使用场景：当组件中属性值发生变化的时，需要做些额外的操作

​	

组件的上传操作：大概思路

​	1 安装上传模块   ngx-uploader

​	2 后端处理图片上传

​	3 返回上传成功后图片内容并更新会话中内容	

显示学习的课程：

​	