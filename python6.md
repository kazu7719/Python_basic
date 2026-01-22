## print関数
→pythonに用意された、ターミナルに値を出力する関数

name = "Taro"

# 画面に出力する
print(name)


## ターミナルの入力機能
→ input関数

# 入力機能が起動、入力された値が文字列として返る
name = input()

print(name)


## pythonの配列

変数　 = []

pencil_case = ["ペン", "消しゴム", "定規"]

print(pencil_case)


## 配列に値を追加する方法

配列名.append(追加する要素)

pencil_case = ["ペン", "消しゴム", "定規"]
pencil_case.append("えんぴつ")

print(pencil_case)

## 配列の値を習得する方法

配列名[添字]

pencil_case = ["ペン", "消しゴム", "定規"]
pencil_case.append("えんぴつ")

print(pencil_case)
print(pencil_case[1])


## 配列の値を変更する方法

配列名[添字] = 値

pencil_case = ["ペン", "消しゴム", "定規"]
pencil_case.append("えんぴつ")
pencil_case[1] = "修正ペン"

print(pencil_case)
print(pencil_case[1])

## 配列が持つ要素の数え方
→len関数を使う

pencil_case = ["ペン", "消しゴム", "定規"]
print(len(pencil_case))

pencil_case.append("えんぴつ")
pencil_case.append("付箋")
print(len(pencil_case))