# Exp.No:26  
## Method Overriding

---

### AIM  
To write a Python program to create a Parent class `Bird` and inherit two child classes `Sparrow` and `Ostrich` from the `Bird` class with the same method `flight()`. Create an object for each class and call the methods of the class which will print the name of the bird that is flying.

---

### ALGORITHM

1. **Begin the program.**
2. **Define the Bird class**:
   - Create a method `intro()` to print "There are many types of birds."
   - Create a method `flight()` to print "Most of the birds can fly but some cannot."
3. **Define the Sparrow class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Sparrows can fly."
4. **Define the Ostrich class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Ostriches cannot fly."
5. **Create an object `obj_bird`** of the `Bird` class.
6. **Create an object `obj_spr`** of the `Sparrow` class.
7. **Create an object `obj_ost`** of the `Ostrich` class.
8. **Print the general message** "There are many types of birds."
9. **Call the `flight()` method** on each object (`obj_bird`, `obj_spr`, `obj_ost`) to display the respective messages.
10. **Terminate the program.**

---

### PROGRAM

```

# Reg.No: 212223060057
# Name: DINESH KUMAR A

class India():
	def capital(self):
		print("New Delhi is the capital of India.")
	def language(self):
		print("Hindi is the most widely spoken language of India.")
	def type(self):
		print("India is a developing country.")
class USA():
	def capital(self):
		print("Washington, D.C. is the capital of USA.")
	def language(self):
		print("English is the primary language of USA.")
	def type(self):
		print("USA is a developed country.")
obj_ind = India()
obj_usa = USA()
for country in (obj_ind, obj_usa):
    country.capital()
    country.language()
    country.type()
```

### OUTPUT
<img width="1137" height="282" alt="image" src="https://github.com/user-attachments/assets/bd9ee197-55bb-49d3-b544-7aee7ff923ac" />


### RESULT
Thus, the Python program to demonstrate Method Overriding using inheritance has been successfully executed.

