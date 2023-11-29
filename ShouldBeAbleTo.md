# Section 1: Course Fundamentals (Theory)
1. Explain what is .NET vs C#
2. .NET architecture and main components
3. What is CLI and what is its workflow
4. What is CLR and what are it's components.
5. C# features
6. Define Object, Class, Method, Namespace

# Section 2: C# Language Basics (Practical Starts Here)
7. Start a c# program with the class and Main method
8. What are primitive and non-primitive types.
9. What are the primitive types
10. Declare and initialize all primitive types and get also their default values
11. Create an example of a ternary evaluation
12. Create a situation of num1 and num2 are null, and then revert the if, meaning both should be false (Example clean code udemy, ep 62, 1:52)
13. Create an if, if else and else block
14. Create a syntactically correct switch case block
15. Create a syntactically correct switch expression block
16. Create a while and a do while. Explain the differences between them and the dangers associated with these.
17. Create a for and a foreach loop
18. Create a goto statement with its label. What are the dangers of backwards jumps?

# Section 3: Bank Project - Getting Started

# Section 4: C# Object Oriented Programming - Basics
19. Enumerate all types of classes (access and other modifiers) and what are their specificities.
20. What is the stack and the heap and what are the differences between them?

# Section 5: Fields
21. What is a field? Define fields in code. 
22. What are the fields access modifiers.What is its default access modifier if not specified?
23. What are the differences between the readonly and the const keywords

# Section 6: Methods
24. Define and Create a method in code
25. What are the access modifiers.What is its default access modifier if not specified? What other modifiers can we add?
26. What is encapsulation
27. What is the purpose of the "this" keyword?
28. What is the ref keyword when applied to arguments?
29. Whats a default param value and how to set it? Create a method where the default value is set
30. What is a named argument? Create a method where the args are named.
31. What is method overloading?
32. What is the ref keyword when applied to a param? Create a functioning example
33. What is the out keyword when applied to a param? Create a functioning example with a type declared in arg and one where the type is not declared.
34. What is the in keyword when applied to a param? Create a functioning example.
35. What is the ref return keyword when applied to a param? Create a functioning example.
36. What is the params keyword when applied to a param? Create a functioning example.
37. What is a local function? Can it have access or other modifiers? And how about accessing vars and fields? Create a functioning example.
38. What are static local functions? Can it have access or other modifiers? And how about accessing vars and fields? Create a functioning example.
39. What is recursion? Where can it be used? Give examples.

# Section 7: Type Conversion
40. What is implicit casting? Create an example
41. What is explicit casting? Create an example
42. What is parse? What can be the danger of this?Create an example
43. What is tryParse? Create an example
44. What are the conversion methods (System.Convert)?
Create an example
45. What is the dynamic keyword? Create an example?

# Section 8: Constructors
46. What is a constructor? Create an example
47. What is a static constructor? What are the key differences from a normal constructor? Create an example
48. What is object initializer? What must be in place for us to use it? Create an example

# Section 9: Properties & Indexers
49. What is a property? Create an example of a prop with a custom getter and setter.
50. Create an auto-implemented property and initialize it with a value
51. What is an indexer? Create an example with an overloaded index ex: I want to pass "first" or "second" and the value returned is the first or second element of the array.

# Section 10: Inheritance, Hiding, Overriding
52. What is inheritance? Create an example
53. What is the base keyword? Create an example
54. What is method hiding? Create an example
55. What are the keywords virtual and override? Create examples
56. What are the sealed keyword? Create and example with a class and with a method.

# Section 11: Abstract Classes and Interfaces
57. What is an abstract class? Create an example of a class and a method.
58. How can one access a non abstract method or property of an abstract class?
59. What is the difference between the abstract class and the interface?
60. What is an interface? Create an example
61. What can and can't we have in an interface?
62. In what way can we achieve polymorphism with an interface? Create an example
63. What is interface inheritance? Create an example
64. What is explicit interface implementation? Create an example

# Section 12: Namespaces
65. What is a namespace?
66. What are using statements? Give an example with an alias, a using static and a global using

