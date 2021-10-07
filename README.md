*Napisz program, który wczyta liczby a, b oraz n, następnie n liczb i wypisz największą parzystą z wczytanych liczbę, która jednocześnie jest większa od a oraz mniejsza od b.*

a = int(input())
b = int(input())
n = int(input())
max = 0
while n > 0:
    x = int(input())
    if x > max and x > a and x < b and x % 2 == 0:
        max = x
    n-=1

if max == 0:
    exit()
print(max)
