n=int(input())
l=list(map(int,input().split()))
res = []
for idx, ele in enumerate(l):
    if ele % 2 != 0:
        res.append(idx)
print(str(res))