# Section 13: Partial & Static Classes, Enumerations
67. What is a partial class? Create one example
68. What is a partial method? Create one example
69. What is a static class? What's its objective? Create one example
70. What is an enumeration? Create an example

# Section 14: Structures
71. What are structs? And what are the differences between struct and a class? Create an example
72. What are readonly structs? Create an example

# Section 15: System.Object Class
73. What is the class System.Object?
74. What is boxing and unboxing? Create examples

# Section 16: Generics
75. What is a generic class? Create an example
76. What are the generic constraints? Create a generic class with such constraints
77. What is a generic method? Create an example

# Section 17: Handling Null
78. What is a nullable? Create an example
79. What does the HasValue method? and how can I get the Value from the nullable?
80. What is the null coalescing operator? Create an example.
81. What is the null propagation operator? Create an example.
82. What is the null forgiving operator? Create an example.

# Section 18: Extension Methods and Pattern Matching
83. What is an extension method? Create an example.
84. What is pattern matching? Create an example
85. What is the keyword dynamic? Create an example

# Section 19: GC, Destructors, IDisposable
86. Write a using block and a using declaration with an overridden Dispose method that reads "disconnecting"

# Section 20: Delegates & Events
87. What is a delegate? Create one example.
88. What is a multicast delegate? Create one example.
89. What is an event? Create an example (console "Adding the event" when subscribing and when unsubscribing "Removing the event")
90. What is an auto-implemented even? What is the difference to a normal event? Create an example
91. What is an anonymous method? Create an example with a delegate and another subscribing to an event.
92. What is a lambda expression? Create a simple example. Then, for practicing, create normal methods and try to convert them into lambdas.
93. What are pre-defined delegate types? Create examples for each one.
94. Create an event handler with a customEventsArgs which is a child of EventArgs.
95. What is an expression tree? Create an example
96. What is expression body members? Create an example of a method with a getter and a setter for ex.
97. What are switch expressions? Create an example

# Section 21: Arrays
98. What is an array? There are 3 ways to declare an array. Create examples.
99. Explore the methods of the array class by creating an example of each
100. What is the BinarySearch method of the array? What's the absolute requirement that the array must verify before applying this search method?
101. Which is the sorting algo used in the sort method?
102. What's a multi-dimensional array? Create an example. How can I know the nr of dimensions?
103. What's a jaggedArray? Create an example
104. What's the difference between CopyTo and Clone? Create examples of both
105. Write examples of slices and indexes from last

# Section 22: Collections
106. What is a collection? What types there is? Create an example for each one.
107. Create a list with the object initializer. Explore all the methods of the class and create an example of each
108. Create a dictionary with the object initializer. Explore all the methods of the class and create an example of each. Loop through key/pair values in a for or foreach.
109. Create a sorted list. Explore all the methods of the class and create an example of each.
110. Create a sorted dictionary. Explore all the methods of the class and create an example of each.
110. What are the differences in time and memory complexity between the two?
111. What is an HashTable? Create an instance and explore the methods.
112. What is a generic HashSet? Whats the difference from HashTable? Create an example
113. What are the complexities of the generic types? Go through the list and for each write the answer and justify.
114. What are stack and queue? What's the difference between them? Create an example from each using their specific methods.
115. What is the hierarchy of interfaces in generic collections?
116. What is the relation between IEnumerable and IEnumerator? Create examples of how can we loop through a collection a while and all the methods and props of the IEnumerator.
117. Create a custom list deriving from IEnumerable. Why would someone create a custom list?
118. What is the IEquatable for? Create an example
119. What is the IComparable for? Create an example
120. What is the IComparer for? Create an example
121. What is the difference between Covariance vs Contravariance? Provide examples of both

# Section 23: Anonymous Types
122. What are anonymous types? Create an example of a normal, a nested and an array.

# Section 24: Tuples
123. What are Tuples and the difference between them and anonymous objects? Create an example.
124. What's a Value Tuple, what's the difference between them and regular Tuples? Create an example
125. What is deconstruction? Create an example discarding one of the vars.

# Section 25: LINQ
126. What is linq? What are the benefits?
127. What are the different groups of operators?

