<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full STEEM Node Deployment Guide</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; }
        h1, h2 { color: #333; }
        p, li { color: #555; }
        a { color: #007bff; text-decoration: none; }
        a:hover { text-decoration: underline; }
        .important { color: #dc3545; }
        .note { color: #ffc107; }
    </style>
</head>
<body>

<h1>Full STEEM Node Deployment Guide</h1>
<p>This guide outlines the steps required to deploy a full STEEM node using Docker and Docker Compose. The process is streamlined for ease of use across any operating system, provided Docker and Docker Compose are installed.</p>

<img src="URL_TO_STEEM_LOGO" alt="STEEM Logo" style="width: 100px;">
<img src="URL_TO_DOCKER_LOGO" alt="Docker Logo" style="width: 100px;">

<h2>System Requirements</h2>
<ul>
    <li><strong>Operating System:</strong> Any, with Docker and Docker Compose installed</li>
    <li><strong>Storage:</strong> At least 10 TB SSD storage for optimal performance</li>
    <li><strong>Memory:</strong> 512 GB RAM for efficient processing</li>
    <li><strong>CPU:</strong> 64 CORE CPU to handle the workload</li>
</ul>

<h2>Quick Start</h2>
<ol>
    <li>Fork this repository into your system.</li>
    <li>Rename the cloned repository to <code>FULL-NODE</code> and place it under <code>/home</code>.</li>
    <li>Open a terminal and navigate to the <code>FULL-NODE</code> directory.</li>
    <li>Run <code>docker-compose up -d</code> to start all related containers. This will initiate the node to start syncing from block 1.</li>
</ol>

<p class="important">Note: For a faster way to sync blocks, consider downloading block logs from <a href="https://files.steem.fans/">the Steem backup data server</a>.</p>

<p class="note">Feel free to open any issues or merge requests. For more assistance, <a href="https://steemit.com/@krishiv">contact us</a>.</p>

</body>
</html>
