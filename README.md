
n = str(input("숫자를 입력하시오: "))
if n.isdecimal():
  n = int(n)
  if n <= 30:
    for i in range(1, n + 1):
      for j in range(1, i + 1):
        print(j,end="")
      print()
  else:
    print("너무 많습니다")
else:
  print("정수를 입력해 주세요")
