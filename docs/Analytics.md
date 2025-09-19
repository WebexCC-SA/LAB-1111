# Lab 10 - Alerts and analytics
Now that we've configured Webex Suite settings, groups, locations, and users, let's explore how to stay informed and proactive by using alerts and analytics.

### Alerts
Alerts in Control Hub are notifications that inform administrators about important events or issues, such as service outages, security events, or license usage. They help you monitor your Webex environment and respond quickly to any concerns.
![Alert Center](template_assets/Alerts.gif)
<table>
  <colgroup>
    <col style="width:40%">
    <col style="width:60%">
  </colgroup>
  <tbody>
    <tr>
      <th>Use case and solution</th>
      <th><a href="http://admin.webex.com/" target="_blank">Control Hub</a> navigation</th>
    </tr>
    <tr>
      <td>
        This is where critical alerts created automatically by Webex services will show. Looks like you’re all caught up for now!
      </td>
      <td>
        <strong><a href="https://help.webex.com/en-us/article/mykour/Alert-Center-in-Control-Hub" target="_blank">Alert Center</a> &gt; Alerts</strong>
      </td>
    </tr>
    <tr>
      <td>
        <p>Let’s look how we can get notification on some that may be of importance to us.</p>
        <p>We’re usually on top of these types of things, but I like all the notifications I can get!</p>
      </td>
      <td>
        <p><strong>Manage &gt; All rules</strong></p>
        <p>SSO IDP Certificate expiry</p>
        <ul>
          <li>Email: Enable – add any email</li>
          <li>Webex space: Enable
            <ul>
              <li><em>This will create a space with the first alert. You could also use an existing space.</em></li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <p>There isn’t a standard rule that meets our needs for devices, so let’s create our own. We’re choosing devices, but note that you can also create rules for Meetings and Calling.</p>
        <p>RoomOS operational alerts in Control Hub inform admins about issues with Cisco RoomOS devices like Webex Boards and Desk, helping quickly detect and fix problems to keep meetings smooth.</p>
        <p>That is – you can avoid those panicked calls from users that join their important meeting that is in 5 minutes!</p>
      </td>
      <td>
        <p><strong>Manage &gt; Create rule</strong></p>
        <ul>
          <li>Service: Devices</li>
          <li>Type – RoomOS operational alerts</li>
          <li>Severity – High</li>
          <li>Title – RoomOS Code Red</li>
          <li>Target – All devices</li>
          <li>Check email</li>
          <li>Add email</li>
          <li>Check Webex space</li>
          <li>Check – 1 to 1 bot</li>
          <li>Add email</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        <p>Review the rule you created or make changes.</p>
      </td>
      <td>
        <p><strong>Manage &gt; My rules</strong></p>
        <p>RoomOS Code Red</p>
      </td>
    </tr>
  </tbody>
</table>

>![Think about it](template_assets/thinkingcat.png) Think about it: What alerts do you need to see in the Alert Center in the mornings while you drink your coffee and for which do you need notifications?
