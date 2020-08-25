## define what runtime complexity is
- How efficient the code is

### 0(1)
def print_one_item(items):
    print(items[0])

### 0(n)
def print_every_item(items):
    for item in items:
        print(item)

### 0(n^2)
def print_pairs(items):
    for item_one in items:
        for item_two in items:
            print(item_one, item_two)




def count_ones(a_list): # 0(n)
    total = 0 # 0(1)
    for element in a_list: # 0(n)
        if element == 1: # 0
            total += 1
    return total