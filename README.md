Download Link: https://assignmentchef.com/product/solved-ch231a-assignment8-stacks-queues
<br>
<h1></h1>

<ul>

 <li> Implement using C++, Python or Java the data structure of a stack backed up by a linked list, that can store data of any type, and analyze the running time of each specific operation. Implement the stack such that you have the possibility of setting a fixed size but not necessarily have to (size should be −1 if unset). Your functions should print suggestive messages in cases of underflow or overflow. You can assume that if the size is passed, it will have a valid value.</li>

</ul>

<table width="502">

 <tbody>

  <tr>

   <td width="207">class Stack[T]:private:</td>

   <td width="295"> </td>

  </tr>

  <tr>

   <td width="207">struct StackNode {T data;StackNode <sup>∗ </sup>next;};</td>

   <td width="295">// linked list</td>

  </tr>

  <tr>

   <td width="207">StackNode <sup>∗ </sup>top;</td>

   <td width="295">// top of stack</td>

  </tr>

  <tr>

   <td width="207">int size;</td>

   <td width="295">// -1 if not set, value otherwise</td>

  </tr>

  <tr>

   <td width="207">int current_size; public:</td>

   <td width="295">// unused if size = -1</td>

  </tr>

  <tr>

   <td width="207">push(x : T) : void</td>

   <td width="295">// if size set, check for overflow</td>

  </tr>

  <tr>

   <td width="207">pop() : T</td>

   <td width="295">// return element if not in underflow</td>

  </tr>

  <tr>

   <td width="207">isEmpty() : bool Stack(int new_size)Stack()</td>

   <td width="295">// true if empty, false otherwise</td>

  </tr>

 </tbody>

</table>

<ul>

 <li> Implement a queue which uses two stacks to simulate the queue behavior.</li>

</ul>

<h1><strong>Problem 8.2 </strong>Linked Lists &amp; Rooted Trees</h1>

<ul>

 <li> Write down the pseudocode for an in-situ algorithm that reverses a linked list of <em>n </em>elements in Θ(<em>n</em>). Explain why it is an in-situ algorithm.</li>

 <li> Implement an algorithm to convert a binary search tree to a sorted linked list and derive its asymptotic time complexity.</li>

 <li><strong>Bonus </strong> Implement an algorithm to convert a sorted linked list to a binary search tree and derive its asymptotic time complexity. The search time complexity of the resulting binary search tree should be lower than the one for the equivalent sorted linked list.</li>

</ul>