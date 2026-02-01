import random

def generate_otp(length=6):
    otp = ""
    for _ in range(length):
        otp += str(random.randint(0, 9))
    return otp

print(" OTP Generator")

otp = generate_otp()
print("Your OTP is:", otp)
