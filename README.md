# cosc122-lab-1-introduction-to-data-structures-and-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [COSC122 Lab 1-Introduction to Data Structures and Algorithms Solved](https://www.ankitcodinghub.com/product/cosc122-lab-1-introduction-to-data-structures-and-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100072&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSC122  Lab 1-Introduction to Data Structures and Algorithms Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Introduction to Data Structures and Algorithms

Goals

This lab will give you some experience with different searching algorithms and a high-level overview of some of the data structures you will encounter in this course. This lab is designed to give you a taste of some of the material you will encounter — future labs will cover these topics (and others) in much greater detail.

Labs and Lab Quizzes

Welcome to the first lab for the course! These labs build upon the material presented in lectures and described in your textbook by giving you some experience with writing, using, and adapting various data structures and algorithms. The primary emphasis of these labs is on analysing and understanding, rather than writing code.

Material in these labs will often build upon examples shown in your textbook. As such, it is strongly recommended that you read the associated chapters/sections of the textbook before attempting these labs. Links to the online version of the textbook will usually be provided in footnotes. You might also want to bookmark the main textbook page (here).

For Lab 1, you are not expected to know how searching algorithms work. But if you are interested sections 6.2 (link) and 3.5 (link) in the online textbook cover the relevant details.

As with the introduction to programming course, each lab has a Quiz Server quiz associated with it. These quizzes must be completed and submitted by the due date given in each quiz (usually the Monday after the topic is covered in labs). You only get one attempt at each lab quiz, unlike COSC121/131, but a practice quiz will open after the due date for you to do more practice.

Searching Algorithms

In the archive for this lab is the arrays.py module, which contains a few classes that implement a data structure for an array that stores positive integers. The three classes in the module are:

1. LinearArray—usesaPythonlistforstoringitems.

2. SortedArray—usesasortedPythonlistforstoringitems.

3. BitVectorArray—using a modified bit vector for storing items (see the “Comparing Search Meth- ods” section).

However, some of the methods in these classes aren’t finished yet—you will have to complete them before you can try them out.

Linear Searching

Please note, the linear search method is also known as sequential search and the textbook refers to it as sequential search. Given the simplicity of this method, it should be clear that linear and sequential can easily be interchanged. Linear refers more to the time complexity for the method and sequential refers more to the way we search through a list of items. If the list is laid out in a straight line then both ideas are very similar, ie, a search is just a walk along the line of items until we find the one we are looking for.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The LinearArray class contains the code for storing a simple Python list of ints, with a few methods to insert new values, delete existing values, and check to see if a particular value exists in the array. Although a Python list already comes with this functionality, we want to experiment with potentially more efficient ways of doing things.

You will need to complete the find_index method to search the self.data list for the provided value, returning the index of the item if it is found within the list. Use the comments in the method as a guide, and remember to count the number of comparisons with data in the array using the self.comparisons variable.

To test your code, you can create a new instance of the LinearArray class and manually test inserting, deleting, and checking for the existence of elements:

from arrays import LinearArray x = LinearArray()

# Insert some items x.insert(3)

x.insert(2)

x.insert(1)

# Look for an item; should return True x.contains(2)

# Remove an item

x.remove(2)

# Look for an item; should return False x.contains(2)

The archive also contains a few data files that you can use to test the class and the number of com- parisons required for each operation. There first four files: file0.txt, file1.txt, file2.txt, and file3.txt; with 10, 100, 1000, and 10000 inserts into the array, respectively. The test files are basically lists of com- mands to run on the various arrays. These trace files allow us to test the arrays with exactly the same sequence of commands so we can see the difference in performance for the same workload. The data files from number 4 onward contain various sized batches of commands that can be used for testing and comparison—and lab quiz questions. The start of test file 0 looks like:

i 89 i 97 c 97 i 11 c 11 i0 c 11 i 88 …

Where:

• istandsforinsert

• cstandsforcontains?(ormorespecificallycheckwhetheranumberisinanarray) • dstandsfordelete/removenumberfromarray

