# 设置观察目标
## 类型
1、LiveData
2、MutableLiveData
区别在于 ”可变“
LicaData属于不可变对象，暴露给外部实现监听效果
MutableLiveData属于可变对象，最好不要暴露给外部使用
## 初始化
1、统一初始化，在initXXX()中初始化
2、getXXX初始化
