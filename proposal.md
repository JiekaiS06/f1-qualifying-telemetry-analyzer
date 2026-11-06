# Proposal

## What will (likely) be the title of your project?

Formula 1 Qualifying Telemetry Analyzer

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

I plan to develop a Python program that analyzes four Q3 qualifying laps by Lewis Hamilton and Valtteri Bottas at the 2020 Belgian Grand Prix. It will display and compare telemetry such as speed, throttle, braking, and gear selection using charts.

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

My project will be a Python program for reading and analyzing qualifying telemetry from the 2020 Formula 1 Belgian Grand Prix at Spa-Francorchamps. The data covers four Q3 laps from Mercedes drivers Lewis Hamilton and Valtteri Bottas, two laps per driver. The program will read JSON files and extract speed, throttle position, braking status, gear, distance, and time data. Its basic version will display lap information and plot speed against track distance.

After the basic version works, I plan to add graphs for throttle, braking, and gear changes. A text-based menu will let users choose a driver, lap, and type of telemetry. If time permits, users will also be able to compare two laps on the same graph, or view multiple telemetry channels together. I would also like to calculate simple statistics, such as maximum and average speed for each lap.

The program will run locally in Python and use Matplotlib to display charts, subject to confirmation that third-party plotting libraries are permitted. I will use fundamental Python concepts from CIS 1051, including file handling, lists, dictionaries, loops, conditionals, and functions.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

Not applicable, only for CIS 1051

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

Not applicable.  I will work independently.

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

- - Read all four JSON telemetry files successfully.

- - Extract and display basic information for each driver and lap.

- - Plot speed against track distance for one selected lap.

- - Make sure the basic program runs reliably and displays the data correctly.

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

In addition to GOOD:

- - Plot throttle position, braking status, and gear changes.

- - Add a text-based menu for selecting drivers, laps, and telemetry channels.

- - Compare the same telemetry channel from two laps on one graph.

- - Organize the code into reusable Python functions.

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

In addition to BETTER:

- - Compare all four laps on the same graph.

- - Display several telemetry channels, such as speed, throttle, and braking, in one figure.

- - Calculate maximum and average speeds for each lap.

- - Add more flexible menu options for comparisons.

- - Improve chart labels, titles, legends, and readability.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

First, I will inspect the four JSON telemetry files I have downloaded and identify the fields I need. I will learn how to use Python's built-in json module to load the data and extract speed, distance, and other channels. I will then create a small working program that displays selected information.

Next, I will learn the basics of Matplotlib, if its use is permitted, and plot speed against track distance. Once the first graph works, I will add other telemetry channels. I will then use loops, conditionals, and functions to build a simple text-based menu and attempt a two-lap comparison. If time allows, I will expand the program to four-lap comparisons, combined plots, and basic speed statistics.

I will develop and test the project in stages, beginning with a reliable basic version before adding optional features. This is an individual project, so I will be responsible for all development and testing.