Open the array_tests.py file and have a look at the process_file function. If you run the array_tests. py module then it will run the main_tests function that will run the following example:

# for example

filename = ‘file0.txt’

print(‘Processing’, filename, ‘with a linear array’) test_array = LinearArray() # initialise a LinearArray process_file(filename, test_array)

This will produce the following output for file0.txt, where the first number is the index of the trace line being run:

Processing file0.txt with a linear array

</div>
</div>
<div class="layoutArea">
<div class="column">
0: 1: 2:

</div>
<div class="column">
insert 89

insert 97 contains 97

</div>
<div class="column">
0 comparisons

0 comparisons

2 comparisons (found)

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
3: 4: 5: 6: 7: 8: 9:

10: 11: 12: 13: 14: 15: 16: 17: 18: 19:

</div>
<div class="column">
insert 11 contains 11 insert 0 contains 11 insert 88 contains 0 insert 55 insert 76 insert 27 contains 97 contains 88 contains 89 insert 6 contains 11 contains 27 insert 64 contains 1

</div>
<div class="column">
0 comparisons 3 comparisons 0 comparisons 3 comparisons 0 comparisons 4 comparisons 0 comparisons 0 comparisons 0 comparisons 2 comparisons 5 comparisons 1 comparisons 0 comparisons 3 comparisons 8 comparisons 0 comparisons

10 comparisons

</div>
<div class="column">
(found) (found) (found)

(found) (found) (found)

(found) (found)

(not found)

</div>
</div>
<div class="layoutArea">
<div class="column">
Once LinearArray is working and giving the correct output, you can try the other input files as well. Note that inserting an element in a LinearArray takes no comparisons at all, while checking whether or not an array contains an element can take a long time for those inserted relatively recently (as they are near the end of the list). In the upcoming sections we will see that Sorted and BitVector arrays work differently, eg, the sorted array will use some comparisons when adding and the BitVector will only need one comparison when searching . . .

&gt; Now you can answer the Linear search questions in Quiz1. Binary Searching

The SortedArray class performs the same operations as LinearArray, but uses a binary search algorithm to insert and check if an array contains elements.

This time, all of the methods have been completed for you, however: you need to add the code

to count the number of data comparisons (not index comparisons) in the appropriate places in both

insert and find_index.

Once you have completed this, you can test your code by processing the data files. The output when

processing file0.txt with a sorted array should look like:

</div>
</div>
<div class="layoutArea">
<div class="column">
Processing file0.txt with a

</div>
<div class="column">
sorted array 0 comparisons 1 comparisons 1 comparisons 2 comparisons 3 comparisons 2 comparisons 3 comparisons 2 comparisons 5 comparisons 2 comparisons 3 comparisons 3 comparisons 5 comparisons 5 comparisons 3 comparisons 4 comparisons 3 comparisons 5 comparisons 4 comparisons 8 comparisons

</div>
</div>
<div class="layoutArea">
<div class="column">
0: 1: 2: 3: 4: 5: 6: 7: 8: 9:

10: 11: 12: 13: 14: 15: 16: 17: 18: 19:

</div>
<div class="column">
insert

insert contains insert contains insert contains insert contains insert insert insert contains contains contains insert contains contains insert contains

</div>
<div class="column">
89 97 97 11 11

0 11 88 0 55 76 27 97 88 89 6 11 27 64 1

</div>
<div class="column">
(found) (found) (found) (found)

(found) (found) (found)

(found) (found)

(not found)

</div>
</div>
<div class="layoutArea">
<div class="column">
NOTE: If Wing truncates (leaves out) some of the output with longer files then you should run your program in debug mode (click the red bug icon instead of the green ◃ play button.)

&gt; Now you can answer the Binary Search questions in Lab Quiz 1.

Once you have had a play and understand the search methods and data files you should consider

the following questions:

• Whichsearchisbetterforfailedcontainsoperations?Why?

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
• Whyaretherenocomparisonsneededfortheinsertoperationinthelinearsearch,butafeware needed for the binary search?

