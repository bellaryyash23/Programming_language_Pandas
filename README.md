# Popularity of Different Programming Languages over Time using Pandas, Matplotlib of Python

🌟The oldest programming language still in use today is FORTRAN, which was developed in 1957. Since then many other programming languages have been developed. But which programming language is the most popular?

🌟StackOverflow will help us answer this burning question. Each post on Stack OverFlow comes with a Tag. And this Tag can be the name of a programming language.
To figure out which language is the most popular, all we need to do is count the number of posts on Stack Overflow that are tagged with each language. The language with the most posts wins!

🌟We have used this data to do follow tasks:

👉Visualise your data and create charts with Matplotlib.

👉Pivot, group and manipulate your data with Pandas to get it into the format you want.

👉Work with timestamps and time-series data

👉Style and customise a line chart to your liking.

🌟All this done and we have used the following methods to achieve these data analysis:

✅Used .groupby() to explore the number of posts and entries per programming language

✅Converted strings to Datetime objects with to_datetime() for easier plotting

✅Reshaped our DataFrame by converting categories to columns using .pivot()

✅Used .count() and isna().values.any() to look for NaN values in our DataFrame, which we then replaced using .fillna()

✅Created (multiple) line charts using .plot() with a for-loop

✅Styled charts by changing the size, the labels, and the upper and lower bounds of our axis.

✅Added a legend to tell apart which line is which by colour

✅Smoothed out our time-series observations with .rolling().mean() and plotted them to better identify trends over time.

🌟Here's a sample of the final Notebook after performing all these actions:

![Programming_Languages](https://user-images.githubusercontent.com/88725274/192222147-825be628-9682-41e2-a442-c02a26d5a93b.jpg)

👆Programming Language Notebook Sample👆
