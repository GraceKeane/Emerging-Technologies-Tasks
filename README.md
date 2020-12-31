### BSc (Honours) in Computing in Software Development
### Emerging Technologies Tasks 
### Grace Keane - G00359990


#### Tasks
<b>Task 1 - </b> 
I Developed a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. My code does not depend on
any module from the standard library or otherwise. It Includes research, descriptions, diagram and referances.

<b>Task 2 - </b>
The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables
are independent. Chi-squared value based on a given data set is approximately 24.6. I Used scipy.stats to verify this value and calculated the associated p value. I
included a short note with references justifying my analysis in a markdown cell.

<b>Task 3 -</b>
The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) .
However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above
calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . I Researched these Excel functions, writing a note in a Markdown cell
about the difference between them. Then used numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard
deviation of a population when performed on a sample.

<b>Task 4 -</b>
I used scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. I also explained in a Markdown cell how my code works and how accurate it
might be, and then explained how my model could be used to make predictions of species of iris. When this was complete I applied kNN (k Nearest Neighbours) to 
Fisher’s famous Iris data set.

#### Repository contents
- img - Contains two images used to demonstrate the consept of the square root function in task 1.
- .gitignore - Text file that tells Git to ignore Python in this project
- Emerging Technologies Tasks.ipynb - Contains all tasks from 1 to 4
- README.md - defines what each task was about, software requirements needed to run this project, steps on how to run and what to expect to see after you run the code.

#### Software requirements

The easiest way for a beginner to get started with Jupyter Notebooks is by installing Anaconda. Anaconda is the most widely used Python distribution for data science and comes pre-loaded with all the most popular libraries and tools.

In order to run this project some software needs to be installed on your machine. These include...
1) [Python](https://www.python.org/downloads/)
2) [Anaconda](https://www.anaconda.com/products/individual)
3) [cmder](https://cmder.net/)

#### How to run fully
- Clone repo
- Create a new folder on destop
- Cd into newly created folder in cmder & type "git clone (url here)"
- Type "jupyter notebook" to open project in Jupyter Notebook
- Click file with ".ipynb" at the end
- Click "Kernel" & "Restard & run all" (all code cells & markdowns should have run and displayed after 1 minute)

#### What to expect when running the code
After running the code, jupyter notebook should print out the output of each code block underneath each code cell and also print writing from the markdown cells .
