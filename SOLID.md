<h1>SOLID Principles<h1>

<h2><b>S – Single Responsibility Principle – SRP – (most important for clean code)</b></h2>
<p>&nbsp;&nbsp; - <b>Cohesion</b></p> 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•	“Every software component should have one and only one responsibility.”;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•	Cohesion is the degree to which the various parts of a software component are related;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•	High cohesion helps attain better adherence to the Single Responsibility Principle;</p>
<p>&nbsp;&nbsp; -	<b>Coupling</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	“Coupling is defined as the level of inter dependency between various software components”;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Loose coupling helps attain better adherence to the Single Responsibility Principle;</p>
<p>&nbsp;&nbsp; -<b>Reason for Change</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	“Every software component should have one and only one reason  to change.” – Uncle Bob;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	“The only thing that is constant is change.” – Heraclitus: in other words, change is inevitable, this apply to software as well, software is never dormant is always changing;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	If a software component has multiple reasons to change then the frequency of changes to it will increase, every change to a software component opens up the possibility of introducing bugs into the software.</p>
<p>&nbsp;&nbsp;<b>O – Open-Close Principle – OCP – (most important for clean code)</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	“Software components should be closed for modification, but open for extension”;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Closed for modification means, new feature getting added to the software component should not have to modify existing code;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Open for extension means, a software component should be extendable to add a new feature or toad a new behavior to it;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Following OCP and SRP can lead to cost benefits in the long run;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	OCP and SRP can work together to achieve a better design;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Do not apply OCP blindly and introduce unwanted complexity to your code;</p>
<p>&nbsp;&nbsp;<b>L – Liskov Substitution Principle - LSP</b></p>
<p>&nbsp;&nbsp;“Object should be replaced with their subtypes without affecting the correctness of the program”</p>
<p>&nbsp;&nbsp;Change “Is A” way of thinking;</p>
<p>&nbsp;&nbsp;“If it sounds like a duck quack’s like a duck but it needs batteries, you probably have the wrong abstraction!”;</p>
<p>&nbsp;&nbsp;It helps us to model good inheritance hierarchies;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp; - <b>Breaking the Hierarchy</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp; -	<b>Tell, Don’t Ask</b></p>
<p>&nbsp;&nbsp;<b>I – Interface Segregation Principle – ISP</b></p>
<p>&nbsp;&nbsp;“Many client-specific interfaces are better than one general purpose interface”;</p>
<p>&nbsp;&nbsp;“No client should be forced to depend on methods it does not use”;</p>
<p>&nbsp;&nbsp; -	<b>Restructuring the code to follow ISP</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Split the big interface into smaller interface</p>
<p>&nbsp;&nbsp;<b>-	Techniques to Identify Violations</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	FAT interfaces: having high number of methods;</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Low Cohesion interfaces;</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Empty Methods Implementation:  blank implementations of interface methods is almost always a violation of the Interface Segregation Principle.</p>
<p>&nbsp;&nbsp;<b>D – Dependency Inversion Principle – DIP</b></p>
<p>&nbsp;&nbsp;“You should depend upon abstractions, not concretions.”;</p>
<p>&nbsp;&nbsp;“High-Level modules should not depend on low-level modules. Both should depend on abstractions.”;</p>
<p>&nbsp;&nbsp;“Abstractions should not depend on details. Details should depend on abstractions”;</p>
<p>&nbsp;&nbsp;<b>-	Dependency Injection</b></p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Is a design pattern in which an object or function receives other objects or functions that is depends on;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	It completely dissociates a class for going out and getting its dependencies instantiated;</p>
<p>&nbsp;&nbsp;<b>-	Inversion of Control – IoC</b><p>
<p>&nbsp;&nbsp;“IoC inverts the flow of control as compared to traditional control flow.”;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;•	Spring framework;</p>
