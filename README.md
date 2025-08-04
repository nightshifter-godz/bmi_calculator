# bmi_calculator
just tried python basics, this is simply used to calculate a person's bmi

# BMI calcu details
# You have to provide details first, as you can see below I came up with my own example for names, height, and weight

name1 = "ALYGANDA"
height_m1 = 3
weight_kg1 = 40

name2 = "Jhocey"
height_m2 = 6
weight_kg2 = 78

name3 = "Mikhaiah"
height_m3 = 8
weight_kg3 = 87

# here is the formula/code

def bmi_calculator(name, height_m, weight_kg):
    bmi = weight_kg / (height_m ** 2)
    print(f"{name}'s BMI is: ")
    print(bmi)
    if bmi < 18.5:
        return name + " is overweight"
    else:
        return name + " is underweight"

result1 = bmi_calculator(name1, height_m1, weight_kg1)
result2 = bmi_calculator(name2, height_m2, weight_kg2)
result3 = bmi_calculator(name3, height_m3, weight_kg3)

# then just try and print it, after doing all the codes

print(result1)
print(result2)
print(result3)
