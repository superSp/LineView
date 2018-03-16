# LineView
一个简易的可以，可以随自己意愿修改的LineView

![演示jpg](https://github.com/superSp/LineView/blob/master/lineview.png)
##### 使用比较简单
先去这里把View源码下载下来放入到自己的view目录
在布局中添加:（`com.sp.view.LineView`根据自己放代码的位置修改）
````
<com.sp.view.LineView
        android:id="@+id/lineView"
        android:layout_width="match_parent"
        android:layout_height="350px" />
````
使用:
````
((LineView) headView.findViewById(R.id.lineView)).setData(
                        Arrays.asList("02-1","02-1","02-1","02-1","02-1","02-1","02-1"),
                        Arrays.asList(1.0f,2.0f,3.0f,4.0f,5.0f,6.0f,7.0f));
````
##### 可以自己修改的自定义属性
````
    /**
     * 底部间隙大小
     */
    private float bootomDes = 10;
    /**
     * 左边间隙大小
     */
    private float leftDes = 10;
    /**
     * 纵坐标固定值分为几个间隔 默认6个
     */
    private int yGapSize = 6;
    /**
     * 背景色
     */
    private int bgColor = 0x66000000;
    /**
     * 刻度值字体大小
     */
    private int scaleTxtSize = 13;
    /**
     * 刻度字体颜色
     */
    private int scaleTxtColor = 0xffffffff;
    /**
     * 折线颜色
     */
    private int lineColor = 0xff2791dc;
    /**
     * 折线粗细层度
     */
    private int lindWidth = 2;
````
# 实现思路以及流程
[我的简书地址](https://www.jianshu.com/p/6458a5cf71c8)
