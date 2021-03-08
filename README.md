# OOPs_Assignment_2

In this project I solved the problem which is :

Make a trait Queue which performs two functions of enqueue and dequque.
* Two classes: DoubleQueue and SquareQueue mix in this trait.
* You may use List for the implementation and keep both the classes in the same file with proper packaging.

DoubleQueue enqueues the element after doubling them
SquareQueue enqueues the element after squaring them
dequeue method will remove the first element from the queue(having concrete definition in trait Queue).

So, according to above problem I created  following scala file:-

*A Trait class(Queue.scala) to implement the methods(dequeue and enqueue):-
		where:
			-enqueue is an abstract method
			-dequeue is an concrete method.

*Two scala classes(DoubleQueue, SquareQueue) in a module(classes) both class extend the Queue trait:-
		where:
			-DoubleQueue enqueues the element after doubling them
			-SquareQueue enqueues the element after squaring them

