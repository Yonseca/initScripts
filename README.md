<h1>initScripts</h1>
Some (maybe) useful init scripts, ready to use. 

<h2>Instructions:</h2> 
<ol>
<li>Just put them on your <code>/etc/init.d/</code> folder</li>
<li>Check which Linux distro are you using</li>
    <ol>
	<li>If you're on Debian:
	    <ol>
		<li>Execute <code>update-rc.d scriptName defaults</code><sup>1</sub>
	    </ol>
	</li>
	<li>If you're on Fedora:
	    <ol>
		<li>Execute <code>chkconfig --add scriptName</code><sup>2</sub></li>
		<li>Execute <code>chkconfig --level 2345 scriptName on</code><sup>2</sub></li>
	    </ol>
	</li>
    </ol>
<li>PROFIT!!</li>
</ol>

<hr>
<h2>References</h2>
<sup>1</sup> <a href=https://www.debian-administration.org/article/28/Making_scripts_run_at_boot_time_with_Debian>Article from debian-administration</a><br>
<sup>2</sup> <a href=http://unix.stackexchange.com/a/20361>Answer on StackExchange</a>
