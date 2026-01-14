import random

secret = random.randint(1, 100)
max_guesses = 5
guesses = 0

print("🎮 Welcome to the Guessing Game!")
print("I'm thinking of a number between 1 and 100.")
print(f"You have {max_guesses} tries.\n")

while guesses < max_guesses:
    user_input = input("Enter your guess: ")

    if not user_input.isdigit():
        print("⚠️ Please enter a valid number.\n")
        continue

    guess = int(user_input)
    guesses += 1

    if guess == secret:
        print(f"\n🎉 Correct! You guessed the number in {guesses} tries.")
        break
    elif guess < secret:
        print("⬇️ Too low!\n")
    else:
        print("⬆️ Too high!\n")

if guess != secret:
    print(f"❌ Game over! The number was {secret}.")
