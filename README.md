# linear-data-homework-10-solved
**TO GET THIS SOLUTION VISIT:** [Linear Data Homework 10 Solved](https://www.ankitcodinghub.com/product/data-structure-important-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110159&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Linear Data Homework 10 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
1. All submitted code must compile under JDK 8. This includes unused code, so don’t submit extra files that don’t compile. Any compile errors will result in a 0.

2. Do not include any package declarations in your classes.

3. Do not change any existing class headers, constructors, instance/global variables, or method signatures.

4. Do not add additional public methods.

5. Do not use anything that would trivialize the assignment. (e.g. don’t import/use java.util.ArrayList for an Array List assignment. Ask if you are unsure.)

6. Always be very conscious of efficiency. Even if your method is to be O(n), traversing the structure multiple times is considered inefficient unless that is absolutely required (and that case is extremely rare).

7. You must submit your source code, the .java files, not the compiled .class files.

8. After you submit your files, redownload them and run them to make sure they are what you intended to submit. You are responsible if you submit the wrong files.

Graph Algorithms

For this assignment, you will be coding 4 different graph algorithms. This homework has quite a few files in it, so you should make sure to read ALL of the documentation given to you before asking a question.

Graph Data Structure

You are provided a Graph class. The important methods to note from this class are:

• getVertices provides a Set of Vertex objects (another class provided to you) associated with a graph.

• getEdges provides a Set of Edge objects (another class provided to you) associated with a graph.

• getAdjList provides a Map that maps Vertex objects to Lists of VertexDistance objects. This Map is especially important for traversing the graph, as it will efficiently provide you the edges associated with any vertex. For example, consider an adjacency list map where vertex A is associated with a list that includes a VertexDistance object with vertex B and distance 2 and another VertexDistance object with vertex C and distance 3. This implies that in this graph, there is an edge from vertex A to vertex B of weight 2 and another edge from vertex A to vertex C of weight

3.

Vertex Distance Data Structure

In the Graph class and Dijkstra’s algorithm, you will be using the VertexDistance class implementation that we have provided. In the Graph class, this data structure is used by the adjacency list to represent which vertices a vertex is connected to. In Dijkstra’s algorithm, you should use this data structure along with a PriorityQueue. At any stage throughout the algorithm, the PriorityQueue of VertexDistance objects will tell you which vertex currently has the minimum cumulative distance from the source vertex.

Search Algorithms

Breadth-First Search is a search algorithm that visits vertices in order of “level”, visiting all vertices one edge away from start, then two edges away from start, etc. Similar to levelorder traversal in BSTs, it depends on a Queue data structure to work.

Depth-First Search is a search algorithm that visits vertices in a depth based order. Similar to pre/post/inorder traversal in BSTs, it depends on a Stack data structure to work. However, in your implementation, the Stack will be the recursive stack. It searches along one path of vertices from the start vertex and backtracks once it hits a dead end or a visited vertex until it finds another path to continue along. Your implementation of DFS must be recursive to receive credit.

Single-Source Shortest Path (Dijkstra’s Algorithm)

There are two main variants of Dijkstra’s Algorithm related to the termination condition of the algorithm. The first variant is where you depend purely on the PriorityQueue to determine when to terminate the algorithm. You only terminate once the PriorityQueue is empty. The other variant, the classic variant, is the version where you maintain both a PriorityQueue and a visited set. To terminate, still check if the PriorityQueue is empty, but you can also terminate early once all the vertices are in the visited set. You should implement the classic variant for this assignment. The classic variant, while using more memory, is usually more time efficient since there is an extra condition that could allow it to terminate early.

Minimum Spanning Trees (MST – Prim’s Algorithm)

An MST has two components. By definition, it is a tree, which means that it is a graph that is acyclic and connected. A spanning tree is a tree that connects the entire graph. It must also be minimum, meaning the sum of edge weights of the tree must be the smallest possible while still being a spanning tree.

By the properties of a spanning tree, any valid MST must have |V | − 1 edges in it. However, since all undirected edges are specified as two directional edges, a valid MST for your implementation will have 2(|V | − 1) edges in it.

Prim’s algorithm builds the MST outward from a single component, starting with a starting vertex. At each step, the algorithm adds the cheapest edge connected to the incomplete MST that does not cause a cycle. Cycle detection can be handled with a visited set like in Dijkstra’s.

Self-Loops and Parallel Edges

In this framework, self-loops and parallel edges work as you would expect. If you recall, self-loops are edges from a vertex to itself. Parallel edges are multiple edges with the same orientation between two vertices. These cases are valid test cases, and you should expect them to be tested. However, most implementations of these algorithms handle these cases automatically, so you shouldn’t have to worry too much about them when implementing the algorithms.

Visualizations of Graphs

Grading

Here is the grading breakdown for the assignment. There are various deductions not listed that are incurred when breaking the rules listed in this PDF, and in other various circumstances.

Methods:

BFS 15pts

DFS 15pts

Dijkstra’s 25pts

Prim’s 20pts

Other:

Checkstyle 10pts

Efficiency 15pts

Total: 100pts

A note on JUnits

If you need help on running JUnits, there is a guide, available on Canvas under Files, to help you run JUnits on the command line or in IntelliJ.

Style and Formatting

It is important that your code is not only functional but is also written clearly and with good style. We will be checking your code against a style checker that we are providing. It is located on Canvas, under Files, along with instructions on how to use it. We will take off a point for every style error that occurs. If you feel like what you wrote is in accordance with good style but still sets off the style checker please email Tim Aveni (tja@gatech.edu) with the subject header of “[CS 1332] CheckStyle XML”.

Javadocs

Vulgar/Obscene Language

Any submission that contains profanity, vulgar, or obscene language will receive an automatic zero on the assignment. This policy applies not only to comments/javadocs but also things like variable names.

Exceptions

When throwing exceptions, you must include a message by passing in a String as a parameter. The message must be useful and tell the user what went wrong. “Error”, “BAD THING HAPPENED”, and “fail” are not good messages. The name of the exception itself is not a good message.

For example:

Bad: throw new IndexOutOfBoundsException(“Index is out of bounds.”);

Good: throw new IllegalArgumentException(“Cannot insert null data into data structure.”);

Generics

If available, use the generic type of the class; do not use the raw type of the class. For example, use new LinkedNode&lt;Integer&gt;() instead of new LinkedNode(). Using the raw type of the class will result in a penalty.

Forbidden Statements

• package

• System.arraycopy()

• clone()

• assert()

• Arrays class

• Array class

• Thread class

• Collections class

• Collection.toArray()

• Reflection APIs

• Inner or nested classes

• Lambda Expressions

• Method References (using the :: operator to obtain a reference to a method)

If you’re not sure on whether you can use something, and it’s not mentioned here or anywhere else in the homework files, just ask.

Debug print statements are fine, but nothing should be printed when we run your code. We expect clean runs – printing to the console when we’re grading will result in a penalty. If you submit these, we will take off points.

Provided

The following file(s) have been provided to you. There are several, but we’ve noted the ones to edit.

1. GraphAlgorithms.java

This is the class in which you will implement the different graph algorithms. Feel free to add private static helper methods but do not add any new public methods, new classes, instance variables, or static variables.

2. GraphAlgorithmsStudentTests.java

This is the test class that contains a set of tests covering the basic operations on the GraphAlgorithms class. It is not intended to be exhaustive and does not guarantee any type of grade. Write your own tests to ensure you cover all edge cases. The graphs used for these tests are shown above in the pdf.

3. Graph.java

This class represents a graph. Do not modify this file.

4. Vertex.java

This class represents a vertex in the graph. Do not modify this file.

5. Edge.java

This class represents an edge in the graph. It contains the vertices connected to this edge and its weight. Do not modify this file.

6. VertexDistance.java

This class holds a vertex and a distance together as a pair. It is meant to be used with Dijkstra’s algorithm. Do not modify this file.

Deliverables

You must submit all of the following file(s). Please make sure the filename matches the filename(s) below, and that only the following file(s) are present. If you make resubmit, make sure only one copy of the file is present in the submission.

After submitting, double check to make sure it has been submitted on Canvas and then download your uploaded files to a new folder, copy over the support files, recompile, and run. It is your responsibility to re-test your submission and discover editing oddities, upload issues, etc.

1. GraphAlgorithms.java
