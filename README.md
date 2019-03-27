# statusbarutils
沉浸式状态栏工具类

依赖:
工作空间下build.gradle设置:  
  allprojects {  
    repositories {
        //... 省略其他

        maven {
            url 'https://raw.githubusercontent.com/wankai313/statusbarutils/master'
        }
    }
}
项目下:  
  dependencies {  

  //... 省略其他  
  implementation 'com.wankai.libaray_statusbar_utils_w:statusbarutils:1.0.0'
  
}  
  StatusBarUtil.initStatusBar(Activity context, boolean isDark);
设置状态栏字体颜色

  StatusBarUtil.initViewPaddingTop(final Activity context, final View view);
设置需要改变的view的size
