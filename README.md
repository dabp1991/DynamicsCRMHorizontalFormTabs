
# dynamics365formTabs
A web resource that adds horizontal form tabs to a given form in dynamics crm older than CRM 2016.  

<h2>Prerequisites</h2>
<div>
<p>For the web ressource to work it needs Jquery and XrmServiceToolkit.  </p>
<p>While jquery is downloaded through a cdn, XrmServiceToolkit can be downloaded  <a href="https://github.com/XrmServiceToolkit/XrmServiceToolkit">here</a>. </p>
<p>The toolkit should then be added to CRM as a web resource and we are ready for implementation.</p>
</div>
<h2>Implementation</h2>
<div>
<ol>
<li> Rename the toolkit script source in the head of the web ressource, so that it matches the source name of your toolkit web ressource. </li>
<li>Create a new tab on (fx. menu) and add an iframe to it, with the formtab as the resource</li>
<li>Make sure to uncheck the "Show the label of this tab on the form" on all the tabs, so that the normal tab function doesn't display</li>
<li>Rename the tab names to match the name of the label (the "Name" of the tab is used as the label of the tab)</li>
<li>Publish the changes and you now got horizontal tabs</li>
</ol>
</div>

