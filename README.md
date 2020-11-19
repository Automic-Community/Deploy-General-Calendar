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

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