• For linear search, how is the number of comparisons needed to check that an item exists related to that item? Why does looking for 5635 in file3 take fewer comparisons in linear search than in binary search?

Comparing Search Methods

Performing a comparison between two data values is one of the slowest operations and the most fre- quent operations in a searching algorithm, which is why algorithms seek to minimise the number of comparisons they make. In addition to printing out the number of comparisons, the time.perf_counter() function provided by the time module allows you to examine how long it actually takes code to execute.

The array_tests.py module imports time and provides a timing example in the time_sorted_trial function (as shown below):

def time_sorted_trial(filename):

“”” Times how long it takes to processes the

given file with a SortedArray

“””

test_array = SortedArray()

print(‘\nRunning trial on sorted array with’, filename) start_time = time.perf_counter()

process_file(filename, test_array)

end_time = time.perf_counter()

time_taken = end_time – start_time

print(f”Took {time_taken:.3f} seconds.”)

return time_taken

Try using time on a SortedArray and a LinearArray – note the difference in execution time. You will want to write a time_linear_trial function that is very similar to the provided time_sorted_trial function. Use files file1, file2 and file3 to look at how the relative performance of each implementation changes as the input size increases.

&gt; Now you can answer the Linear vs Binary question(s) in Lab Quiz 1.

The arrays module also contains a BitVectorArray class. This is an implementation that uses a vari- ation of a bit vector or bitmap data structure to store its data—instead of storing each inserted value in the list, it simply records how many times a particular value is inserted. This data structure isn’t covered in the textbook, so don’t worry if you don’t understand it—it’s used here because it happens to work well for this particular kind of data (and is part of a good answer to Google’s question to Barack Obama1).

You can use the BitVectorArray as you have for the LinearArray and SortedArray with one difference: when you’re creating the BitVectorArray, you need to tell it what the largest possible value you will store is:

b1 = BitVectorArray (100) process_file(‘file0.txt’, b1) b3 = BitVectorArray (10000) process_file(‘file3.txt’, b3)

Use time to examine how fast the BitVectorArray is, and compare its results to that of the other two implementations (especially when you use files file2 and file3).

Although a bit vector is extremely fast and efficient (compared to linear and binary searching), this doesn’t mean it’s the panacea of searching algorithms; it has some major disadvantages. 2

1 http://www.youtube.com/watch?v=k4RRi_ntQc8&amp;feature=youtu.be

2The fact that you need to tell it how big the largest item you want to store is might give you a hint about what some of those disadvantages are.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Testing Python’s List and Set Implementations

Sets have been covered in the introduction to programming course. Please read section 3.5 to 3.8 of the online textbook. In this section, we will compare the behaviour of the Python ’in’ operation (which checks whether an item is contained in the given list or set) using a list and a set implementation.

Note: In this section you will run tests for various list sizes (n’s) but you will run each test a number of times and report the average time taken for the given list size (n).

<ul>
<li>Run the appropriate code in internal_trials.py to test searching in a Python list. Plot the results in a graph. See notes below for graphing ideas.</li>
<li>Changethenumberoftrialsto5,10,100,etc.anduseagraphtocomparethebehaviourof’in’in a list. Try 1000 trial runs if you don’t get too bored waiting… See graphing tips below.</li>
<li>Complete the code in run_set_trials so that it tests the ’in’ operation on a set. The code will be very similar to the run_list_trials function except you will need to execute a statement like (found = value_to_find in test_set) multiple times as specified by variable num_trials. Make sure that
the program displays the average time taken by a single search, as the size of the set changes.
</li>
<li>Changethenumberoftrialsto5,10,100,etc.anduseagraphtocomparethebehaviourof’in’in
a set. Try 1000 trial runs, hopefully it is a bearable wait… See graphing tips below.
</li>
<li>Running more trials shouldn’t greatly affect the time per ’in’ operation, so why is it important to
use multiple trials? Think about the nature of modern multi-tasking, multi-processor computers.
</li>
<li>Compare the two implementations by plotting, in a single graph, the values for both implemen- tations for 100 trials. You should get a graph similar to the graph at the bottom of section 2.7 of the online text book.
Graphing Tips

