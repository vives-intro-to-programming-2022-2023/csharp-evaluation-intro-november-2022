
# Test Report RateMySetup
### Run Summary

<p>
<strong>Overall Result:</strong> ❌ Fail <br />
<strong>Pass Rate:</strong> 0% <br />
<strong>Run Duration:</strong> 1s 233ms <br />
<strong>Date:</strong> 2022-11-19 11:03:17 - 2022-11-19 11:03:18 <br />
<strong>Framework:</strong> .NETCoreApp,Version=v6.0 <br />
<strong>Total Tests:</strong> 4 <br />
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
<td>4</td>
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
<td>Tests.UnitTestRatingGenerator.TestAbnormalSizes<blockquote><details>
<summary>Error</summary>
<strong>Message:</strong>
<pre><code>Assert.Equal() Failure
          ↓ (pos 0)
Expected: <>
Actual:   
          ↑ (pos 0)</code></pre>
<strong>Stack Trace:</strong>
<pre><code>   at Tests.UnitTestRatingGenerator.TestAbnormalSizes() in /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/RateMySetup/Tests/UnitTestRatingGenerator.cs:line 38</code></pre>
</details></blockquote>
</td>
<td>3ms</td>
</tr>
<tr>
<td> ❌ Failed </td>
<td>Tests.UnitTestRatingGenerator.TestBasic5StarRating<blockquote><details>
<summary>Error</summary>
<strong>Message:</strong>
<pre><code>Assert.Equal() Failure
          ↓ (pos 0)
Expected: <_____>
Actual:   
          ↑ (pos 0)</code></pre>
<strong>Stack Trace:</strong>
<pre><code>   at Tests.UnitTestRatingGenerator.TestBasic5StarRating() in /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/RateMySetup/Tests/UnitTestRatingGenerator.cs:line 11</code></pre>
</details></blockquote>
</td>
<td>< 1ms</td>
</tr>
<tr>
<td> ❌ Failed </td>
<td>Tests.UnitTestRatingGenerator.TestRatingSymbol<blockquote><details>
<summary>Error</summary>
<strong>Message:</strong>
<pre><code>Assert.Equal() Failure
          ↓ (pos 0)
Expected: <___>
Actual:   
          ↑ (pos 0)</code></pre>
<strong>Stack Trace:</strong>
<pre><code>   at Tests.UnitTestRatingGenerator.TestRatingSymbol() in /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/RateMySetup/Tests/UnitTestRatingGenerator.cs:line 30</code></pre>
</details></blockquote>
</td>
<td>< 1ms</td>
</tr>
<tr>
<td> ❌ Failed </td>
<td>Tests.UnitTestRatingGenerator.TestRatingSize<blockquote><details>
<summary>Error</summary>
<strong>Message:</strong>
<pre><code>Assert.Equal() Failure
          ↓ (pos 0)
Expected: <___>
Actual:   
          ↑ (pos 0)</code></pre>
<strong>Stack Trace:</strong>
<pre><code>   at Tests.UnitTestRatingGenerator.TestRatingSize() in /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/RateMySetup/Tests/UnitTestRatingGenerator.cs:line 22</code></pre>
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
[xUnit.net 00:00:00.44]   Discovering: Tests
[xUnit.net 00:00:00.48]   Discovered:  Tests
[xUnit.net 00:00:00.49]   Starting:    Tests
[xUnit.net 00:00:00.56]       Assert.Equal() Failure
[xUnit.net 00:00:00.57]                 ↓ (pos 0)
[xUnit.net 00:00:00.57]       Expected: <>
[xUnit.net 00:00:00.57]       Actual:   
[xUnit.net 00:00:00.57]                 ↑ (pos 0)
[xUnit.net 00:00:00.57]       Stack Trace:
[xUnit.net 00:00:00.57]         /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/RateMySetup/Tests/UnitTestRatingGenerator.cs(38,0): at Tests.UnitTestRatingGenerator.TestAbnormalSizes()
[xUnit.net 00:00:00.58]       Assert.Equal() Failure
[xUnit.net 00:00:00.58]                 ↓ (pos 0)
[xUnit.net 00:00:00.58]       Expected: <_____>
[xUnit.net 00:00:00.58]       Actual:   
[xUnit.net 00:00:00.58]                 ↑ (pos 0)
[xUnit.net 00:00:00.58]       Stack Trace:
[xUnit.net 00:00:00.58]         /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/RateMySetup/Tests/UnitTestRatingGenerator.cs(11,0): at Tests.UnitTestRatingGenerator.TestBasic5StarRating()
[xUnit.net 00:00:00.58]       Assert.Equal() Failure
[xUnit.net 00:00:00.58]                 ↓ (pos 0)
[xUnit.net 00:00:00.58]       Expected: <___>
[xUnit.net 00:00:00.58]       Actual:   
[xUnit.net 00:00:00.58]                 ↑ (pos 0)
[xUnit.net 00:00:00.58]       Stack Trace:
[xUnit.net 00:00:00.58]         /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/RateMySetup/Tests/UnitTestRatingGenerator.cs(30,0): at Tests.UnitTestRatingGenerator.TestRatingSymbol()
[xUnit.net 00:00:00.58]       Assert.Equal() Failure
[xUnit.net 00:00:00.58]                 ↓ (pos 0)
[xUnit.net 00:00:00.58]       Expected: <___>
[xUnit.net 00:00:00.58]       Actual:   
[xUnit.net 00:00:00.58]                 ↑ (pos 0)
[xUnit.net 00:00:00.58]       Stack Trace:
[xUnit.net 00:00:00.58]         /home/runner/work/csharp-evaluation-intro-november-2022/csharp-evaluation-intro-november-2022/RateMySetup/Tests/UnitTestRatingGenerator.cs(22,0): at Tests.UnitTestRatingGenerator.TestRatingSize()
[xUnit.net 00:00:00.58]   Finished:    Tests
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
[xUnit.net 00:00:00.56]     Tests.UnitTestRatingGenerator.TestAbnormalSizes [FAIL]
[xUnit.net 00:00:00.57]     Tests.UnitTestRatingGenerator.TestBasic5StarRating [FAIL]
[xUnit.net 00:00:00.58]     Tests.UnitTestRatingGenerator.TestRatingSymbol [FAIL]
[xUnit.net 00:00:00.58]     Tests.UnitTestRatingGenerator.TestRatingSize [FAIL]
</code></pre>
</details>



----

[Created using Liquid Test Reports](https://github.com/kurtmkurtm/LiquidTestReports)