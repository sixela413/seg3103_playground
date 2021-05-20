<h1>Lab01</h1>

| Outline | Value |
| --- | --- |
| Name | Alexis Verana |
| Course | SEG 3103 |
| Date | Summer 2021 |
| Professor | Andrew Forward, aforward@uottawa.ca |
| TA | Zahra Kakavand, zkaka044@uottawa.ca |

<h1>Deliverables</h1>
<ul>
  <li>https://github.com/sixela413/seg3103_playground</li>
  <li>Shared repo above with TA and Professors
</li>
 </ul>
 
<h2>Java</h2>
<p>I am running Java version 16.0.1</p>
<p><img src="/lab01/assets/java_install.jpg" width="350">
INSERT PIC

<p>The first step to run the program was to compile it using:</br>
<code>javac -encoding UTF-8 --source-path src -d dist src/*.java</code>
</p>

<p>The command used to run the program was:<br>
<code>java -cp ./dist Main</code>
</p>

<p>Here is an putput of the running program:</br>
<pre>
Newmath (type 'exit' to exit program)
Numerator: 13
Denominator: 3
13 / 3 = 4
Numerator: exit</pre>
</p>

<p>A screenshot of the terminal:</p>
INSERT PIC

<h2>JUnit</h2>
<p>I am working with JUnit 5 (via Console standalone 1.7.1)</p>

<p>To run JUnit, I need to compile the application (see above), and then compile the test code:<br>
<code>javac -encoding UTF-8 --source-path test -d dist -cp dist;lib/junit-platform-console-standalone-1.7.1.jar test/*.java</code>
</p>

<p>To run the tests, the command use:<br>
<code>java -jar lib/junit-platform-console-standalone-1.7.1.jar --class-path dist --scan-class-path</code>
</p>

<p>The output of the tests:<br>
<pre>
INSERT CODE
</pre>
</p>

<p>Screenshot of output from the terminal:</p>
INSERT PIC

<h2>Elixir</h2>
<p>I am running Elixir 11.4 with Erlang 21<br>
  INSERT PIC
</p>

<p>To run the Elixir program (in <code>newmath_ex</code>, first I compile it:<br>
<code>mix compile</code>
</p>

<p>Then I run it using:<br>
  <code>iex -S mix</code>
</p>

<p>Here is an output of the running program:<br>
<pre> 
</pre>
</p>

<p>Screenshot of output from the terminal:</p>

<h2>ExUnit</h2>
<p>ExUnit is built directly into Elixir (and compiled like above with <code>mix compile</code>)</p>

<p>To run the tests:<br>
  <code>mix test</code>
</p>
  
<p>The output of the tests:<br>
 <pre>
 </pre>
</p>

<p>Screenshot of output from the terminal:</p>




