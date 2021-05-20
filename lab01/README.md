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
Thanks for using JUnit! Support its development at https://junit.org/sponsoring

←[36m.←[0m
←[36m+--←[0m ←[36mJUnit Jupiter←[0m ←[32m[OK]←[0m
←[36m| '--←[0m ←[36mNewmathTest←[0m ←[32m[OK]←[0m
←[36m|   +--←[0m ←[34mdiv_ok()←[0m ←[32m[OK]←[0m
←[36m|   '--←[0m ←[34mdiv_by_zero()←[0m ←[32m[OK]←[0m
←[36m'--←[0m ←[36mJUnit Vintage←[0m ←[32m[OK]←[0m

Test run finished after 212 ms
[         3 containers found      ]
[         0 containers skipped    ]
[         3 containers started    ]
[         0 containers aborted    ]
[         3 containers successful ]
[         0 containers failed     ]
[         2 tests found           ]
[         0 tests skipped         ]
[         2 tests started         ]
[         0 tests aborted         ]
[         2 tests successful      ]
[         0 tests failed          ]
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
<pre>Interactive Elixir (1.11.4) - press Ctrl+C to exit (type h() ENTER for help)
iex(1)> NewmathEx.
...(1)> MixProject
NewmathEx.MixProject
iex(2)> NewmathEx.div(13,4)
{:ok, 3.25}
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
Finished in 0.09 seconds
1 doctest, 2 tests, 0 failures

Randomized with seed 935000
 </pre>
</p>

<p>Screenshot of output from the terminal:</p>




