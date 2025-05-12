# csu22012-assignment-2-shortest-path-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [CSU22012 Assignment 2-Shortest path Algorithms Solved](https://www.ankitcodinghub.com/product/csu22012-assignment-2-shortest-path-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90915&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSU22012 Assignment 2-Shortest path Algorithms Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Problem description:

ACM is a reality TV contest that sets three contestants at three random city intersections. win, the three contestants need all to meet at any intersection of the city as fast as possible.

</div>
<div class="column">
In order to

</div>
</div>
<div class="layoutArea">
<div class="column">
The contestants may arrive at the intersections at different times, in which case, the first to arrive can wait until the others arrive.

From an estimated walking speed for each one of the three contestants, ACM wants to determine the minimum time that a live TV broadcast should last to cover their journey regardless of the contestants’ initial positions and the intersection at which they finally meet. You are hired to help ACM answer this question.

You may assume the following:

<ul>
<li>Each contestant walks at a given estimated speed.</li>
<li>The city is a collection of intersections in which some pairs are connected by one-way streets that the contestants can use to traverse the city. Two intersections can be connected by two one-way streets allowing travel in opposite directions of each other.
Input:

As input you are given the following parameters:
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
• A filename (String) containing the details of the road network, as follows:

o Line 1 = integer N representing the total number of intersections

o Line 2 = integer S representing the total number of streets in the city. All streets are one-way, they connect two intersections, and there is at most one street connecting any pair of intersections in any one direction (at most two streets, one in each direction)

o Lines 3 onwards – each line represents a street and consists of 2 integers (2 intersections that the street is connecting) and a double (representing the street length in kilometers), separated by a space.

A sample input file might look like: 3

2

<ol>
<li>1 &nbsp;2 0.5</li>
<li>2 &nbsp;3 0.75</li>
</ol>
Representing a city with 3 intersections and 2 streets, in which the length of the street leading from intersection 1 to 2 is 0.5km, and the length of the street leading from intersection 2 to 3 is 0.75.

• Three integers representing the average walking speed of each of the three contestants, in meters per minute sA, sB, sC where (50 ≤ sA, sB, sC ≤ 100)

Assignment specification

You need to solve the above problem using two different shortest path algorithms in order to observe the differences between their implementation and performance.

1. Dijkstra version

Download CompetitionDijkstra.java file.

Write a java class CompetitionDijkstra in CompetitionDijkstra.java file (please do not use custom packages as web-cat will give an error) which should implement at least the following methods:

<ul>
<li>CompetitionDijkstra (String filename, int sA, int sB, int sC) – constructor for this class should take the four parameters as specified in the input, and create and populate the most appropriate data structure in which to hold the city road network in this example. Walking speeds should be stored in member variables.</li>
<li>public int timeRequiredforCompetition()- this method should return an integer indicating the minimum number of minutes that will pass before the three contestants can meet in the city generated in your constructor, if they start to walk immediately after the show starts. Remember that the contestants can be originally located at any random (unknown) intersection and can decide to meet at any random unknown intersection: you need to account for the worst case scenario. The answer should be given rounding decimals to the next integer (e.g., 2.9 minutes rounds up to 3 minutes and 3.2 minutes rounds up to 4 minutes). If it is not possible to run the given competition in a given city represented by the</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
map you generated (i.e., if there are 2 random locations in a city between which no path exists), the method should return -1, as should for any other errors (eg input walking speeds outside the specified range). To implement this method you have to use Dijkstra’s shortest path algorithm.

2. Floyd-Warshall version

Download CompetitionFloydWarshall.java file.

Write a java class CompetitionFloydWarshall in CompetitionFloydWarshall.java file. The class should have the exact same functionality and the same Constructor parameters and method signature as specified in part 1 but use Floyd-Warshall’s algorithm to generate shortest paths.

3. Testing

Download CompetitionTests.java file.

Write a java class CompetitionTests in CompetitionTests.java file, which should implement JUnit tests for your CompetitionDijkstra and CompetitionFloydWarshall classes

Your goal is to write enough tests so that:

<ul>
<li>Each method in in the classes is tested at least once,</li>
<li>Each decision (that is, every branch of if-then-else, for, and other kinds of choices) in is
tested at least once,
</li>
<li>Each line of code in all classes is executed at least once from the tests.
The submission server will analyse your tests and code to determine if the above criteria have been satisfied.

You are given a number of test input files. Please use tinyEWD and 1000EWD in the first instance. All other input files have been created to test edge cases that might arise, and are those that webcat will evaluate your code with.

For Fun (not marked)

Implement the same competition using Bellman-Ford algorithm and compare the performance to Dijkstra and Floyd-Warshall for different type/size of input graphs. Download a sample file containing 1 milion vertices and 15 million edges from https://algs4.cs.princeton.edu/44sp/ and try to test the performance. Following that, you can modify input files to contain negative weights and run the competition. You will need to extend the code to first detect negative cycles. Observe what happens to Dijkstra version.
</li>
</ul>
</div>
</div>
</div>
