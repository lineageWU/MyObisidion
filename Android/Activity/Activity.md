# Activity
## AndroidManifest.xml 项目配置文件
代表项目启动页的代码块
<intent-filter>  
 <action android:name="android.intent.action.MAIN" />  
 <category android:name="android.intent.category.LAUNCHER" />  
</intent-filter>

# Fragment
## 动态添加
FragmentManager fragmentManager = getSupportFragmentManager();
        FragmentTransaction fragmentTransaction = fragmentManager.beginTransaction();
        fragmentTransaction.replace(R.id.fl,fragment);
        fragmentTransaction.commit();
