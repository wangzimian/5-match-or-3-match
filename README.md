# 比较在单局胜算高于0.5下，3局2胜，5局3胜，7局4胜等等，哪种更有利于选手的获胜
# 用户可以修改的地方：
# 1.
calculate_success(3)#3局2胜
calculate_success(5)#5局3胜
calculate_success(7)#7局4胜
calculate_success(9)#9局5胜
calculate_success(11)#11局6胜

这里可以增加，删减，修改。括号里的数字为总局数。
# 2.
p_range=list(np.linspace(0.5,1,6))#这里可以调整p的取值范围(0.5,1)，以及点数(6)

这里可以修改0.5，1，6这三个数字，用于决定单局胜率的遍历范围。0.5是最小值，1是最大值，6是范围内取的点的个数。
