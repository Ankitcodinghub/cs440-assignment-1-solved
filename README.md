# cs440-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS440 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs440-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92288&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS440 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1: Tree Indexing

Assume that the block size is 30 bytes. In this question, each node in a B+ tree must fit in a block and its size must be as close as possible to the size of a block. Answer the following parts using B+ trees.

(a) Assume that all data values are integers with the fixed size of 8 bytes and each record pointer takes at most 4 bytes. Find a B+ tree whose height changes from 2 to 3 when the value 20 is inserted. Note that the height of a tree is depth of the deepest node plus one. For example, the height of a tree with a single node is 1. Show your structure before and after the insertion. (1 point)

(b) Assume that all data values are integers with the fixed size of 4 bytes and each record pointer takes at most 4 bytes. Find a B+ tree in which the deletion of the value 40 leads to a redistribution. Show your structure before and after the deletion. Your example could be different from the answer given for part (a). (1 point)

2: Indexing (1 point)

(a) Consider the following relational schema:

Emp(eid:integer, ename:string, age:integer, salary:real)

The underlined attributes are keys for their relations. Consider the following SQL query:

<pre>Select *
From Emp
Where age = 20 and salary &gt; 20000
</pre>
Describe B+ tree index on Emp that improves the running time of this query more than every other index over most Emp relation instances. You may explain the attributes, and their order of the index and whether it should be clustered.

3: Sorting on external storage

(a) Consider a file with records of following structure:

<pre>Emp (eid (integer), ename (string), age (integer), salary (double))
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Oregon State University Assignment 3 CS 440, Winter 2022

</div>
</div>
<div class="layoutArea">
<div class="column">
Fields of types integer, double, and string occupy 4, 8, and 40 bytes, respectively. Assume that each (I/O) block can fit at most one record (tuple) of the input file. Implement the two-pass multi-way sorting for the file Emp.csv in C/C++ using the skeleton code posted with this assignment. The sorting should be based on the attribute eid. There are at most 22 blocks available to the sort algorithm in the main memory, i.e., the size of the buffer is 22.

<ul>
<li>The input relation is stored in a CSV file, i.e., each tuple is in a separate line and fields of each record are separated by commas.</li>
<li>The result of the sort must be stored in a new CSV file. The file that stores the relation Emp are Emp.csv.</li>
<li>Your program must assume that the input file is in the current working directory, i.e., the one from which your program is running.</li>
<li>The program must store the result in a new CSV file with the name EmpSorted.csv in the current working directory.</li>
<li>Your program must run on Linux. Each student has an account on hadoop-master.eecs.oregonstate.edu server, which is a Linux machine. You may use this machine to test your program if you do not have access to any other Linux machine. You can use the following bash command to connect to ir:
<pre>     &gt; ssh your_onid_username@hadoop-master.eecs.oregonstate.edu
</pre>
Then it asks for your ONID password and probably one another question. You can access this server on campus. If you want to access from outside of campus, you’ll need to use VPN to access the campus network.
</li>
<li>You must name the file that contains the source code of the main() function main3.cpp.</li>
<li>You may use following commands to compile and run C++ code:
<pre>     &gt; g++ -std=c++11 main3.cpp -o main3.out
     &gt; main3.out
</pre>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
