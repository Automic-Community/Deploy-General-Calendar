*Deploy General Calendar*
=============


This script allows you to deploy the calendar from one node to other remote nodes.
http://github.com/Automic-Community/Deploy-General-Calendar

<!-- List of attached files -->
Contents of Solution Package:

						
								*Dollar_Universe-Deploy_Calendar.zip
								
						


Documenation and Instructions
---

<p><span><strong class="bbc">Goal</strong></span><br /><br />In Dollar Universe v5, deploying the general calendar can't be done directly. This script allows you to deploy the calendar from one node to other remote nodes.<br /><br />This way you can define/Update the calendar on 1 node only then deploy using this script.<br /><br /><span><strong class="bbc">Command Description</strong></span><br /><br />Using this script is simple:</p>
<ul class="bbc">
<li>Make sure uxsetenv is loaded</li>
<li>Execute the script with the list of nodes you want to deploy to</li>
</ul>
<p>Syntax: </p>
<pre class="prettyprint lang-auto linenums:0 prettyprinted"><span class="pln">perl deploy_calendar</span><span class="pun">.</span><span class="pln">pl NODE</span><span class="pun">=&lt;</span><span class="pln">NODES</span><span class="pun">&gt;</span></pre>
<p><br />The node parameter can be:</p>
<ul class="bbc">
<li>One node:
<pre class="prettyprint lang-auto linenums:0 prettyprinted"><span class="pln">perl deploy_calendar</span><span class="pun">.</span><span class="pln">pl NODE</span><span class="pun">=</span><span class="pln">hklpmsup01</span></pre>
</li>
<li>Node patern:
<pre class="prettyprint lang-auto linenums:0 prettyprinted"><span class="pln">perl deploy_calendar</span><span class="pun">.</span><span class="pln">pl NODE</span><span class="pun">=</span><span class="pln">hk</span><span class="pun">*</span></pre>
</li>
<li>All nodes:
<pre class="prettyprint lang-auto linenums:0 prettyprinted"><span class="pln">perl deploy_calendar</span><span class="pun">.</span><span class="pln">pl NODE</span><span class="pun">=*</span></pre>
</li>
</ul>
<p>Note: This is a perl script, it requires perl where it is executed</p>

Copyright and License
---

Solutions, Templates, Actions and other content available on the Automic Marketplace subject to the Automic [Developers Distribution License] (http://automic.com/developers-distribution-license) as well as the Automic Community [Terms of Service] (http://automic.com/community-terms-of-service).
Automic does not support, maintain or warrant any content submitted by the Automic Community.



Questions or Need Help? 
---
Any questions or comments? Converse with your fellow Users in the [Automic Community] (https://community.automic.com).