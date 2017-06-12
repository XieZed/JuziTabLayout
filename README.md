# JuziTabLayout
自定义的谷歌原生TabLayout, 主要是解决谷歌的tablayout 的 indicator太宽, 不能符合ui设计的问题

照搬谷歌的源码, 然后对tabview进行了小幅改动, 以控制indicator的宽度, 原本indicate的宽度是用的tabview的left和right, 
改为了用tabview中的textview的left和right

顺便添加了一个tabview之间的分隔线, 用的是LinearLayout的divider属性
