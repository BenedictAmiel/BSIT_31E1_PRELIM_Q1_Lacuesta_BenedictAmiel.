Why did you use inheritance?
I used inheritance to allow one class to reuse the properties and methods of another class, which reduces code duplication

2. Why did you use interfaces?
I used interfaces so that different classes can share the same behaviors even if they are not related by inheritance.

3. Could Helicopter inherit from both Vehicle and Airplane? Why or why not?
No. A class can only inherit from one parent class, so it cannot inherit from two classes at the same time.

4.Why can Helicopter implement both IFlyable and IDriveable?
A class can implement multiple interfaces, allowing it to support both flying and driving behaviors.

5. If a Submarine can both sail and dive, how would you design it?
I would have Submarine inherit from Vehicle and implement the ISailable and IDiveable interfaces.
