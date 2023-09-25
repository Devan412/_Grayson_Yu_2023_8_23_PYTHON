import random

min = 1
max = 5
count = 0
target = random.randint(min,max)
print("==============猜數字遊戲==================\n")

while(True):
    try:
        keyin = int(input(f"猜數字範圍:{min}~{max}:"))
    except:
        print("輸入格式錯誤")
        count += 1
        print(f"您已經猜了{count}次")
    else:
        count += 1
        if(keyin >= min and keyin <= max):
            if keyin == target:
                print(f"賓果!猜對了, 答案是:",target)
                print(f"您總共猜了{count}次")
                break
            else:
                print("猜錯了")
                print(f"您已經猜了{count}次")
        else:
            print("輸入錯誤,超出範圍")
            print(f"您已經猜了{count}次")

print("遊戲結束")