# Lab 6 - Calling
Webex Calling provides a robust set of features to enhance your organization's communication, and it’s all in the cloud.  In this lab, you'll review and optimize key Webex Calling service settings, then adjust client-specific settings as needed. Finally, you'll import and apply feature changes for your Calling users to ensure the best experience across your organization.

The [Calling settings chart](template_assets/CallingSettings.pdf){:target="_blank"} shows which Calling settings are set by default and which you can change for groups using a template or bulk tools to override. Use the chart as a quick reference to see default settings versus customizable options to fit your organization’s needs
## Service settings
<table>
  <thead>
    <tr>
      <th style="width: 40%;">Use Case & Solution</th>
      <th style="width: 60%;"><a href="http://admin.webex.com/" target="_blank">Control Hub</a> &gt; Services &gt; Calling &gt; Settings > Service</th>
    </tr>
  </thead>
  <tbody><tr><td colspan="2;"><i>Note: Most individual settings require clicking save before moving to the next setting.</i></td></tr>
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
    <td style="width: 40%;">For training and compliance, all employee calls should be recorded.
      </td>
      <td style="width: 60%;">
        <strong>Manage User Calling Data</strong>
            <p>Bulk change recording access</p>
              <p><b>All Locations &gt; Download Data</b></p>
<ul><li>Specific user data for download:<ul><li>Recording<li>Voicemail</ul><li>Once download is initiated, go to <i>View upload history tasks</i> to download the most recent file </ul>
              Edit the CSV file<br>
              <ul><b>All employees</b>
            <ul><li>Column GP Call Recording enabled: TRUE</li> 
            <li>Column GQ Call Recording type: Always
                <ul><i><strong>These are case sensitive!</strong></i></ul></ul>
  <b>Contractors</b><ul><li>Kellie Melby, Eric Steele, Stefan Mauk
              <li>Column B: Voicemail enabled – FALSE
              </ul><p>
            Upload CSV file. You should see that 8 records have been updated.
      </td>
    </tr>
     <td style="width: 40%;">All users have the same physical phone and need the same speed dial button configured.
    <p><ul><li>Create a Line Key Template
      </td>
     <td style="width: 60%;">
        <strong>Device<p>Configure Default Device Settings > Line Key Templates > View Templates > Create custom template</strong></p>
<ul><li>Template name: 9851 Speed Dial<li>Device Model: Cisco 9851<li>Assign Line Key<ul><li>Order 2: Speed dial<li>
Line Key Label: Cisco Support<li>Destination: 18005536387</ul><li>Assign template<ul><li>Locations: PPS Corporate<li>Current device layout: Default Layout<li>8 devices will be found. Apply Custom Layout.
              </ul>
      </td>
    </tr>
  </tbody>
</table>

## Webex App settings and template
<table>
  <thead>
    <tr>
      <th style="width: 40%;"><strong>Use Case & Solution</strong></th>
      <th style="width: 60%;"><strong><a href="http://admin.webex.com/" target="_blank">Control Hub</a> &gt; Services &gt; Calling &gt; Settings</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="width: 40%;">Company policy dictates that users cannot block their caller id or manage any of their voicemail settings in the Webex App and/or User Hub (user.webex.com)  <ul><br>
                <li> Remove caller ID and voicemail settings from User Hub.</li>
                </ul></td>
      <td style="width: 60%;">
        <p><strong>Webex App > Hide Calling Settings</strong></p>
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
        <p><strong>Templates &gt; Webex App > Create template</strong></p>
        <ul>
          <li>Template name: PPS Contractors<ul><li>Description: Disable Sharing</ul>
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


