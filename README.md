<h1>Nmap Automation Tool</h1>

<p>This is a simple Python script that serves as an automation tool for Nmap, a powerful network scanning tool.
The script utilizes the <code>nmap</code> library to perform scans on a specified IP address.</p>

<h2>Usage</h2>

<ol>
<li><strong>Clone the Repository:</strong></li>
<pre><code>git clone https://github.com/your-username/nmap-automation-tool.git</code></pre>

<li><strong>Navigate to the Project Directory:</strong></li>
<pre><code>cd nmap-automation-tool</code></pre>

<li><strong>Run the Script:</strong></li>
<pre><code>python3 nmap_automation.py</code></pre>
</ol>

<h2>Features</h2>

<ul>
<li>SYN ACK Scan</li>
<li>UDP Scan</li>
<li>Comprehensive Scan</li>
</ul>

<h2>How to Use</h2>

<ol>
<li>Enter the target IP address when prompted.</li>

<li>Select the type of scan you want to run:
<ul>
    <li>SYN ACK Scan</li>
    <li>UDP Scan</li>
    <li>Comprehensive Scan</li>
</ul>
</li>

<li>View the scan results, including:
<ul>
    <li>Nmap version</li>
    <li>Scan information</li>
    <li>Scanner status</li>
    <li>Open ports</li>
</ul>
</li>
</ol>

<h2>Example</h2>

<pre><code>
Please enter the IP address you want to scan: 192.168.1.1

Please enter the type of scan you want to run:
1) SYN ACK Scan
2) UDP Scan
3) Comprehensive Scan

You have selected option: 1
nmap version: &lt;nmap version details&gt;

{'tcp': {'services': '1-1024', 'method': 'syn-ack'}}
Scanner Status: up
['tcp']
Open Ports: dict_keys([&lt;open ports&gt;])
</code></pre>

<p><strong>Note:</strong> Make sure to install the required library using:</p>
<pre><code>pip install python-nmap</code></pre>

<p>Feel free to contribute or provide feedback!</p>

</body>

</html>
