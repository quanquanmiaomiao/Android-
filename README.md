# Android-
Android常用的一下过渡动画效果

# 怎么用？
res/anim目录下,考进去:

最简单用法:
startActivity后加:overridePendingTransition(R.anim.anim_in, R.anim.anim_out);
finish()后加:overridePendingTransition(R.anim.anim_in, R.anim.anim_out);

动画注释:
fade:
hold:
hyperspace_in:
hyperspace_out:  
my_alpha_action
my_scale_action
push_left_in
push_left_out
push_up_in
push_up_out
scale_rotate
scale_translate
scale_translate_rotate
slide_down_out
slide_left
slide_right
slide_up_in
wave_scale
zoom_enter
zoom_exit


对应效果：
淡入淡出效果
放大淡出效果
转动淡出效果1
转动淡出效果2
左上角展开淡出效果
压缩变小淡出效果
右往左推出效果
下往上推出效果
左右交错效果
放大淡出效果
缩小效果
上下交错效果



