# assign-3
# itertools.combinations()

from itertools import combinations
word , length  = input().split()
for i in range(1, int(length)+1):
    for j in combinations(sorted(word), i):
        print (''.join(j))

# itertools.product()

from itertools import product

input_A = list(map(int, input().split()))
input_B = list(map(int, input().split()))

print(*list(product(input_A, input_B)))

