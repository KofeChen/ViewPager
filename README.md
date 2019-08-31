# ViewPager

### 无限循环轮播组件
- 1.jpg
- 2.jpg
- 3.jpg
- 4.jpg
- ViewPager.html
- 思路图

### 思路：
先把最后一张和第一张 clone 出来，分别放到第一张前面和最后一张后面，当第一张图片想要看到末尾滚动过来的图片时直接进行滚动可以看到 clone 的最后一张图片，此时在滚动完成之后立刻把原来的最后一张图片调整到展示窗口位置，因为是同一张图片用户看不出变化过程。同样最后一张图片往前滚动的原理相同，当用户在最后一张图片想向后看时直接进行滚动看到了 clone 的第一张图片，此时再把原来的第一张图片调整到展示窗口位置。
