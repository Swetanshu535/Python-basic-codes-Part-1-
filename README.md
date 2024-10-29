# Python-basic-codes-Part-1-


#exercrise 1 shopping cart program

item= input("Provide the name of the item: ")
Quantity= float(input("Provide the amount of the item: "))
Price= float(input("Provide the price of the item: "))

total= Price * Quantity

print(f"The total is {total}")


#exercrise 2 gym workouts

Exercise= input("Name of the exercise")
Reps= int(input("Number of reps: "))
Sets= int(input("Number of sets: "))
Total_time= (Reps * Sets)/365

print(f"the total time spent in the exercise every week {Total_time}")


#exercise 3 fast food order
Item= input("Name of the item: ")
Addon= int(input("Number of addon needed: "))
Accessories= int(input("Number of chili flakes needed: "))
Additional= int(input("Number of oregano needed: "))
Juice= int(input("number of juice needed: "))
Price= int(input("State the price displayed on the board for the item: "))


total= Price * Juice

print(f"Total price of the item is ${total}")



#exercise 4 library books analysis
book_name= input("Name of the book: ")
Book_quantity=int(input("Number of books taken: "))
Day_of_borrow= input("Write the day when the book was borrowed: ")
Rent= int(input("Enter the rent per book from your library card:" ))
day_count= int(input("Enter the number of days taken for the rent: "))
total= Book_quantity * Rent
print(f"the total rent for the taken books is {total}")
if total <day_count:
    print("Return the books within the given date ")
else:
    print("the return date will be refurbished")

