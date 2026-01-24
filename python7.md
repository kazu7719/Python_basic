## 辞書の生成方法
変数 = { キー1 : バリュー1, キー2 : バリュー2, キー3 : バリュー3 }

student = {"name":  "John", "age": 10 }
teacher = {"name": "Mike", "age": 25 }

print(student)
print(teacher)

## 辞書の値追加方法
辞書名[追加するキー] = 値

teacher["subject"] = "English"

## 辞書の値の取得方法
辞書名[取得したい値のキー]

print(teacher["name"])

## 辞書の値の変更方法
辞書名[変更したい値のキー]　= 値

teacher["name"] = "Emma"


## if文

if 条件式:
    処理
→条件式の後に:を入れる
→処理の前にインデントを半角スペース4つ分入れる

value = 3

if value > 0:
    print("値は性です")

## else(if文)

if 条件式:
    (条件式が真のときに実行する処理)
else:
    (条件式が偽のときに実行する処理)


value = -1

if value > 0:
    print("値は正です")
else:
    print("値は負です")

## elif(if文)

if 条件式1:
    (条件式1が真のときに行う処理)
elif 条件式2:
    (条件式1が偽のとき、かつ条件式2が真のときに実行する処理)
else:
    (条件式1と条件式2がどちらも偽のときに実行する処理)


value =int(input())

if value > 0:
    print("値は正です")
elif value < 0:
    print("値は負です")
else:
    print("値は0です")

  



