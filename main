print("Solve: SLAYER + SLAYER + SLAYER = LAYERS")
guess = int(input("What is your guess? "))


S = (guess // 100000) % 10
L = (guess // 10000) % 10 
A = (guess // 1000) % 10
Y = (guess // 100) % 10
E = (guess // 10) % 10
R = guess % 10

slayer = guess * 3
layers = (L * 100000) + (A * 10000) + (Y * 1000) + (E * 100) + (R * 10) + (S * 1)
# layers = int(str(L) + str(A) + str(Y) + str(E) + str(R) + str(S))
result = (slayer == layers)

print(layers, "==", slayer, "->", result)