# Section 26: String, DateTime, Math
128. Create a string and examples for all the instance methods
129. Create examples for all the static methods
130. Create a string and use string formatting, interpolation and verbatin examples.
131. What's a string builder? What's its purpose? Create an example.
132. Create a DateTime and examples for all the instance methods.
133. Create examples with static properties
134. Create examples using the static methods of the static class Math.
135. Using regex, check if a string as 3 and only 3 digits.
136. Create examples using the other regex operators.

# Section 27: IO, Serialization, Encoding
137. Create examples exploring the static methods of the File Class
138. Create an instance and examples exploring the non-static FileInfo class
139. Create examples exploring the static methods of the Directory Class
140. Create an instance and examples exploring the non-static DirectoryInfo class
141. Create an instance and examples exploring the non-static DriveInfo class
142. Create an instance and examples exploring the fileStream class. 
143. Create an instance and examples exploring the streamWriter class. Create examples with normal instance creation and closing the stream; and create one example with the "using" block.
144. Create an instance and examples exploring the streamReader class. Create examples with normal instance creation and closing the stream; and create one example with the "using" block.
145. Whats the difference between fileStream and streamWriter?
146. Create an instance and examples exploring the binaryWriter class. Create examples with normal instance creation and closing the stream; and create one example with the "using" block.
147. Create an instance and examples exploring the binaryReader class. Create examples with normal instance creation and closing the stream; and create one example with the "using" block.
148. Whats the difference between streamWriter and binaryWriter?
149. Define Binary De/Serialization. Create an example using Binary Formatter class for writing and reading. What's the problem with this approach?
150. What's JSON De/Serialization? Create an example of both.
151. What's XML De/Serialization? Create an example of both.

# Section 28: Exception Handling
152. Create a Try/Catch/Finally block
153. Why the Finally is different from having the code that we want to run always, simply after the try/catch block?
154. What's an inner exception? How can we create one? Create an example.
155. Create a custom exception that inherits from InvalidOperationException. Create a catch for it.
156. Whats the Stack Trace? Create an example were it's printed to the console.
157. What's catch when? Create an example

# Section 30: C# 9 and 10 (.NET 6) - New Features
158. What's top level statements?
159. What's file scoped namespace?
160. What's a global using file?
161. Whats a module initializer? What's its purpose?
162. Create an example of a nullable type and a nullable forgiving operator
163. What's target typed "new" expression. Create an example when creating an instance and another returning from a method
164. What's pattern matching? Create an example with an if
165. Create an example with a normal switch case
166. Create an example with a switch case with a when
167. Create an example with a switch expression pattern
168. Create an example with a switch expression with relational and logical pattern
169. Create an example with a switch expression with property pattern
170. Create an example with a switch expression with tuple pattern
171. Create an example with a switch expression with positional pattern
171. Create an example with a switch expression with extended property pattern
172. What's a init-only property and what does it enable? Create an example
173. What's a readonly struct? Create one with a paramless ctor and with an init accessor
174. What's a record? Create an example.
175. Create 2 equal records instances and analyze the return of the equals method. Justify the result. What's the difference to a result from the same method of a normal class? Experiment also with the "==" operator.
176. Create a shallow copy of a record using the with operator.
177. Deconstruct a record to different vars. Do we need to create a deconstruct method? why?
178. Call a ToString() method on a record instance. What do we see and why? 
179. Create a custom constructor for a record class. Try to have 3 params, 2 passed and 1 calculated
180. Create a record instance from a record class that inherits from another.
181. Create a sealed record method that overrides a method from the parent.
182. Create a record struct and a readonly record struct. Explain their differences.
183. What are the args keyword in the static void Main? Create an example with static void main and with a top level statement.
184. Whats a partial method? Create 2 partial classes, 1 with a private field and a method signature, the other with the property that gets and sets the field and the method implementation.
185. What is a static anonymous function? Create an example trying to access a non static field and another trying to access const and static fields
186. Create a lambda expression with an explicit return type.
187. Initiate a const by referencing two other constants;
188. What are default methods in interfaces? Create an example
189. Create an interface with an internal method and try to implement the same on a child class.
190. Create an interface with a private method and try to implement the same on a child class. Doesn't work? why?
191. Create an interface with a static method and try to implement the same on a child class.
192. What's the IndexFromEnd? Create an example.
193. Create an array of objects, now using the Range Struct, get a slice from the 2nd element to the 5th element inclusive.

