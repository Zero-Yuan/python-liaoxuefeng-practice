# python-liaoxuefeng-practice
1) 函数
def product(*x):
    if len(x) < 1:
        print('cuowu')
    else:
        sum = 1
        for i in range(len(x)):
            sum = sum * x[i]
        return sum
