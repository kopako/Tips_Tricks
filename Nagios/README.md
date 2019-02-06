date 06.02.2018

# NagiosCore
or "Where did I suck"

**"How to install the instance"** is well described by official [manuals](https://assets.nagios.com/downloads/nagioscore/docs/nagioscore/4/en/quickstart.html).

What I haven't found so easily is demands on how does _host_definition.cfg_ [should looks like](https://assets.nagios.com/downloads/nagioscore/docs/nagioscore/4/en/objectdefinitions.html#host). 

Those are what they say required fields:
<table border="0" class="Default">
<tr><td colspan=3 class="Definition">define host {</td></tr>
<tr><td>host_name</td><td><i>host_name</i></td></tr>
<tr><td>max_check_attempts</td><td>#</td></tr>
<tr><td>check_period</td><td><i>timeperiod_name</i></td></tr>
<tr><td>contacts</td><td><i>contacts</i></td></tr>
<tr><td>contact_groups</td><td><i>contact_groups</i></td></tr>
<tr><td>notification_interval</td><td>#</td></tr>
<tr><td>notification_period</td><td><i>timeperiod_name</i></td></tr>
<tr><td class="Definition">}&nbsp;&nbsp;&nbsp;&nbsp;</td><td colspan=2></td></tr>
</table>
