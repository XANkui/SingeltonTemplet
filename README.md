# SingeltonTemplet
泛型单例模板

//TODO 添加过场不销毁功能；添加多线程锁

特点介绍：

1、泛型单例模板，继承即可使用，无需挂载脚本到游戏物体上；

2、包括 new 和 继承 MonoBehaviour 的两种类型的单例模板；

说明：new 和 MonoBehaviour 类型的单例的最大区别在于：
  
      继承 MonoBehaviour 的单例可以使用 Unity 的生命函数
      
使用方法：

1、继承泛型单例；

2、编写相关接口函数；

3、直接在其他需要的脚本使用单例的方法调用对应单例中的共有函数或变量即可；

4、单例无需挂载在任何游戏物体上；
