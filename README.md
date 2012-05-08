<h1>anchorBits</h1>

<h2>Database back up</h2>

<p>Most of this came from http://davidwalsh.name/backup-mysql-database-php as I am a complete php novice.</p>
<p>To use this, you need to add your database details to this <code>backup_tables('localhost','username','password','database_name');</code> and change this <code> $url = 'url/of/anchor/site/admin';</code> to your admin url.</p>
<p>Next, upload the file to the root AnchorCMS location, then you'll need to add a link in your admin file to run the backup.php like this:</p>
<p><code>&lt;a href="http://yoursite.com/anchor/backup.php" &gt; Back Up DB &lt;/a&gt; </code></p>

<h2>Tiny Editor Integration</h2>

<p>Tiny Editor can be found here http://www.scriptiny.com/2010/02/javascript-wysiwyg-editor/ . </p>
<p>I've just played around with the CSS and the Script to make it fit nicely into my clients sites</p>
<p>Download the files from the link and swap the downloaded style.css with my one, then copy and paste the script from the paste.html file
into your add.php and edit.php files in the style>theme>posts or style>theme>pages folders.  You'll need to change the id in the paste.html 
script to "html" if this is in the edit.php files.</p>
<p>Remember to change the cssfile in the paste.html to read the url of your style.css</p>


==========
