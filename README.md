# Flow-sequence-or-Flow-chart-using-Repeat-While-and-Do-While-loops

# Name : DIVYA M
# Register Number : 212223040043
# Aim:

To design and implement workflows in UiPath using Repeat Number of Times, While, and Do While loops, in order to demonstrate different looping mechanisms that print counter values from 1 to 5. Repeat Number of Times → executes activities a fixed number of times. While Loop → executes activities repeatedly while a condition is true (pre-condition check). Do While Loop → executes activities at least once and then continues while the condition is true (post-condition check).

# Procedure:

# Repeat Number of Times:
Variables: counter (Int32, default = 1). Use Repeat Number of Times (NumberOfTimes = 5). Inside, add a Message Box → counter.ToString. Add Assign → counter = counter + 1. Shows 5 message boxes, values 1–5.
# Do While loop:

Create a Sequence. Variables: counter (Int32) default 1. Drag Do While into the Sequence. Inside the Do body add: Log Message counter.ToString() and an Assign counter = counter + 1. Set the Do While Condition to counter <= 5. Save and Run — body runs first, then condition checked; repeats while condition is true.

# While Loop:
Variable: counter (Int32, default = 1). Use While activity with condition: counter <= 5. Inside While: Message Box → counter.ToString Assign → counter = counter + 1 Shows 5 message boxes, values 1–5.

# OUTPUT :

# Repeat Number of Times:

<img width="1128" height="688" alt="487825066-0b88e859-0716-4932-8525-43fcca64c74e" src="https://github.com/user-attachments/assets/dc3292c4-2e46-418e-937f-25980bf3693b" />

# Do While loop:
<img width="1075" height="562" alt="487820259-c816b6e5-e038-4288-b47b-e4a677e5cd16" src="https://github.com/user-attachments/assets/633aae46-4f80-4510-857d-e9ee0f3df46c" />


# While Loop:
<img width="1192" height="594" alt="487827287-41fb03ff-fec9-4f2a-b512-5b1468fd6217" src="https://github.com/user-attachments/assets/52ad3723-77a8-435a-a206-9152d92f083d" />


# Result:

The workflows were successfully executed: Using Repeat Number of Times, the loop iterated exactly 5 times and displayed counter values from 1 to 5. Using While loop, the workflow checked the condition before each iteration and displayed counter values from 1 to 5. Using Do While loop, the workflow executed the body once before checking the condition and then displayed counter values from 1 to 5.
