<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"  "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>

</head><body>
<H2>SubscriptionCore</H2>
<table>
<colgroup><col/><col/><col/></colgroup>
<tr><th>Description</th><th>ControlSeverity</th><th>Automated</th></tr>
<tr><td>Minimize the number of admins/owners</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Mandatory central accounts must be present on the subscription</td><td>High</td><td>Yes</td></tr>
<tr><td>Deprecated/stale accounts must not be present on the subscription</td><td>Critical</td><td>Yes</td></tr>
<tr><td>Must not grant access to non-AD/AAD accounts (e.g., Live ID accounts) in the subscription</td><td>High</td><td>Yes</td></tr>
<tr><td>Service accounts cannot support MFA and should not be used for subscription activity</td><td>High</td><td>Yes</td></tr>
<tr><td>There should not be more than 2 classic administrators</td><td>High</td><td>Yes</td></tr>
<tr><td>Use of management certificates is not permitted.</td><td>High</td><td>Yes</td></tr>
<tr><td>Azure Security Center (ASC) must be correctly configured on the subscription</td><td>High</td><td>Yes</td></tr>
<tr><td>Pending Azure Security Center (ASC) alerts must be resolved</td><td>High</td><td>Yes</td></tr>
<tr><td>Pending Azure Security Center (ASC) tasks and recommendations must be resolved</td><td>High</td><td>Yes</td></tr>
<tr><td>Service Principal Names (SPNs) should not be Owners or Contributors on the subscription</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Critical application resources should be protected using a resource lock</td><td>Medium</td><td>Yes</td></tr>
<tr><td>ARM policies should be used to audit or deny certain activities in the subscription that can impact security</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Alerts must be configured for critical actions on subscription and resources</td><td>High</td><td>Yes</td></tr>
<tr><td>Do not use custom-defined RBAC roles</td><td>Medium</td><td>Yes</td></tr>
<tr><td>Do no use any classics resources on a subscription</td><td>High</td><td>Yes</td></tr>
</table>
</body></html>
