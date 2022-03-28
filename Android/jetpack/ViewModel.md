# 设置观察目标
## 作用
1、分离数据显示和数据获取、解析
2、定义观察者对象，实现实时变化
## 类型
1、LiveData
2、MutableLiveData
区别在于 ”可变“
LicaData属于不可变对象，暴露给外部实现监听效果
MutableLiveData属于可变对象，最好不要暴露给外部使用
## 初始化
1、统一初始化，在initXXX()中初始化
2、getXXX初始化
## 共享
new ViewModelProvider(活动上下文).get(SharedViewModel.class);
活动上下文为同一个对象时，viewModel对象也是同一个

## 扩展
MediatorLiveData 一对多监听

