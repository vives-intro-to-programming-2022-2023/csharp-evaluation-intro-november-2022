
# Test Report LabradorGoesWoof
### Run Summary

<p>
<strong>Overall Result:</strong> ❌ Fail <br />
<strong>Pass Rate:</strong> 0% <br />
<strong>Run Duration:</strong> 1s 216ms <br />
<strong>Date:</strong> 2022-11-19 11:03:49 - 2022-11-19 11:03:51 <br />
<strong>Framework:</strong> .NETCoreApp,Version=v6.0 <br />
<strong>Total Tests:</strong> 2 <br />
</p>

<table>
<thead>
<tr>
<th>✔️ Passed</th>
<th>❌ Failed</th>
<th>⚠️ Skipped</th>
</tr>
</thead>
<tbody>
<tr>
<td>0</td>
<td>2</td>
<td>0</td>
</tr>
<tr>
<td>0%</td>
<td>100%</td>
<td>0%</td>
</tr>
</tbody>
</table>

### Result Sets
#### Tests.dll - 0%
<details>
<summary>Full Results</summary>
<table>
<thead>
<tr>
<th>Result</th>
<th>Test</th>
<th>Duration</th>
</tr>
</thead>
<tr>
<td> ❌ Failed </td>
<td>Tests.UnitTestBarkCounter.TestInvalidFormat<blockquote><details>
<summary>Error</summary>
<strong>Message:</strong>
<pre><code>Assert.Equal() Failure
Expected: -1
Actual:   0</code></pre>
<strong>Stack Trace:</strong>
<pre><code>   at Tests.UnitTestBarkCounter.TestInvalidFormat() in /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/LabradorGoesWoof/Tests/UnitTestBarkCounter.cs:line 28</code></pre>
</details></blockquote>
</td>
<td>5ms</td>
</tr>
<tr>
<td> ❌ Failed </td>
<td>Tests.UnitTestBarkCounter.TestBarkCounter<blockquote><details>
<summary>Error</summary>
<strong>Message:</strong>
<pre><code>Assert.Equal() Failure
Expected: 29
Actual:   0</code></pre>
<strong>Stack Trace:</strong>
<pre><code>   at Tests.UnitTestBarkCounter.TestBarkCounter() in /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/LabradorGoesWoof/Tests/UnitTestBarkCounter.cs:line 13</code></pre>
</details></blockquote>
</td>
<td>< 1ms</td>
</tr>
</tbody>
</table>
</details>

### Run Messages
<details>
<summary>Informational</summary>
<pre><code>
[xUnit.net 00:00:00.00] xUnit.net VSTest Adapter v2.4.3+1b45f5407b (64-bit .NET 6.0.11)
[xUnit.net 00:00:00.43]   Discovering: Tests
[xUnit.net 00:00:00.47]   Discovered:  Tests
[xUnit.net 00:00:00.48]   Starting:    Tests
[xUnit.net 00:00:00.55]       Assert.Equal() Failure
[xUnit.net 00:00:00.55]       Expected: -1
[xUnit.net 00:00:00.55]       Actual:   0
[xUnit.net 00:00:00.55]       Stack Trace:
[xUnit.net 00:00:00.56]         /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/LabradorGoesWoof/Tests/UnitTestBarkCounter.cs(28,0): at Tests.UnitTestBarkCounter.TestInvalidFormat()
[xUnit.net 00:00:00.56]       Assert.Equal() Failure
[xUnit.net 00:00:00.56]       Expected: 29
[xUnit.net 00:00:00.56]       Actual:   0
[xUnit.net 00:00:00.56]       Stack Trace:
[xUnit.net 00:00:00.56]         /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/LabradorGoesWoof/Tests/UnitTestBarkCounter.cs(13,0): at Tests.UnitTestBarkCounter.TestBarkCounter()
[xUnit.net 00:00:00.56]   Finished:    Tests
</code></pre>
</details>

<details>
<summary>Warning</summary>
<pre><code>
</code></pre>
</details>

<details>
<summary>Error</summary>
<pre><code>
[xUnit.net 00:00:00.55]     Tests.UnitTestBarkCounter.TestInvalidFormat [FAIL]
[xUnit.net 00:00:00.56]     Tests.UnitTestBarkCounter.TestBarkCounter [FAIL]
</code></pre>
</details>



----

[Created using Liquid Test Reports](https://github.com/kurtmkurtm/LiquidTestReports)