# Section 31: Threading
194. Whats a thread? Create one example.
195. Whats concurrent, parallel and concurrent&parallel execution? 
196. Create a thread via the ThreadStart delegate.
197. Create examples of the methods Start and Sleep.
198. Create 3 threads and from the 3rd thread call the join method of thread 1 and 2. What will happen to each of the threads?
199. Create 2 threads and from the 2nd call the interruption of the 1st. Catch the exception.
200. Explain the thread states and thread lifecycle
201. Create an example of a thread where args are being passed to the thread method through a lambda expression
202. Create an example of a thread where an arg is being passed to the thread method through a parameterized thread start.
203. Create a class to encapsulate the thread method in a way that it no longer requires an arg to be passed (accesses it via property of a class) (it should be 1 class to each thread to not create a concurrency of threads)
204. Return something from a thread to the invoker thread. For this, create a callback method that will make the thread method return.
205. What are the 3 most common problems with shared resource in a multi-threaded environment? Define and explain each one.
206. What's thread synchronization? What are the mechanisms? Define them.
207. Create one example where monitor mechanism is implemented with Enter method and another with TryEnter
208. What's thread signaling?
209. What's a synch primitive? Define the types
210. Describe the methods of the ManualResetEvent. Create an example
211. Create a Producer/Consumer model with the ManualResetEvent where an initial 15 element array is filled in 5 batches of 3. The consumer does the same and prints in batches of the 3 to the console.
212. Take the example created before and change it to an autoResetEvent type of primitive
213. Create a Producer/Consumer model with the monitor class. A buffer (in form of a queue) which a producer thread is queueing (from a pre filled dataset of 1 to 10). A consumer thread is dequeueing the buffer and printing its value to the console. Each queue insertion by the producer takes 7 seconds and the dequeuing from the consumer 2.5 seconds. The buffer can only take at any given point a set of 5 values. If the buffer has no values the consumer has to wait. If the buffer is at its limit, the producer has to wait.
214. Whats the difference between the reset events and the monitor approaches to thread signaling? What are the dangers?
215. Take the prior exercise and migrate it to manualResetEvent implementation.
216. When to use concurrent collections? What are the available types?
217. Take the prior exercise and migrate it to concurrent collections.
218. Create an example where you have a csv file with 1000 rows of data. Create a thread for each 100 rows and  process each chunk per thread. The main thread reads the first 100 rows and start new threads. Keep the threads in a thread collection. For each chunk calculate a gender wise count and print it to the console.
219. Migrate the prior exercise to use semaphores.
220. Migrate the prior exercise to use mutex.
221. Migrate the prior exercise to use thread pool.
222. Whats the CountDownEvent primitive?

# Section 32: Tasks
223. What are the drawbacks of Threading?
224. What are the advantages of TPL?
225. Create Task with Task.Run
226. Create a Stopwatch measurement
227. Create an example where we implement 2 tasks and wait for both in the main thread. Use the WaitAll method.
228. Take a prior example and migrate it to Task<\TResult>. What's the difference to Task?
229. What does the Task.WaitOne method does? Create an example.
230. What are the differences between Thread.Sleep and Task.Delay
231. Take the prior example and add a chained continuation task method.
232. What are the possible status on TaskStatus property of the class Task?
232. Create a task with 2 continuations tasks. Make the 2nd continuation task print to console the return value of the original task.
233. What is a cancellation token? Create one example.
234. Create a task1 that writes to file and a task2 that reads from file. The task2 only starts after the task1 finishes. The main thread can be blocked while writing and read operations.

# Section 33: Asynchronous Programming
235. Define Asynchronous Programming
236. Migrate the FileIO exercise to async methods

# Bonus Section: .Net Cli
237. Create a new console application
238. Create a new solution file and a asp.net proj and add the proj to the solution. Build the solution
240. Create 2 csprojs in the same folder, add a ref from one to the other.
241. Create a csproj and add a package to it.
242. Create a tool, add a command to it and then install it and run the command to invoke it.

