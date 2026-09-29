import random

print("===== NUMBER GUESSING GAME =====")
print("1. Easy")
print("2. Medium")
print("3. Hard")

choice = int(input("Choose your difficulty: "))

if choice == 1:
    maximum = 50
    max_attempts = 10
    level = "Easy"

elif choice == 2:
    maximum = 100
    max_attempts = 10
    level = "Medium"

elif choice == 3:
    maximum = 1000
    max_attempts = 10
    level = "Hard"

else:
    print("Invalid choice!")
    exit()

secret_number = random.randint(1, maximum)
attempts = 0

print("\nDifficulty:", level)
print("Guess a number between 1 and", maximum)
print("You have", max_attempts, "attempts.")

while attempts < max_attempts:
    guess = int(input("\nEnter your guess: "))
    attempts += 1

    if guess < secret_number:
        print("Too Low! ⬇️")

    elif guess > secret_number:
        print("Too High! ⬆️")

    else:
        print("\n🎉 Congratulations!")
        print("You guessed the correct number!")
        print("Attempts used:", attempts)
        break

else:
    print("\n❌ Game Over!")
    print("The correct number was:", secret_number)