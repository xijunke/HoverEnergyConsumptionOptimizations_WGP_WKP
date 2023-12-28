# Here,the optimal post-processed resuts are for aerodynamic lift and drag coefficients (C_F) varying with wing morphology parameters 

# 说明注释区别

本文件夹的程序改编自WingM5_4_10variable_group，20160106日之前该论文的一些气动力和力矩以及功率的计算程序有小错误

目前改程序已经修改，几近正确

0.hybrid_GA_fminsearch_WingM4_4_2由hybrid_GA_fminsearch_WingM4_4_1进化修改而来
1.该文件夹下为10变量GA混合优化之程序—fmincon—搜索算法
2.含翅膀形貌学和运动学参数(采用Wang ZJ wingbeat pattern 运动学规律)共计10个变量
3.功率调用函数和气动力调用函数一起调用同一个函数Aero_F_M_fruitfly——程序较简洁
4.变量约束区间改小——注意数据的上下限修改——直指频率约束f∈[0,300];
5.kenimatics_wing_and_AoA_fruitfly_sim输出(1000*9)矩阵