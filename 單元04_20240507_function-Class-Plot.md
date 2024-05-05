# Function? Class? plot?

> 在寫程式碼時有一個非常重要的觀念是DRY(Don’t Repeat Yourself)，意思是避免同樣的程式碼重複出現在很多個地方，除了可讀性很低外，也不易維護。所以要適當的進行封裝，來達到程式碼的重用性(Reusable)。
> 今天的重點就是要來教大家如何建構自己的 Python函式(Function)，就是能夠讓你的程式碼被重複的使用(Reusable)，並且提高維護性及可讀性!!

## 1. Function, List, For Loop

![image](https://github.com/Grace-TA/Python2024/assets/89304181/32e2ded7-5853-4537-84f0-87eb3c439630)

## 2. Function with Default Value

![image](https://github.com/Grace-TA/Python2024/assets/89304181/37730aca-06d3-4f78-b0e3-22315af3f5dc)



## 5. Class? class類別，就是像一個模組，可以產出具有相似特性的實體(物件) 也有人會說他像是一個蛋糕模子，可以一直套用 生產蛋糕

![image](https://github.com/Grace-TA/Python2024/assets/89304181/d847caef-615c-4241-a34f-607cb722abb9)


## 6. 如何作圖(plot)?

### a. 計算正弦曲線上點的 x 和 y 座標

![image](https://github.com/Grace-TA/Python2024/assets/89304181/8024b50a-7677-43c1-8a2f-14ae51486b50)

### b. 只需一點額外的工作，我們就可以輕鬆地一次繪製多條線，並添加標題、圖例和軸標籤

![image](https://github.com/Grace-TA/Python2024/assets/89304181/c224263a-ce19-4dd4-8da1-9a6a82fd7dce)

### c. 繪製多子圖，並添加標題、圖例和軸標籤

![image](https://github.com/Grace-TA/Python2024/assets/89304181/6bec553f-0afc-4c40-94f6-cfd413494e95)

### d. 繪製2X2子圖，並添加標題、圖例和軸標籤

![image](https://github.com/Grace-TA/Python2024/assets/89304181/e640e4f6-e5e8-4e1b-9a8b-52bdaf65c910)


## Your Show Time: Challenge 1

![image](https://github.com/Grace-TA/Python2024/assets/89304181/b5684d50-c5b6-47ff-9256-c6f5e0fd41ca)

## Your Show Time: Challenge 2

```python
## ## Challenge 2:
sID = '109065804'
import random

def Sum(x,y):
  print('x+y = ', x+y) # 加法

def Delta(x,y):  
  print('x-y = ', x-y) # 減法

def MM(x,y):  
  print('x*y = ', x*y) # 乘法

def DD(x,y):  
  print('x/y = ', x/y) # 除法

def Calc(ss, xx, yy):
  print('x=%d, y=%d, ss=%d; thus, ' % (xx, yy, ss),end="")

  if ss == 1: # 加法
    Sum(xx,yy)

  elif ss == 2: # 減法
    Delta(xx,yy) 

  elif ss == 3: # 乘法
    MM(xx,yy)

  elif ss == 4: # 除法
    DD(xx,yy)  

  else:
    print('ss = %d, Do nothing!' % ss)

# Main Program
for i in range(1,10):
  xx = random.randint(1, 10) # Generate an integer number the range between 1 and 10
  yy = random.randint(1, 10)

  # Your Program with One Line!

today = datetime.now()
print('*** %s! Done by %s at ' % ('Good Job',sID),today)

```
### Output Result
![image](https://github.com/Grace-TA/Python2024/assets/89304181/88c32994-a83e-4c28-acb4-4274d8354b0f)


## Your Show Time: Challenge 3: 如何用 matplotlib 繪製一個圓？

![image](https://github.com/Grace-TA/Python2024/assets/89304181/5c239deb-eb9b-436e-a814-e8a6480ebb34)



