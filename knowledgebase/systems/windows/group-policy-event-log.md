# Group Policy Event Log Analysis

When shit hits the fan and your GPOs start getting flaky and don’t get
applied, worry not for here is a list of event codes to troubleshoot your
issue. Most certainly, you’ll find the source of your issue in one of these.

## *But I'm lazy or* ... <insert whatever reason here>

Sure thing, just paste this into your event viewer.

```
4000-4007,4016-4299,5000-6007,6017-7007,7017-8007
```

Or if you’re more the PowerShell kind of guy, [no luck](https://github.com/PowerShell/PowerShell/issues/12303), you simply can’t put
that many IDs in a single query for now.


## The actual list

<table>
<tr><th>Event ID Range</th><th>Description</th></tr>
<tr><td>4000–4007</td><td>Group Policy start events: These informational events appear in the event log when an instance of Group Policy processing begins.</td></tr>
<tr><td>4016–4299</td><td>Component start events: These informational events appear in the event log when a component of Group Policy processing begins the task described in the event.</td></tr>
<tr><td>5000–5299</td><td>Component success events: These informational events appear in the event log when a component of Group Policy processing successfully completes the task described in the event.</td></tr>
<tr><td>5300–5999</td><td>Informative events: These informational events appear in the event log during the entire instance of Group Policy processing and provide additional information about the current instance.</td></tr>
<tr><td>6000–6007</td><td>Group Policy warning events: These warning events appear in the event log when an instance of Group Policy processing completes with errors.</td></tr>
<tr><td>6017–6299</td><td>Component warning events: These warning events appear in the event log when a component of Group Policy processing completes the task described in the event with errors.</td></tr>
<tr><td>6300–6999</td><td>Informative warning events: These warning events appear in the event log to provide additional information about possible error conditions with the action described in the event.</td></tr>
<tr><td>7000–7007</td><td>Group Policy error events: These error events appear in the event log when the instance of Group Policy processing does not complete.</td></tr>
<tr><td>7017–7299</td><td>Component error events: These error events appear in the event log when a component of Group Policy processing does not complete the task described in the event.</td></tr>
<tr><td>7300–7999</td><td>Informative error events: These error events appear in the event log to provide additional information about the error condition with the action described in the event.</td></tr>
<tr><td>8000–8007</td><td>Group Policy success events: These informational events appear in the event log when the instance of Group Policy completes successfully.</td></tr>
</table>
