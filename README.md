ECMH

# 基本思路
ECMH整体思路是：先把集合里的元素映射成椭圆曲线上的点，然后利用椭圆曲线上的加法求解哈希值。该项目成功实现了集合上的哈希,生成椭圆曲线的公私钥对。


# 部分代码说明
# SM2_Pluspoint(P, Q, a, p)
返回值R = P+Q , P、Q为椭圆曲线上的两点 , 加法运算为定义在椭圆曲线上的加法







# SM2_Mulyipoint(k, P, a, p)
返回值R = k*P , P为椭圆曲线上的一点 , k为正整数






# SM2_Mod
模运算





# SM2__Mod_Decimal(n, d, b)
返回值x = n*d^{-1} mod b






# key_gen
SM2密钥对的生成







# Legendre
欧拉准则判断是否为二次剩余



#  Tonelli_Shanks
Tonelli-Shanks算法求二次剩余


![Uploading image.png…]()



# 生成公私钥对


![image](https://user-images.githubusercontent.com/75195549/181478309-e9060b0a-aca0-4b04-8039-24bc9daed8d7.png)



# 结果展示
为达到相同的安全性，ECMH算法需要的密钥长度远远小于哈希求和算法，因而ECMH相较哈希求和算法更为安全。


在ubuntu虚拟机中运行如下图所示：



![image](https://user-images.githubusercontent.com/75195549/180392780-ecf2fd9e-5482-487a-963d-9f44179284ad.png)




。
