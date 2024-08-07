
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
```
<p><b>Time Complexity</b></p>
<ul>
    <li>Its amount of time taken by algorithm to run.</li>
    <li>The input processed by an algorithm helps in determining the time complexity.</li>
</ul>

<table>
    <tr>
        <td>
            <pre>
time taken 0.0 millisecs
public static long Sumofn(int n)
{
    return n * (n + 1) / 2;
}
            </pre>
        </td>
        <td>
            <pre>
 time taken 2.0 millisecs
public static long SumofNo(int n)
{
    long sum = 0;
    for (int i = 1; i <= n; i++)
    {
        sum += i;
    }
    return sum;
}
            </pre>
        </td>
    </tr>
</table>

<p><b>Space Complexity</b></p>
<ul>
    <li>Its amount of memory or space taken by algorithm to run.</li>
    <li>The memory reqired to process the input by an algorithm helps in determinig the space complexity.</li>
</ul>

<p><b>Asymptotic Analysis of an Algorithm</b></p>
<p>Asymptotic Analysis</p>
<ul>
    <li>It helps in evaluating performance of an algorithm in terms of input size and its increase.</li>
    <li>Using asymptotic analysis we don't measure actual running time of algorithm.</li>
 <li>It helps in determining how time and space taken by algorithm increases with input size.</li>
</ul>
<p> Asymptotic Notations</p>
    <p>Asymptotic Notations are the mathematical tools used to describe the running time of an algorithm in terms of input size.</p>
    <p>Example: Performance of a Car in 1 Liter of Petrol</p>
    <table class="example-table">
        <tr>
            <th>Traffic Condition</th>
            <th>Performance (km/liter)</th>
        </tr>
        <tr>
            <td>Highway (min traffic)</td>
            <td>25 km/liter</td>
        </tr>
        <tr>
            <td>City + Highway (avg traffic)</td>
            <td>20 km/liter</td>
        </tr>
        <tr>
            <td>City (max traffic)</td>
            <td>15 km/liter</td>
        </tr>
    </table>

<p>Asymptotic Notations help us in determining:</p>
<ul>
        <li>Best Case</li>
        <li>Average Case</li>
        <li>Worst Case</li>
</ul>

<p><b> Types of Asymptotic Notations </b></p>
<p>There are three notations for performance running analysis of an algorithm</p>
<ul>
        <ol>1.Omega(Ω) Notation</ol>
        <ol>2.Theta (Θ) Notation</ol>
        <ol>3.Big O(O) Notation</ol>
</ul>
<p><b>Omega(Ω) Notation</b></p>
<p>It is the formal way to express the lower bound of an algorithm'size running time.
Lower bound means for any given input this notation determines the best amount of time an algorithm can take to complete.
For Example-If we say certain algorithm takes 100 secs as best amount of time.So,100 secs will be lower bound of that algorithm.the algorithm can take
more than 100 secs but it will not take less than 100 secs </p>

<p><b>Theta (Θ) Notation</b></p>
<P>
It is the formal way to express both the upper and lower bound of an algorithm's running time.
By Lower and Upper bound means for any given input this notation determines an average amount of time an algorithm can take to complete.
For example-If we run certain algorithm and it takes 100 secs for first run, 120 secs for second run ,110 for third run and so on.,So Theta (Θ) Notation gives an 
average of running time of that algorithm.
</P>
<p><b>Big O(O) Notation</b></p>
<p>
It is the formal way to express the upper bound of an algorithm's running time.
Upper bound means for any given input this notation determines longest amount of time an algorithm can take to complete.
<b>For Example</b> If we say certain algorithm takes 100 secs as longest amount of time.So 100 secs will be upper bound of that algorithm .
the algorithm can take less than 100 secs but it will not take more than 100 secs
</p>

<h4>Examples</h4>
 <div class="container">
        <h1>What is an Array?</h1>
       <img src="https://github.com/prabhatkumar1379/DSA/blob/main/array.PNG?raw=true" alt="Array Example">
        <ul>
            <li>1. It’s a collection (box) of data elements of specified type.</li>
            <li>2. All data holding partitions have contiguous memory locations.</li>
            <li>3. Each partition has two neighbors except first and last one.</li>
            <li>4. Size of array is fixed and cannot be modified once it is created.</li>
            <li>5. Being adjacent each partition is indexed and can be determined by its position.</li>
            <li>6. Index starts at 0 and for (one dimensional array) ends at length - 1.</li>
        </ul>
    </div>
## Declaration and Initialization of an Array

### Declaration of a One Dimensional Array
One Dimensional array can be declared via syntax:
<p>dataType arrayName[];</p>
<p>dataType [] arrayName;</p>
for example 

```
int myarr [];
int [] myarr;
```

<h4>Initialization of an Array</h4>
<p>
It gives memory to array element .One Dimensional array can be initialized via syntax -</p>

```
arratName = new dataType[size];
for example-
myarr = new int [5];
```

<h4>Declaration and Initialization</h4> 

the array can declared and initialized in same line  via syntax -
```
dataType [] arraName = new dataType[size];
dataType arraName [] = new dataType[size];

For example -
int [] myarr = new int[5];
int myarr [] =new int[5];
int[] myarr = new int[] {1, 2, 3, 4};
int myarr[]  = new int[] {1, 2, 3, 4};
int myarr [] = new[] {1, 2, 3, 4};


```
