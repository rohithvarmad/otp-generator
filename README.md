# otp-generator
# python program to generate 
# an OTP from the squares of the 
# odd digits 
def otp(numbers):
    length=len(numbers)
    otp=""
    for odd in range(1,length,2):
        otp+=str(int(numbers[odd])**2)
    print(otp[0:4])
numbers="123456"
otp(numbers)
