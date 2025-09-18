# Lab 6 - Calling

Webex Calling provides a robust set of features to enhance your organization's communication, and it’s all in the cloud.  In this lab, you'll review and optimize key Webex Calling service settings, then adjust client-specific settings as needed. Finally, you'll import and apply feature changes for your Calling users to ensure the best experience across your organization. 

The [Calling settings chart](template_assets/CallingSettings.pdf){:target="_blank"} shows which Calling settings are set by default and which you can change for groups using a template or bulk tools to override. Use it as a quick reference to see default settings versus customizable options to fit your organization’s needs.
## Service settings
<table>
  <thead>
    <tr>
      <th style="width: 40%;">Use Case & Solution</th>
      <th style="width: 60%;"><a href="http://admin.webex.com/" target="_blank">Control Hub</a> &gt; Services &gt; Calling &gt; Service settings</th>
    </tr>
  </thead>
  <tbody><tr><td colspan="2;"><i>Note: Most individual settings require clicking save before moving to the next setting.</i></td></tr>
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
      <td style="width: 40%;">Enabling call recording announcements ensures call participants are informed, supporting legal compliance and transparency. Local laws require all emergency calls be recorded.<ul><br>
                <li> Turn on compliance announcements and emergency call recording.</li>
                </ul>
      </td>
      <td style="width: 60%;">
        <p><strong>Call Recording</strong></p>
        <ul>
          <li>Compliance announcements: Enable play announcement for inbound and outbound PSTN calls</li>
          <li>Record emergency calls: Enable</li>
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
      <td style="width: 40%;">To reduce security risk and data breech concerns, contractors do not need voicemail. For training and compliance, all employee calls should be recorded.<br><ul>
                <li> Disable voicemail for contractors and enable call recording for all employees.</li>
                </ul>
      </td>
      <td style="width: 60%;">
        <strong>Manage User Calling Data</strong>
            <p>Bulk change Webex Application access and voicemail enablement for Contractors</p>
              <p><b>All Locations &gt; Download Data</b></p>
<ul><li>Specific user data for download: Voicemail</li></ul>

              Once download is initiated, go to <i>View upload history tasks</i> to download the most recent file <br><br>
              <b>Edit the CSV file
              Users: esteele, smauk, kmelby</b>
              <ul>
                <li>Column B: Voicemail enabled – FALSE</li>
            </ul>
            <b>All employees</b>
              <ul>
                <li>Column GP Call Recording enabled TRUE</li>
              </ul><p>
            Upload CSV file. You should see that 8 records have been updated.
      </td>
    </tr>
    <tr>
      <td style="width: 40%;">Spot check your import.<p> <i>Hint: As a shortcut, use the AI-powered smart search bar at the top of Control Hub to search for Kellie Melby.</i></td>
      <td style="width: 60%;">
        <strong>Management &gt; Users &gt; Kellie Melby &gt; Calling</strong><br>
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


>![Think About It](template_assets/thinkingcat.png) Think about it: Which Calling settings might need to be changed for your organization or for certain groups?


