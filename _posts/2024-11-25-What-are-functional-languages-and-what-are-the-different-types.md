---
title: What are functional languages and what are the different types?
author: alpa28980
date: Mon, 25 Nov 2024 04:47:46 GMT
categories: ["Development Language"]
tags: ["Functional Languages"]
comment: true
---
Introduction.


Functional programming is a programming paradigm based on pure functions. A pure function is a function that does not depend on external state and always produces the same output for the same input. Functional programming enforces immutability, where the values of variables cannot change, and utilizes higher-order functions, where functions themselves are treated as variables and can be passed as arguments to other functions.

Compared to procedural/object-oriented programming, functional programming has a higher level of abstraction, making it harder to read code, but it doesn't require significant changes to existing data structures. Functional languages are also less popular. However, functional programming has the advantage of being easy to parallelize and test/debug due to its immutability.

Functional programming has strengths in parallelism and debugging through key concepts such as pure functions, immutability, and higher-order functions, but its relative lack of popularity and high level of abstraction are noted as drawbacks.

Immutability.
---.

Immutability is a key concept in functional programming. Immutability means that once a value is defined, it cannot be changed. Instead of changing an existing value, a new value should be created. To achieve this, we use persistent data structures instead of destructive updates.

Immutability has the following advantages

1. It facilitates parallelism. Since the data doesn't change, it's thread-safe and easy to parallelize.
2. Referential transparency is guaranteed. The result of a function is not affected by external state.
3. Easy to debug. Easy to trace state because no data changes.

Examples of immutable data structures include Linked List, Vector, and HashMap. They typically reflect changes by creating new nodes or arrays to preserve the existing data.

Pure functions
-----

A pure function is a key concept in functional programming: a function that does not depend on external state and always produces the same output for the same input. Pure functions have no side effects, meaning they don't change the state of the program. This facilitates parallel programming because it's safe to call pure functions from multiple threads at the same time.

Pure functions are also memoizable, meaning that for the same input, the output is always the same. You can increase performance by storing and recycling the results of previous computations. Functions with side effects, on the other hand, are harder to memoize because their output depends on external state. 4 For example, applying memoization to a recursive function that computes the Fibonacci sequence improves its time complexity from exponential to linear time.

Another advantage of pure functions is that they are easy to test and debug. Because they don't depend on external state, the behavior of a function can be verified in isolation, making it easier to find and fix bugs. On the other hand, functions with side effects depend on external state, which makes them harder to test. As you can see, pure functions are beneficial in many ways, including parallel programming, performance optimization, and testing.

Function synthesis
-----

Function Composition means combining two or more functions to create a new function. This is accomplished by utilizing a Higher-Order Function. A higher-order function is a function that takes or returns a function as an argument.

Function synthesis allows you to solve complex tasks by breaking them down into smaller functions. The behavior of synthesized functions is also easier to predict and easier to test and debug due to the immutability and pure nature of functions.  Finally, function synthesis also contributes to productivity by making your code more modular and reusable.

Function synthesis is a very important concept in functional programming. It allows you to combine smaller functions to solve complex problems, and it has many benefits, including making your code more readable and easier to test. As such, function compositing is one of the core principles of functional programming.

Major functional languages
---------

Major functional programming languages include Lisp, Haskell, Erlang, and Scala.

Lisp is the oldest functional language, developed in 1958, and is well suited for symbolic data processing. It is widely used in fields such as artificial intelligence and compilers.

Haskell is a purely functional language developed in the late 1990s, with a static type system and type inference. It has a strong type system and support for parallel programming, and is used in finance and science.

Erlang was created in 1986 to develop Ericsson telephone exchanges and specializes in distributed systems and parallel programming. It is known for its high fault tolerance and hot-swappability, and is used in telecommunications, financial systems, and more.

Scala is a multi-paradigm language developed in the early 2000s that supports both functional and object-oriented programming. It is JVM-based, highly interoperable with Java, and is used in a variety of fields, including big data processing and web development.

Conclusion.
--.

Functional programming is based on immutability and pure functions, which is advantageous for parallel and concurrent programming, debugging, and unit testing. Higher-order functions and function synthesis allow you to write concise and reusable code, and you can take advantage of various optimization techniques such as memoization and lazy evaluation. However, the high level of abstraction can make it difficult to learn and less productive, and the burden of changing existing data structures to persistent ones can be daunting. The lack of popularity of purely functional languages also limits their use, and changing values can cause performance degradation and garbage collection overhead due to new memory allocations. However, the advantages of functional programming are likely to become more prominent in multi-core CPUs and distributed systems, and it is expected to be used in a variety of fields, including big data, machine learning, and web development. Functional features are gradually being introduced into existing languages, although they are far from becoming a fully mainstream paradigm.
---
---

<iframe src="https://ads-partners.coupang.com/widgets.html?id=807239&template=carousel&trackingCode=AF3190673&subId=&width=680&height=140&tsource=" width="680" height="140" frameborder="0" scrolling="no" referrerpolicy="unsafe-url" browsingtopics></iframe>
해당 링크를 통해 제품 구매가 이루어진 경우 쿠팡 파트너스 활동 일환으로 인해 일정 수수료가 블로거에게 제공되고 있습니다

