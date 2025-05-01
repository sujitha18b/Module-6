# Exp.No:6B
## COUNTER CLASS


### AIM  
To write a Python program to create a `Counter` class that can increment the value of a counter.



### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**



### PROGRAM

class Counter: <br />
    def __init__(self): <br />
        self.current = 0 <br />

   def increment(self):  <br />
        self.current += 1  <br />

   def value(self):  <br />
        return self.current  <br />

   def reset(self): <br />
        self.current = 0 <br />

counter = Counter() <br />
counter.increment() <br />
counter.increment() <br />
counter.increment() <br />

print(counter.value())

### OUTPUT

![Screenshot 2025-05-01 130015](https://github.com/user-attachments/assets/4785711c-5321-4e9a-bab5-407801246eb3)

### RESULT
Thus, the given python program is implemented and executed sucessfully.
