# C/C++ 掌握后怎么转 Python

## 第一天

input 读取的是字符串，需要转换为整数或浮点数

比如 n = int(input())


输出浮点数保留一位小数

比如 print(f"{n:.1f}")


把一段字符串，按分隔符切成多个小段，存入列表

比如 s = input().split()


批量处理，在一行获得多个整数

比如 n, m = map(int, input().split())
> map() 是批量处理工具，可以将多个值转换为相同类型
> split() 是将字符串按分隔符切成多个小段，存入列表


/ 是浮点除法，结果一定是小数

// 是整除

% 是取余

绝对值 abs()

开根 引入 math 模块

import math

res = math.sqrt(9)

字符串反转

s = input().strip()

print(s[::-1])
> strip() 是去掉字符串首尾的空格(空格包含换行和回车)

平方 ** 2
> ** 是指数运算符，可以将一个数的指数设置为另一个数
> 比如 2 ** 3 等价于 2 * 2 * 2

获取一串数字的每一位相加之和
s = input().strip()
print(sum(map(int, s)))
> map() 是批量处理工具，可以将多个值转换为相同类型
> sum() 是求和函数，可以对一个可迭代对象求和

函数
python 中的函数不用()，直接调用即可，记得加:

           不用n--，而用n -= 1
           不用n++，而用n += 1

对应关系 && 换成 and
对应关系 || 换成 or
对应关系 ! 换成 not

函数写法
def 函数名(参数1, 参数2, ...):
    函数体
    return 返回值


值1 if 条件 else 值2

比如  print("yes" if is_leap_year(n) else "no")

