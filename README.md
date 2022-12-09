# CleanCode
Some rules to apply when coding having a clean code mind set !

<h1>Clean Code Rules</h1>
<h2><bold>Naming</bold></h2>
<p>&nbsp;&nbsp;Use <b>descriptive and meaningful names.</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Variables & Properties:</b>&nbsp;&nbsp;nouns or short phrases with adjectives;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Functions & Methods:</b>&nbsp;&nbsp;verbs or short phrases with adjectives;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Classes:</b>&nbsp;&nbsp;Nouns</p>
<p>&nbsp;&nbsp;Be as<b>specific</b> as necesary and possible but don't be redundant;</p>
<p>&nbsp;&nbsp;Use<b>yes/no</b> question for booleans(e.g. isValid);</p>
<p>&nbsp;&nbsp;<b>Avoid misleading, slang, unknown abbreviations </b>with your names;</p>
<p>&nbsp;&nbsp;Be<b>consistent</b> with your names (e.g. stick to get... instead of fetch... )</p>
<h2>Comments Formatting</2>
<p>&nbsp;&nbsp;<b>Most comments are bad - </b>avoid them as much as you can!;</p>
<p>&nbsp;&nbsp;Some good comments are<b> acceptable</b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Legal</b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Warnings</b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Helpful explinations</b> (e.g. for Regex);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Todos</b>(don't overdo it);</p>
<p>&nbsp;&nbsp;Use <b>vertical<b> formating:</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Keep related concepts close to each other <b>(vertical density)</b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Add spacint/distance(e.g. blank lines) between concepts that are not directly related <b>(vertical distance)</b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Write code<b> top  to bottom</b>: called functions should come below calling functions (if possible);</p>
<p>&nbsp;&nbsp;Use <b>horizontal</b> formating:</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Avoid long lines </b>- break them into multiple lines instead;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Use <b>indentation</b> to express scope;</p>
<h2>Functions</2>
<p>&nbsp;&nbsp;<b>Limit the number of parameters</b> your functions use - less is better !;</p>
<p>&nbsp;&nbsp;Consider using objects, dictionaries or arrays to <b>group multiple parameters into one parameter<b>;</p>
<p>&nbsp;&nbsp;Functions should be <b>small and do one thing<b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Levels of abstraction inside the function body should be <b>one level bleow the level implied by the function name</b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Avoid mixing levels</b> of abst1raction in functions;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;But: <b>avoid redundent splitting! </b>;</p>
<p>&nbsp;&nbsp;Stay <b>DRY</b> (Don't repeat yourself!)</p>
<p>&nbsp;&nbsp;<b>AVOID unexpected side effects !</b>/p> 
<h2>Control Structures & Errors</2>
<p>&nbsp;&nbsp;Prefer <b> positive checks</b>;</p>
<p>&nbsp;&nbsp;Avoid <b>deep nesting</b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Consider using <b>"Guard"</b> statements;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;Consider using <b>polimorfism</b> & <b>factory functions</b>;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;<b>Extract control structures </b>into separate functions;</p>
<p>&nbsp;&nbsp;Consider using <b>"real" errors</b> (with error handling) instead of "synthetic errors" build with if statements;</p>  
<h2>Objects&Classes</2>
<p>&nbsp;&nbsp;Focus on building <b>"real objects"</b> or <b>data containers/structures</b>;</p>
<p>&nbsp;&nbsp;Build <b>small classes</b> - focus on a <b>single responsibility</b>(which does not mean "single method");</p>
<p>&nbsp;&nbsp;Build classes with <b>high cohesion</b>;</p>
<p>&nbsp;&nbsp;Follow the <b>"Low of Demeter"</b> for <b>"real objects"</b>(avoid this.customer.lastPurchase.date);</p>
<p>&nbsp;&nbsp;Especially when doing <B>OOP</B> follow the <b>SOLID Principles</b>;</p>
<p>&nbsp;&nbsp;Especially <b>SRP</b> and <b>OCP</b> will help a lot with writing clean code (=human readable code);</p>
