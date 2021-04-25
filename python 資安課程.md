# 課堂活動紀錄

## true , false
![](註解%202021-04-25%20141921.png)

### Python try  , 異常處理
![](https://github.com/hank710535/python20210425/blob/main/%E8%A8%BB%E8%A7%A3%202021-04-25%20141921try.png?raw=true)

#### 迴圈與終止
![](https://github.com/hank710535/python20210425/blob/main/%E8%A8%BB%E8%A7%A3%202021-04-25%20141921while.png?raw=true)

###### 函式定義
```
def my_function():
    print("Hello From My Function!")

def sum_two_numbers(a, b):
    return a + b
```
#######  範圍
![](https://github.com/hank710535/HappyPythonDay/blob/main/%E8%A8%BB%E8%A7%A3%202021-04-25%20141921range.png?raw=true)

########   16進制轉字母
![](https://github.com/hank710535/HappyPythonDay/blob/main/%E8%A8%BB%E8%A7%A3%202021-04-25%20141921%E9%80%B2%E5%88%B6.png?raw=true)

########## 函式
```
def sum(i1, i2):
    result = 0
    for i in range(i1, i2):
        result += i
    return result

def main():
    print("Sum from 1 to 10 is", sum(1, 11)) 
    print("Sum from 20 to 37 is", sum(20, 38))
    print("Sum from 35 to 49 is", sum(35, 50))

main()
```
########### 變數的有效範圍
```
x = 111

def f1():
    x = 222
    print(x) 

f1()
print(x)

x = 1

def increase():
    global x
    x =  x + 1
    print(x) 

increase()
print(x)
increase()
increase()
print(x)
```
############# 在pwn開python script
![](https://github.com/hank710535/HappyPythonDay/blob/main/%E8%A8%BB%E8%A7%A3%202021-04-25%20141921%E9%96%8Bscript2.png?raw=true)
############## 解題紀錄
![](https://github.com/hank710535/HappyPythonDay/blob/main/%E8%A8%BB%E8%A7%A3%202021-04-25%20141921score.png?raw=true)
![](https://github.com/hank710535/HappyPythonDay/blob/main/%E8%A8%BB%E8%A7%A3%202021-04-25%20141921score2.png?raw=true)

