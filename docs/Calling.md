# Lab 6 - Calling

[Calling setting defaults](template_assets/CallingSettings.pdf){:target="_blank"}: Opens in a new tab<br>
## Service settings
<table>
  <thead>
    <tr>
      <th style="width: 40%;">Use Case & Solution</th>
      <th style="width: 60%;"><a href="http://admin.webex.com/" target="_blank">Control Hub</a> &gt; Services &gt; Calling &gt; Service settings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="width: 40%;">Employees have complained about the number of spam calls they receive.<br>   <ul>
                <li> Create a call block list.</li>
                </ul>
      </td>
      <td style="width: 60%;">
        <p><strong>Call Block List</strong></p>
        <ul>
          <li>Enable: Block calls from hidden/private numbers</li>
        </ul>
      </td>
    </tr>
    <tr>
       <tr>
      <td style="width: 40%;">Enabling call recording announcements ensures call participants are informed, supporting legal compliance and transparency.   <br><br> Local laws require all emergency calls be recorded.<ul>
                <li> Turn on compliance announcements and emergency call recording.</li>
                </ul>
      </td>
      <td style="width: 60%;">
        <p><strong>Call Recording</strong></p>
        <ul>
          <li>Compliance announcements: Enable play announcement for inbound and outbound PSTN calls</li>
          <li>Record emerency calls: Enable</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="width: 40%;">IT security policies dictate that voicemail passcodes be reset at a regular interval.<br>   <ul>
                <li> Set the time period for passcode expiration.</li>
                </ul>
      </td>
      <td style="width: 60%;">
        <p><strong>Voicemail</strong></p>
        <ul>
          <li>Set the number of days after which passcode expires to 30</li>
        </ul>
      </td>
    </tr>
      <td style="width: 40%;">To reduce security risk and data breech concerns, contractors do not need voicemail.<br><br>
      For training and compliance, all employee calls should be recorded.<br><ul><br>
                <li> Disable voicemail for contractors and enable call recording for all employees.</li>
                </ul>
      </td>
      <td style="width: 60%;">
        <strong>Manage User Calling Data</strong>
            <p>Bulk change Webex Application access and voicemail enablement for Contractors</p>
            <ul>
              <li>All Locations &gt; Download Data</li>
              <li>Specific user data for download:</li>
              <ul>
                <li>Voicemail</li>
              </ul>
              <li>Once download is initiated, go to <i>View upload history tasks</i> to download the most recent file</li>
              <br>
              <li>Edit the CSV file</li>
              <li>Users: esteele, smauk, kmelby</li>
              <ul>
                <li>Column B: Voicemail enabled – FALSE</li>
            
              </ul>
              <li>All employees</li>
              <ul>
                <li>Column GP Call Recording enabled TRUE</li>
              </ul>
              <li>Upload CSV file. You should see that 8 records have been udpated.</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="width: 40%;">Spot check your import</td>
      <td style="width: 60%;">
        <strong>Management &gt; Users &gt; Kellie Melby &gt; Calling</strong>
           Confirm the following:<ul>
              <li>Voicemail: disabled</li>
              <li>User calling experience: Call Recording: enabled</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## Client settings and template
<table>
  <thead>
    <tr>
      <th style="width: 40%;"><strong>Use Case & Solution</strong></th>
      <th style="width: 60%;"><strong><a href="http://admin.webex.com/" target="_blank">Control Hub</a> &gt; Services &gt; Calling &gt; Client settings</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="width: 40%;">Company policy dictates that users cannot block their caller id or manage any of their voicemail settings in the Webex App and/or User Hub (user.webex.com)  <ul><br>
                <li> Remove caller ID and voicemail settings from User Hub.</li>
                </ul></td>
      <td style="width: 60%;">
        <p><strong>Hide Calling Settings</strong></p>
        <ul>
          <li>Call Settings: Disable Block caller ID</li>
          <li>Voicemail: Disable all</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="width: 40%;">Contractors should not be able to share content or request/give remote control of shared content.  <ul><br>
                <li> Change sharing settings using a template for the contractors.</li>
                </ul></td>
      <td style="width: 60%;">
        <p><strong>Templates &gt; Create template</strong></p>
        <ul>
          <li>Template name: Disable Sharing</li>
          <li>Disable:
          <ul><li>Request remote control</li>
          <li>Give remote control</li>
          <li>Screen sharing</li>
          </ul><li>Apply template to PPS Contractor group</li>
      </td>
    </tr>
  </tbody>
</table>


>![Think About It](template_assets/thinkingcat.png) Think about it: What settings would you change for your organization? What groups might need restrictions?


