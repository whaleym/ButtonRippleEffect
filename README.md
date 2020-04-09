# ButtonRippleEffect
**涟漪效果按钮实现**
'''
通过css动画配合js点击事件，实现点击按钮的涟漪效果
具体做法如下：
给按钮添加点击事件，在按钮元素节点下动态添加'<span>'元素
利用css修改span元素形状为圆形，并添加动画，宽高从（0，0）放大到 （500，500），不透明度从 0.5 变化为 0.
在js中设置定时器，1s后将<span>元素移除
'''
