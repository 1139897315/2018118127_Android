# 子服务的绑定，子服务代码运行在异步任务。

界面

![image-20201128233645505](README.assets/image-20201128233645505.png)

点击绑定按钮，onServiceConnected()方法在活动与服务成功绑定时调用。

![image-20201128233241048](README.assets/image-20201128233241048.png)

点击取消绑定按钮，onServiceDisconnected()方法在活动与服务连接断开时调用。

![image-20201128233314480](README.assets/image-20201128233314480.png)