# Personal-Projects
Hi everyone! This is where I will be posting personal projects for me in order to get better at Python. 
I will be working on as much projects as I can with as little help as possible!

# Change Return Program 1/30/2020

For my first personal project, I created a change return program that asks you the cost of the item, 
the amount of money given and then calcuates the difference!(Amount of change needed). I was able to solve about half of this
project on my own with exception of googling certain terms to familiarize myself.

What I got stuck on was trying to figure out how to use my type_money dictionary to show how many Dollars, Dimes, etc. to
give out. I attempted to use a for loop while iterating through the dictionary, but that didn't work out as I was using
floaters as oppose to integars.

I eventually caved in and seeked out help using my good friend pythontutor.com. The user that joined my session was able to
explain that I can use a while loop with if statements to count down to my "change" value to 0, using my dictionary. This code
is showed in between the #### signs. The user also multiplied "money" and "cost" by 100, so that I'm working with integars.
Then switched back to floater value by dividing back by 100. By multipying money and cost by 100, it made my code much more 
easier to handle than when I was trying to write out the code using floater values.

Despite seeking out help halfway through the project, I am happy that I was able to semi complete this project on my own.
Hopefully my future projects won't require as much help!


# NYC Population Analysis 3/14/2020

For my second project, I will be using the pandas library to analyze and create vizualizations for the nyc metro population area from 2000 - 2020. I used the Pandas and Python Quick Refernce Udemy course and the internet as a guide for this project.

I found a csv file from the nyc website containing population data of each borough from 2020. I uploaded this csv file into python and displayed the table. Then, I used .insert() to add another column called "Population in 2020" and used census data from the nyc website to manually enter in each number by borough. I used .rename() to rename the "Population" column to "Population in 2020". Then, I used .insert() again to add my last column, "Population in 2010" and it's data into my table. I used the .apped() method to add a new row into my data set -> NYC Metro overall. I simpliy added all of the borough columns from each year to put in the data within the append method. 

With all of my data in the table, it's time for the visualization. I used .plot() to plot a simple line graph for all of my columns. I also used .plot.bar() to plot a bar graph, which I believe is a much better visual of the data. I also used .pivot_table to show a generic pivot table of my data that can be used and showed in an excel file.

In the future, I hope to get a better understanding of .plot() method and it's keyword arguements. I also would like to figure out a way to get future trends of data using the data I already have. I am looking to take two more courses on udemy regarding python for data science.

# Clone Name Generator 6/16/20

For my third project, I used python to create a clone birth name generator from the star wars series! I'm a huge star wars fan so this project definitely took my interest. I started off using numpy random number generator to show a number between 99 - 8000. Then I combined the Clone_Name_Generator with a 'ready for duty' string.

Another way I created a clone name generator was by taking the Clone_Name_Generator variable and placing it in a def function, followed by a for loop to print out the clone's birth name.

In the future, I would like to create the other classes of clones ( such as the Clone Commandos, ARC troopers, etc) . I also would like to create a list of different clone birth names using the generator. It would be interesting if I could find a way to show the nicknames of certain clones throughout the series (For example , Captian Rex's birth name is actually CT-7567 while Commander Cody's birth name was CC-2224).