Installing matplotlib

Lab computers have Python and matplotlib installed so don’t try to install them there! If you are running Python on your own computer then you will need to make sure you install matplotlib. The easiest way to install maplotlib is to open the install_numpy_and_matplotlib.py in Wing101 and run it. This will ensure maplotlib is set-up for your user in the Wing environment that you will be running it. Or, check out the matplotlib install page directly, here. Either way, if you are using Windows, the important thing is to make sure you checked the Add Python 3.x to PATH option when installing Python.

Generating data and graphs

Tab delimiting your output (as shown in the run_list_trials function) will allow you to cut and paste output in to Excel (or Libre Office Calc). But, investing a little time in setting up some graphing code in Python will make experimenting a lot easier. Therefore, we recommend you try using matplotlib to get plots of the output. The following gives you an example of how to use matplotlib and is similar to the function graph_one_series_example in internal_trials.py.

import matplotlib.pyplot as plt n_trials = 10

x1, y1 = run_list_trials(n_trials)

# We use the following instead of axes = plt.axes() as it opens new figures (figs) # in new windows for example if you call graph_one_series_example then call

# graph_one_series_example you will get two graph windows 🙂

fig, axes = plt.subplots()

axes.plot(x1, y1, color=’blue’, marker=’o’, label=’list’) axes.set_title(f’List Locate Testing, {n_trials} Trial runs’) axes.set_xlabel(‘n’)
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
axes.set_ylabel(‘Average Time per locate’)

axes.grid(True)

axes.xaxis.set_major_formatter(‘{x:.0f}’) # otherwise defaults to exp notation legend = axes.legend(loc=’upper left’)

plt.show()

Check out the graph_one_series_example and graph_two_series_example functions for some graphing that we already had in the oven. The one series function currently plots the results of list tests but you can easily change it so that it runs set tests instead.

&gt; Now you should be able to answer the Comparing Structures questions in Lab Quiz 1. Sorting Algorithms

Experiment with the sorting algorithm animations at http://www.sorting-algorithms.com/ and make notes about which method is the fastest and how they deteriorate as the problem size changes. You do not need to understand how the algorithms work, just examine the performance characteristics of each under various conditions.

&gt; Now you can answer the Comparing Sorts questions in Lab Quiz 1. Complexity

To end the main part of this lab we have a quick review of asymptotic complexity.

Simple method to determine Big Oh for an algorithm

<ol>
<li>Findanoperationthatthealgorithmdoesatleastasmuchasanyother.</li>
<li>Counthowoftenitisdone(intermsoftheinputsize,n).</li>
<li>Takehighestordertermonly

(increasing order is 1, logn, n, nlogn, n2, n3, n4,…,2n, 3n, n!) and drop any constant that it is multiplied by.</li>
<li>Removeanyconstants.</li>
</ol>
Forexample,ifanalgorithmuses6+5n+6n2+3n3 operationswewouldsayitisO(n3)becausen3 is the part that will grow the quickest. We don’t worry about constant multiples so we wouldn’t write it as O(3n3).

Note you can think of constants as constant ×1, eg, an algorithm that takes 6 operations can be thought of as taking 6 × 1 operations and therefore we can treat it as O(1). Basically, any constant term is treated as O(1).

&gt; Now you can answer the Complexity – Big Oh questions in Lab Quiz 1. Extras

<ul>
<li>ChangethecontainsmethodinSortedArraytousefewercomparisons(downtoroughlyhalfinthe best case). Hints: When searching for x, in initial comparisons, is x more likely to be less than the indexed value or equal to the indexed value? If x is less than (or greater than) the indexed item do you need to also check if it is equal to the indexed item?</li>
<li>For file3, what percentage of entries are faster to check for existence in binary search compared with linear search?</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
