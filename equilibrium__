lst = list(map(int, input().split()))
def find_equilibrium(lst):
    for i in range(1, len(lst)):
        lst[i] = lst[i - 1] + lst[i]
    c = 0
    for i in range(1, len(lst)):
        if lst[i - 1] == lst[len(lst) - 1] - lst[i]:
             return i
    return -1
print(find_equilibrium([-7, 1, 5, 2, -4, 3, 0]))
print(find_equilibrium([1, 2, 3]))
print(find_equilibrium(lst))
