<body>

<h1>Reverse Shell PHP Script</h1>

<p>This repository contains a PHP script that establishes a reverse shell connection. It is designed for educational and testing purposes only. The script allows remote access to a system over a network.</p>

<h2>Usage</h2>

<ol>
<li>
<strong>Modify Configuration:</strong>
<ul>
<li>Open the script (<code>reverse_shell.php</code>) in a text editor.</li>
<li>Update the <code>$ip</code> and <code>$port</code> variables with the desired IP address and port number for the reverse shell connection.</li>
<li>Optionally, adjust other configuration parameters as needed.</li>
</ul>
</li>
<li>
<strong>Run the Script:</strong>
<ul>
<li>Execute the script on the target system where you want to establish a reverse shell connection.</li>
</ul>
</li>
<li>
<strong>Establish Connection:</strong>
<ul>
<li>Once the script is running, it will attempt to connect back to the specified IP address and port.</li>
<li>A successful connection will open a shell session, allowing remote interaction with the target system.</li>
</ul>
</li>
</ol>

<h2>How to Connect</h2>

<p>After running the script on the target system, use the following steps to connect to the reverse shell:</p>

<ol>
<li>Open a terminal on your local machine.</li>
<li>Use the following command to connect to the target system:</li>
</ol>

<pre><code>nc -lvnp YOUR_PORT</code></pre>

<p>Replace  <code>YOUR_PORT</code> with the IP address and port number configured in the script.</p>

</body>

</html>
