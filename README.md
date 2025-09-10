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

<img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/5d7c7cd9-42d5-4af8-ab07-d12976281ae6" />

# Do While loop:

<img width="1920" height="1080" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/932b9009-29f1-4940-aea3-ea7c0a845b32" />

# While Loop:

<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/bcfe3e69-fc2d-44b4-a08a-14d643407ee6" />

# Result:

The workflows were successfully executed: Using Repeat Number of Times, the loop iterated exactly 5 times and displayed counter values from 1 to 5. Using While loop, the workflow checked the condition before each iteration and displayed counter values from 1 to 5. Using Do While loop, the workflow executed the body once before checking the condition and then displayed counter values from 1 to 5.
