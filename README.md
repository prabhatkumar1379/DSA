
# DSA
<h1>Data Structure</h1>
<div>
 It is a way to organise the data.
after organizing data ,it becomes easy to process it.
</div>
<hr> 
 <!-- https://www.youtube.com/watch?v=2ZLl8GAk1X4 -->     
<h2>Types of Data Structures</h2>
<table>
    <thead>
        <tr>
            <th>Linear Data Structures</th>
            <th>Non-Linear Data Structures</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Array</td>
            <td>Tree</td>
        </tr>
        <tr>
            <td>Linked List</td>
            <td>Graph</td>
        </tr>
        <tr>
            <td>Stack</td>
            <td>Heap</td>
        </tr>
        <tr>
            <td>Queue</td>
            <td>Trie</td>
        </tr>
        <tr>
            <td>Hash Table</td>
            <td></td>
        </tr>
    </tbody>
</table>
<hr>
<h1>Algorithms</h1>
<p>An algorithm is a set of instructions to perform a task or to solve a given problem. For example, a recipe book is a collection of recipes in which each recipe provides a step-by-step instruction to prepare food.</p>
<p>Let's say you want to prepare tea. The steps would be:</p>
<ol>
    <li>Boil water.</li>
    <li>Put tea in the teapot.</li>
    <li>Add hot water.</li>
    <li>Put hot tea into tea cups.</li>
    <li>Do you need sugar?
        <ul>
            <li>a) If yes, put it into tea cups.</li>
            <li>b) If no, do nothing.</li>
        </ul>
    </li>
    <li>Stir, drink, and enjoy!!!</li>
</ol>
 ----
 example
 <h3>Print average of 3 given numbers.</h3>
<p>Let say you want to write algorithm for it. So, the steps would be</p>
<ol>
    <li>Perform sum of 3 numbers.</li>
    <li>Store it in a variable <code>sum</code>.</li>
    <li>Divide the sum by 3.</li>
    <li>Store the value in variable <code>avg</code>.</li>
    <li>Print the value stored in <code>avg</code>.</li>
</ol>

```
public static void findAvg(int a, int b, int c)
    {
        int sum = a + b + c;
        int avg = sum / 3;
        Console.WriteLine(avg);
    }
```
<p><b>Analysis of Algorithms</b></p>

<ul>
    <li>An Algorithm is a set of instructions to perform a task or to solve a given problem.</li>
    <li>There are several different algorithms to solve a given problem.</li>
    <li>Analysis of algorithm deals in finding best algorithm which runs fast and takes in less memory.</li>
    <li>For example –
        <p>Q. Find sum of first n natural numbers.</p>
        <ul>
            <li>a) Input :- n = 4<br>
                Output :- 10 i.e. (1 + 2 + 3 + 4)</li>
            <li>b) Input :- n = 5<br>
                Output :- 15 i.e. (1 + 2 + 3 + 4 + 5)</li>
        </ul>
    </li>
</ul>
<p><b>Example</b></p>

```
a
```
public static long Sumofn(int n)
        {
            return n * (n + 1) / 2;
        }
        public static long SumofNo(int n)
        {
            long sum = 0;
            for(int i=1;i<=n;i++)
            {
                sum += i;
            }
            return sum;
        }
   
