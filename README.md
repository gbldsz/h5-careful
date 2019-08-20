[ghtoc]
# h5-careful
汇聚h5应用坑点，减少踩坑。

# 尽量不要用整屏弹框
~~~txt
因为ios有右滑手势，这个手势不会触发路由变化。
你弹框之后，右滑界面，会导致直接返回上一页，但是用户会觉得应该返回弹框出来之前的页面
下面是流程
a->b->(b弹框)->右滑->a
事实上，用户想返回b；
~~~
