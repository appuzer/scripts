<pre><code>
lmsManager.setValue("cmi.success_status", "passed");
lmsManager.setValue("cmi.completion_status","completed");
lmsManager.setValue("adl.nav.request", "exitAll");
closedCourse = true;
window.opener.closedCourse = true;
lmsManager.commit();
lmsManager.terminate2();
</code></pre>
