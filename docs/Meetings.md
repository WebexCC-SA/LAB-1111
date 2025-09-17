# Lab 5 - Meetings
Webex Meetings offers a wide range of features for hosts and cohosts. And with Webex, the most secure.  In this lab, you'll review which settings may need adjustment for your organization. Then, following the approach from earlier labs, you'll create and apply a template with specific limitations for a user group that requires additional controls. 

[Meetings default vs template settings](template_assets/MeetingsSetting.pdf){:target="_blank"}: Opens in a new tab<br>
<table>
  <tbody>
    <tr>
      <th style="width:40%;">Use Case</th>
      <th style="width:60%;">
        <a href="http://admin.webex.com/" target="_blank">Control Hub</a> &gt; Services &gt; Meetings &gt; Templates
      </th>
    </tr>
    <tr>
      <td>
        <strong>Create template</strong>
        <ul>
          <li>Template Name: PPS Contractors</li>
          <li>Description: Internal Meetings</li>
        </ul>
      </td><td>
      </td>
    </tr>
    <tr>
      <td style="width:40%;">
        Limiting contractors to internal meetings only in Webex Meetings enhances your organization's security by preventing external exposure of sensitive information.
      </td>
      <td style="width:60%;">
        <p><strong>Meetings</strong></p>
        <p><strong>Internal</strong></p>
        <ul>
          <li>Block all external users</li>
        </ul>
        <p><strong>External</strong></p>
        <ul>
          <li>Allow approved external sites</li>
          <li>Add: cisco.webex.com</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Disabling Slido for contractors prevents them from starting polls or Q&amp;A sessions, which could otherwise lead to distractions or sharing of unintended information.
      </td>
      <td>
        <p><strong>Collaboration tools</strong></p>
        <ul>
          <li><strong>Polling, Q&amp;A, Slido</strong></li>
          <li>Disable Internal meeting and External meeting</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Disabling recording capabilities for contractors helps safeguard your organization's confidential information, supports compliance with data management policies, and reduces security risks associated with uncontrolled recording and sharing of meeting content.
      </td>
      <td>
        <p><strong>Recording</strong></p>
        <p><strong>Cloud recording &amp; Local Recording</strong></p>
        <ul>
          <li>Disable Internal meeting and External meeting</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Disabling remote control for contractors is a best practice to ensure secure collaboration and protect sensitive information during Webex meetings.<br>
        Limit who contractors can pass remote control to and control of in internal and external meetings.
      </td>
      <td>
        <p><strong>Remote Control</strong></p>
        <p><strong>Turn on remote control</strong></p>
        <ul>
          <li>Disable External meeting</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        We want to limit what can be shared with meeting attendees. We’ll turn off desktop sharing for both internal and external meetings. Turning off desktop sharing prevents confidential or private content being visible to meeting attendees.
      </td>
      <td>
        <p><strong>Sharing</strong></p>
        <p><strong>Enable Sharing</strong></p>
        <ul>
          <li>Internal and External Meetings: Disable Desktop Sharing only</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        To reduce telephony costs, we want to limit contractors to “Toll” only. Although we do encourage use of computer audio for all meetings.
      </td>
      <td>
        <p><strong>Telephony</strong></p>
        <p><strong>Call in</strong></p>
        <ul>
          <li>Enable Toll</li>
        </ul>
        <p><strong>Call back</strong></p>
        <ul>
          <li>Disable Host only</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Apply template to PPS Contractor Group
      </td>
      <td>
        <ul>
          <li>Click Create template and next</li>
          <li>Search “PPS Contractor Group”</li>
          <li>Click Done</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

>![Think about it](template_assets/thinkingcat.png) Think about it: What Meetings settings would you need to change?
