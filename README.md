<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reverse Shell PHP Script</title>
</head>

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

<h2>Disclaimer</h2>

<p><strong>Use this script responsibly and only in environments where you have explicit permission to do so. Unauthorized access to computer systems is illegal and unethical.</strong></p>

<h2>Important Notes</h2>

<ul>
<li>The script utilizes features like <code>pcntl_fork</code> and <code>proc_open</code> to enhance its functionality. Ensure that these features are available and enabled on your PHP environment.</li>
<li>The script attempts to daemonize itself for better background execution. If daemonization fails, a warning will be displayed, but the script will continue to run.</li>
<li>For debugging purposes, you can enable the <code>$debug</code> variable in the script to print additional information.</li>
</ul>

<h2>Contributing</h2>

<p>Contributions are welcome! Feel free to submit issues or pull requests.</p>

<h2>License</h2>

<p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

</body>

</html>
