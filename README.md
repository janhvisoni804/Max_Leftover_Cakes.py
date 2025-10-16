T = int(input("Enter number of test cases: "))
for i in range(1, T + 1):
    N = int(input("Test case " + str(i) + "\nEnter number of lemon cakes: "))
    best_A = N // 2 + 1
    leftover = N % best_A
    print("\nSophie should choose package size", best_A, "to maximize leftovers.\n")
    print("She will get to eat", leftover, "leftover lemon cakes.")
