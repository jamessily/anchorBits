<h1>anchorBits</h1>

<h2>Database back up</h2>

<p>Most of this came from http://davidwalsh.name/backup-mysql-database-php as I am a complete php novice.</p>
<p>To use this, you need to add your database details to this <code>backup_tables('localhost','username','password','database_name');</code> and change this  $url = 'url/of/anchor/site/admin'; to your admin url.</p>
<p>Next, upload the file to the root AnchorCMS location, then you'll need to add a link in your admin file to run the backup.php like this:</p>
<p><code>&lt;a href="http://yoursite.com/anchor/backup.php" &gt; Back Up DB &lt;/a&gt; </code></p>




==========
