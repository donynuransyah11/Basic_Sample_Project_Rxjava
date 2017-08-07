Basic_Sample_Project_Rxjava


Before creating your first observable, What is Reactive Programming ?
+---------------------------------+
int a = 2;
int b = 3;
int c = a * b; // c is 6

a = 10;
// c is still 6
+---------------------------------+

reactive programming is all about responding to value changes.
RxJava makes use of the Observer pattern.
In the Observer pattern, We have objects that implement two key RxJava interfaces: 
1. Observable
2. Observer. 

When an Observable changes state, all Observer objects subscribed to it are notified
Among the methods in the Observable interface is subscribe(), which an Observer will call to begin the subscription.
