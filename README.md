<h1>Merge Sort Algorithm</h1>

<h2>Description</h2>
<p>
  This project implements the merge sort algorithm in C++ using templates to handle various types of data. Merge sort is a divide-and-conquer algorithm that recursively divides the array into halves until it can't be divided further. It then merges the smaller sorted arrays back together, ensuring the entire array is sorted.
</p>

<h2>Files in the Project</h2>
<ul>
  <li><b><code>"mergeSort.h"</code></b> - Header file containing the merge sort algorithm implementation.</li>
  <li><b><code>"driverMergeSort.cpp"</code></b> - Main driver program that demonstrates the usage of the merge sort algorithm.</li>
</ul>

<h2>Languages and Utilities Used</h2>
<ul>
  <li><b>C++</b></li>
  <li><b><code>&lt;iostream&gt;</code></b> - For input and output operations.</li>
  <li><b><code>&lt;vector&gt;</code></b> - For using vectors to store data.</li>
</ul>

<h2>Environments Used</h2>
<ul>
  <li><b>Windows 10</b></li>
</ul>

<h2>How to Run</h2>
<ol>
  <li><b>Compile the Program:</b>
    <pre><code>g++ -o MergesortDriver MergesortDriver.cpp</code></pre>
  </li>
  <li><b>Execute the Program:</b>
    <pre><code>./MergesortDriver</code></pre>
  </li>
  <li><b>Follow the prompts</b> to see the original and sorted sequence.</li>
</ol>

<h2>Output</h2>
<p>
  The program outputs the original sequence of numbers and the sorted version using the merge sort algorithm.
</p>

<h2>Program Walkthrough</h2>
<p align="center">
  <b>Original sequence:</b>
  <br/>
  <br/>
  <code>5 2 8 1 7</code>
  <br/>
  <br/>
  <b>Sorted version:</b>
  <br/>
  <br/>
  <code>1 2 5 7 8</code>
</p>
