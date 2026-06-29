#claude让做的小练习 
#1.成绩统计 
scores = [88, 92, 75, 63, 95, 81, 70, 55, 98, 84]
sum = 0
max = 0

min = 100
suff = 0
for i in scores:
    sum += i
    if i > max:
        max = i
    if i < min:
        min = i
    if i >= 60:
        suff += 1
avr = sum/len(scores)
print(f"平均分为{avr},最高分为{max},最低分为{min},及格人数为{suff}")

#2.单词计数
text = input('请输入一段英文')
corres = {}
i = 0
while i < 26:
    letter = chr(ord('a')+i)
    corres[letter] = 0
    for j in text:
        if j == letter:
            corres[letter] += 1
    i += 1
print(corres)
            
#3.简单函数
def is_prime(n):
    i = 2
    while i <= n:
        if n % i == 0 and i != n:
            print(f"{n}不是质数")
            break
        i += 1
    if i == n + 1:
        print(f"{n}是质数")
    prime = []
    for j in range(2,101):        
        i = 2
        while i <= j:
            if j % i == 0 and i != j:
                break
            i += 1
        if i == j + 1:
            prime.append(j)
    print(prime)
is_prime(int(input('请输入一个整数')))
