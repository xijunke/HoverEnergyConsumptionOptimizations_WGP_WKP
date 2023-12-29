# Here,the optimal post-processed resuts are for fixed aerodynamic lift and drag coefficients (C_F) 

Notes: Aerodynamic lift and drag coefficients (C_F) do not vary with wing morphology parameters

# ˵��ע������

���ļ��еĳ���ı���WingM5_4_10parameters��20160106��֮ǰ�����ĵ�һЩ�������������Լ����ʵļ��������С����

Ŀǰ�ĳ����Ѿ��޸ģ�������ȷ

0.hybrid_GA_fminsearch_WingM4_4_2��hybrid_GA_fminsearch_WingM4_4_1�����޸Ķ���

1.���ļ�����Ϊ10����GA����Ż�֮����fmincon�������㷨

2.�������òѧ���˶�ѧ����(����Wang ZJ wingbeat pattern �˶�ѧ����)����10������

3.���ʵ��ú��������������ú���һ�����ͬһ������Aero_F_M_fruitfly��������ϼ��

4.����Լ�������С����ע�����ݵ��������޸ġ���ֱָƵ��Լ��f��[0,300];

5.kenimatics_wing_and_AoA_fruitfly_sim���(1000*9)����

## For the combined optimal wing shape parameters and kinematic parameters, aerodynamic force, inertial force, aerodynamic power, inertial power, wing pitch and flapping motion power, and total power output are listed here.

## Aerodynamic forces and inertia force
```
Aerodynamic force inbcludes normal force to wing plane, which are decomposed into aerodynamic lift and thrust again. And inertial force is also given out.
```

## Aerodynamic power and inertial power for pitch and flapping axis and total power output

# Figures for above mentioned aerodynamic force and power, inertial force and power, and wing pitch and flapping motion power, and total power output

## aerodynamic_forces_inertia_force_lift_and_thrust
![calculated results](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WGP_WKP/blob/main/WingM6_3_10parameters_fixed_C_F_2/force_moment_power_20160316/pic_png/aerodynamic_forces_inertia_force_lift_and_thrust.png)

## ����Ťת��x-axis����������
![calculated results](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WGP_WKP/blob/main/WingM6_3_10parameters_fixed_C_F_2/force_moment_power_20160316/pic_png/%E6%B2%BF%E7%9D%80%E6%89%AD%E8%BD%AC%E8%BD%B4x-axis%E7%9A%84%E6%B0%94%E5%8A%A8%E5%8A%9B%E7%9F%A9.png)

## �����Ĵ���z-axis����������
![calculated results](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WGP_WKP/blob/main/WingM6_3_10parameters_fixed_C_F_2/force_moment_power_20160316/pic_png/%E6%B2%BF%E7%9D%80%E6%8B%8D%E6%89%93%E8%BD%B4z-axis%E7%9A%84%E6%B0%94%E5%8A%A8%E5%8A%9B%E7%9F%A9.png)

## ����Ťת��x_{rw}-axis���������ʺ͹��Թ���
![calculated results](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WGP_WKP/blob/main/WingM6_3_10parameters_fixed_C_F_2/force_moment_power_20160316/pic_png/%E6%B2%BF%E7%9D%80%E6%89%AD%E8%BD%AC%E8%BD%B4x_%7Brw%7D-axis%E7%9A%84%E6%B0%94%E5%8A%A8%E5%8A%9F%E7%8E%87%E5%92%8C%E6%83%AF%E6%80%A7%E5%8A%9F%E7%8E%87.png)

## �����Ĵ���z_{rr}-axis���������ʺ͹��Թ���
![calculated results](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WGP_WKP/blob/main/WingM6_3_10parameters_fixed_C_F_2/force_moment_power_20160316/pic_png/%E6%B2%BF%E7%9D%80%E6%8B%8D%E6%89%93%E8%BD%B4z_%7Brr%7D-axis%E7%9A%84%E6%B0%94%E5%8A%A8%E5%8A%9F%E7%8E%87%E5%92%8C%E6%83%AF%E6%80%A7%E5%8A%9F%E7%8E%87.png)

## ����Ťת��x_{rw}-axis���Ĵ���z_{rr}-axis�Ĺ��Թ���
![calculated results](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WGP_WKP/blob/main/WingM6_3_10parameters_fixed_C_F_2/force_moment_power_20160316/pic_png/%E6%B2%BF%E7%9D%80%E6%89%AD%E8%BD%AC%E8%BD%B4x_%7Brw%7D-axis%E5%92%8C%E6%8B%8D%E6%89%93%E8%BD%B4z_%7Brr%7D-axis%E7%9A%84%E6%83%AF%E6%80%A7%E5%8A%9F%E7%8E%87.png)

## ������ų����ò�����ĳ�Ťת����_�Ĵ��ʺ��ܹ������
![calculated results](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WGP_WKP/blob/main/WingM6_3_10parameters_fixed_C_F_2/force_moment_power_20160316/pic_png/%E9%92%88%E5%AF%B9%E6%9C%80%E4%BC%98%E7%BF%85%E8%86%80%E5%BD%A2%E8%B2%8C%E5%8F%82%E6%95%B0%E7%9A%84%E7%BF%85%E6%89%AD%E8%BD%AC%E5%8A%9F%E7%8E%87_%E6%8B%8D%E6%89%93%E5%8A%9F%E7%8E%87%E5%92%8C%E6%80%BB%E5%8A%9F%E7%8E%87%E8%BE%93%E5%87%BA.png)