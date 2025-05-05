# csci411-week-6-solved
**TO GET THIS SOLUTION VISIT:** [CSCI411 Week 6 Solved](https://www.ankitcodinghub.com/product/csci411-week-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98720&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI411 Week 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Written Problems

1. (Adapted from exercise 6.2 from Sanjoy Dasgupta, et al., Algorithms, McGraw Hill, 2008)

You are going on a long trip. You start on the road at mile post 0. Along the way there are n hotels, at mile posts a1 &lt; a2 &lt; · · · &lt; an, where each ai is measured from the starting point. The only places you are allowed to stop are at these hotels, but you can choose which of the hotels you stop at. You must stop at the final hotel (at distance an), which is your destination.

You’d ideally like to travel 200 miles a day, but this may not be possible (depending on the spacing of the hotels). If you travel x miles during a day, the penalty for that day is (200−x)2. You want to plan your trip so as to minimize the total penalty – that is, the sum, over all travel days, of the daily penalties.

(a) (15 pts) Describe the optimal substructure of this problem. In particular, define the minimum total penalty in terms of penalties for shorter trips. Justify your answer.

(b) (10 pts) Let the sequence of hotel locations be A = [a1,a2,…,an]. Write pseudocode for a function hotelSequence(A) which returns the minimum total penalty.

(c) (5 pts) Analyze the asymptotic run time of your algorithm.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2. Given an undirected graph G = (V, E), a vertex cover of G is a subset of vertices C ⊆ V such that, for every edge {u,v} ∈ E, either u ∈ C or v ∈ C. It turns out that, while finding a vertex cover of minimum size is difficult for general graphs, it can be done efficiently for trees using dynamic programming.

<ol>
<li>(a) &nbsp;(25 pts) Describe the optimal substructure of this problem. In particular, given a tree T = (V, E), define the size of a minimum vertex cover in terms of smaller trees. Justify your answer.</li>
<li>(b) &nbsp;(15 pts) Write pseudocode for a function treeVC(T) which returns a minimum vertex cover of T.</li>
<li>(c) &nbsp;(5 pts) Analyze the asymptotic run time of your algorithm.</li>
</ol>
Coding Problem

(25 pts) Write a C++ implementation of the pseudocode you developed for problem (1b) and sub- mit to Blackboard and to turnin as assignment 5.cpp. You may find the skeleton code in assign- ment 5 skeleton.cpp on Blackboard helpful.

• Input will come from cin

– The first line will include two integers, n and m, separated by a space.

∗ 4 ≤ n ≤ 1000 is the total number of hotels.

∗ 10 ≤ m ≤ 1000 is the ideal number of miles traveled per day. In question 1, m = 200.

– n lines follow.

– Each line contains the distance of a particular hotel from the starting point. – You may assume that these distances are in sorted order.

• Print output to cout

<ul>
<li>– &nbsp;Your output should consist of two lines.</li>
<li>– &nbsp;The first line should be a space separated list of integers between 1 and n indicating the hotels visited. These should be in ascending order.</li>
<li>– &nbsp;The second line should be the minimum total penalty associated with the hotels visited. Examples</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Example 1:

Input: 4 200 200 400 600 800

Expected output: 1234

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
0

Example 2:

Input: 4 200 190 210 390 590

Expected output: 134

100

Example 3:

Input: 11 10 0

1

2 3 4 5 6 7 8 9 10

Expected output: 11

0

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
