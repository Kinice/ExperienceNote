#做移动端适配的一些坑
1. 在移动端使用css动画会导致绝大部分手机卡顿，直到iPhone5s也会出现。
2. javascript原生手势操作，在遇到移动端浏览器屏幕随触摸移动时会被覆盖，无效果。
3. screen.width与screen.height是设备屏幕的宽高，与是否横屏无关。大部分情况下，screen.height大于screen.width即可判定是移动端。
4. 一般设备的长宽比为16：10或16：9 
