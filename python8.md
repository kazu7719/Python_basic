## 繰り返し処理(for文)

for 変数 in 配列:
    (実行する処理)

colors = ["あか", "あお", "きいろ"]

for color in colors:
    print(f"色:{color}")

## forとrange関数

for 変数 in range(繰り返したい回数):
    (実行する処理)

for i in range(10):
    print(i + 1)

## 関数の定義

def関数名():
    # 実行する処理(処理の前にはインデントが必要)

def say_hello():
    print("Hello World")

say_hello()


## 戻り値(return文)

def sample():
    num = 2 * 3
    return num

print(sample())


## 値が使える範囲について
グローバルスコープ
→関数の外側で定義した変数
→範囲はファイル内全体
→グローバルスコープ内で定義した変数はグローバル変数と呼ぶ
→グローバル変数が使える範囲はグローバルスコープ内とローカルスコープ内

ローカルスコープ
→関数の内側で定義した変数
→範囲はそれぞれの関数内
→ローカルスコープ内で定義した変数はローカル変数と呼ぶ
→ローカル変数が使える範囲はローカル変数を定義した関数内のみ


## 引数について

def 関数名(仮引数):
    (処理)

関数名(実引数)

def square(number):
    print(number * number)

square(3)


→for文では外で定義した変数は中で使用でき、中で定義した変数は外でも使用できる