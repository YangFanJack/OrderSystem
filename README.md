# OrderSyestem

* 设计一个点餐系统。程序运行后，首先选择用户类型，然后从文本文件读入菜单信息

  进行初始化，根据用户类型不同在控制台界面上提供不同功能选择。用户选择某项功能

  后，根据提示进行操作；操作完成后，能返回功能选择菜单重新选择，直至用户退出。

### 客户功能：

* 预订——打印出可选菜单，提示用户选择；在用户选择后，提示用户输入个人

信息，记录下信息，并保存至本地文件。

* 查询/退订——显示所有的已订的订单列表，提示输入退订订单；用户输入后，

如果卖家尚未确认订单，则成功退订并修改本地文件；否则提示退订失败。

### 卖家功能：

* 添加/删除菜单——菜单根据文件初始化后，卖家可以对其进行修改，包括添加

和删除菜式等，修改后将新菜单保存至文件，下次初始化仍可用。

* 查询/修改订单——读取本地文件，显示所有的订单及其状态，提示确认订单或

不进行操作；卖家选择订单后，修改该订单为确认状态。