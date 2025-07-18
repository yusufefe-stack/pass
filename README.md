
import random


chosen_password = str(random.randint(1, 10000))

print(f"(Debug) Oluşturulan şifre: {chosen_password}")  # Bu satırı test için ekledim, gerçek uygulamada kaldırabilirsin.


password = input("Enter your password: ")

if password == chosen_password:
    print("You can access your account now!.")
else:
