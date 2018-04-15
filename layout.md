# 布局
-----
### 1.线性布局(LinearLayout)

当用了**android:layout_weigth**后，width这个属性就会没用。
layout_gravity:对齐方式

### 2.相对布局(RelativeLayout)

layout_alignParentLeft
layout_alignParentTop
layout_alignParentRight
layout_alignParentBottom
layout_centerInParent
layout_above：相对控件
layout_toLeftOf:相对控件

### 3.帧布局(FrameLayout)
所有的控件都是默认在左上角的

### 4.百分比布局
线性布局已经支持按比例大小来布局，因此这个是针对帧布局和相对比句的补充，提供了PercentFrameLayout和PercentRelativeLayout
这个是新增的布局，需要添加support库
compile 'com.android.support:perent:24.2.1'
app:layout_widthPercent="50%"
app:layout_heightPercent="50%"


