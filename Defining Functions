#Logan Spencer 
#In this code there are 8 separte functions provided. Each one prints different types of information and demonstrates a variety of coding principles within python. When run, each function runs properly and prints out the correct information depending on the function. The last function, the user is required to input certain inforamtion.  

#First function: a welcom message that takes a name as the argument and prints a phrase out using the parameters.
def welcome_message(name):
    print(f"Welcom to IS 303 {name}!")
welcome_message("Diego")
welcome_message("Mai")

#Second Function: Takes the parameters and adds them together.
def sum_two_numbers(num1, num2):
    myValue = num1 + num2
    return myValue
print(sum_two_numbers(5,7))
print(sum_two_numbers(1000.5, -30))

#Third Function: Takes a number as the parameter and by using an if statement, tells the user if the number is even or odd.
def even(num):
    if num %2 == 0:
        print("The number you provided is even.")
        return True
    else:
        print("The number you provided is odd.")
        return False
        
even(7)
    
#Fourth Function: Takes a temperature in fahrenheit and within the function, calculates how to convert the degrees to celcius and then returns it.
def fahrenheit_to_celcius(fahrenheit):
    celcius = (fahrenheit - 32) * (5/9)
    return celcius
print(fahrenheit_to_celcius(32))
print(fahrenheit_to_celcius(75))


#Fifth Function: Takes a list of numbers given and returns the minimum, maximum, and mean of the refered to list of numbers. This is done by importing a library called statistics in order to calculate the mean. The mean was also made into a float.
import statistics
numbers_list_1 = [20,45,23,2,87,3]
numbers_list_2 = [1,3,5,7]
def min_max_mean(numbers_list):
    min1 = min(numbers_list)
    max1 = max(numbers_list)
    mean1 = float(statistics.mean(numbers_list))

    return max1, min1, mean1
print(min_max_mean(numbers_list_1))
print(min_max_mean(numbers_list_2))


#Sixth Function: A dog name and it's age are taken as parameters and printed out into a specified sentence. If the age is not specified in the parameters, then it automatically programs to be 0 years old.
def dog_message(name, age = 0):
    print(f"I am a dog named {name} and I'm {age} years old!")
dog_message("Spot", 7)
dog_message("Peppy")

#Seventh Function: An age and a reference age are set as the parameters. Using an if statement, if an individual is a certain age, then the code will print whether they are a minor, adult, or senior. If the age of seniors is not given, then it automatically sets to 65.
def classify_age(age, senior_age = 65):
    if age < 18:
        print("Minor")
    elif age < senior_age:
        print("Adult")
    elif age >= senior_age:
        print("Senior")
    else: 
        return 0 
classify_age(60, 55)
classify_age(62)

#Eighth Function: This function takes the input from the user of how much a product cost, the quantity of it, and the discount percent of the product and prints out the customer's total for the product. By using an if statement, the code is able to calculate what the discount applied would be along with the net price. By using a for loop, the three inputs are able to repeat themselves for three different customers.
def calculate_total(price, quantity, fDiscount_percent, threshold_total = 100, fBonus_discount = .02):
    tPrice = price * quantity
    if tPrice <= threshold_total:
        discount_applied = fDiscount_percent *tPrice
    else: 
        discount_applied = (fDiscount_percent + fBonus_discount) * tPrice
    netPrice = tPrice - discount_applied
    return netPrice


for customerNum in range (1, 4):
    customerPrice = input(f"Enter a price for the product purchased by customer {customerNum}: ")
    customerQuantity = input(f"Enter the number of the product purchased by customer {customerNum}: ")
    customerDiscount = input(f"Enter the discount percent for customer {customerNum} (formatted as a decimal): ")
    total = calculate_total(int(customerPrice), int(customerQuantity), float(customerDiscount))
    print(f"Customer {customerNum}'s total is: ${total:.2f}")







