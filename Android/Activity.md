# Android--Activity #
## Activity的生命周期 ##
![](activity.jpg)
## Activity的回调方法 ##
- onCreate()	这是第一个回调，在活动第一次创建时调用
- onStart()	这个回调在活动为用户可见时被调用
- onResume()	这个回调在应用程序与用户开始可交互的时候调用
- onPause()	被暂停的活动无法接受用户输入，不能执行任何代码。当当前活动将要被暂停，上一个活动将要被恢复时调用
- onStop()	当活动不在可见时调用
- onDestroy()	当活动被系统销毁之前调用
- onRestart()	当活动被停止以后重新打开时调用
