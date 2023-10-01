# Algorithms Deep Dive

In [this](https://github.com/vivekbabu/AlgorithmsTest) project we have a look at various data structures and algorithms used in computer programming. We look at 
- Stacks
- Queues
- Trees
- Graphs

We also look at algorithms like
- Greedy Algorithms
- Dynamic Programming
- DFS & BFS
- Graph Algorithms

## Threads Deep Dive

> Threads are at the centre of great applications
>
> It makes applications look seemless, and makes the life of developer easier

Hence understanding threads is very important for any developer

In [this](https://github.com/vivekbabu/ThreadCourse) repository we try to understand how we can put threads to work

### Understanding Unit Tests

```java
        @Test
	public void isValidLogFileName_ServicesNotInitialized() {
		expectedEx.expect(IllegalStateException.class);
		expectedEx.expectMessage("All dependencies not initialized");
		WebServiceBasedLogAnalyzer analyzer = getLogAnalyzer();
		analyzer.isValidLogFileName("abc.slf");

	}
```
Have we all struggled in understanding how to write good tests to our applications

[This](https://github.com/vivekbabu/UnitTestCourse) repository helps us take the steps towards good unit tests

