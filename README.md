# 使用
下载源码直接copy自定义View文件即可
# 演示

![演示gif](https://github.com/superSp/RulerView/blob/master/RulerViewGif.gif)

![演示gif2](https://github.com/superSp/RulerView/blob/master/RulerViewGif2.gif)


# 支持设置的属性
````
<attr name="scaleCount" format="integer" />                  <!--相邻2个大刻度之间小刻度的数目-->
<attr name="scaleLimit" format="integer" />                  <!--相邻2个大刻度之间的差值默认为1-->
<attr name="rulerHeight" format="dimension" />               <!--尺子的高度-->
<attr name="rulerToResultgap" format="dimension" />          <!--尺子距离结果的高度-->
<attr name="scaleGap" format="dimension" />                  <!--刻度间距-->
<attr name="firstScale" format="float" />                    <!--默认选中的刻度-->
<attr name="maxScale" format="integer" />                    <!--最大刻度-->
<attr name="minScale" format="integer" />                    <!--最小刻度-->
<attr name="bgColor" format="color" />                       <!--背景色-->
<attr name="smallScaleColor" format="color" />               <!--小刻度的颜色-->
<attr name="midScaleColor" format="color" />                 <!--中刻度的颜色-->
<attr name="largeScaleColor" format="color" />               <!--大刻度的颜色-->
<attr name="scaleNumColor" format="color" />                 <!--刻度数的颜色-->
<attr name="resultNumColor" format="color" />                <!--结果字体的颜色-->
<attr name="unit" format="string" />                         <!--单位-->
<attr name="unitColor" format="color" />                     <!--单位颜色-->
<attr name="smallScaleStroke" format="dimension" />          <!--小刻度的宽度-->
<attr name="midScaleStroke" format="dimension" />            <!--中刻度的宽度-->
<attr name="largeScaleStroke" format="dimension" />          <!--大刻度的宽度-->
<attr name="resultNumTextSize" format="dimension" />         <!--结果字体大小-->
<attr name="scaleNumTextSize" format="dimension" />          <!--刻度字体大小-->
<attr name="unitTextSize" format="dimension" />              <!--单位字体大小-->
<attr name="showScaleResult" format="boolean" />             <!--是否显示结果值-->
<attr name="isBgRoundRect" format="boolean" />               <!--背景是否圆角-->
````
