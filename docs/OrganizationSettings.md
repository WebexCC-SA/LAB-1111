# Lab 3 - Organization settings & general template
Organization settings form the backbone of your company’s Webex environment, providing consistency, security, and a customized experience for all users and devices. Some of these settings are best applied organization-wide, while others may be tailored using a template for specific groups of users. In this exercise, we’ll explore how to configure both types to best meet your organization’s needs. 
## Organization settings
[Organization default vs template settings](template_assets/OrgSettings.pdf){:target="_blank"}: Opens in a new tab<br>

<table>
  <thead>
    <tr>
      <th style="width:40%"><strong>Use case & solution</strong></th>
      <td style="width:60%"><strong><a href="http://admin.webex.com/" target="_blank">Control Hub</a> &gt; Management &gt; Organization Settings</strong><p><i>Pro tip: Use Ctrl+F (PC) or Cmd+F (Mac) to find the setting on the page instead of scrolling.</i></th>
    </tr>
  </thead>
  <tbody><td>
        In the Webex App, employees and contractors should only be able to message internally and with approved external vendors, such as Cisco and Temp Recruiters, Inc.<br>   <ul>
                <li> Allow messaging with approved domains.</li>
                </ul>
      </td>
      <td>
        <p><strong>External Communication &gt; External messaging</strong></p>
        <ul>
          <li>Allow selected domains only: Enable</li>
          <li>Manage allowed domains</li>
          <li>Add cisco.com, temprecruiters.com</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        It can be difficult for contractors to remember peoples’ names during video meetings.<br>   <ul>
                <li> Enable the face recognition feature to identify meeting participants.</li>
                </ul>
      </td>
      <td>
        <p><strong>Face recognition</strong></p>
        <ul>
          <li>Allow Name Labels: Enable</li>
          <li>Invite users: Take a look at the email template to invite users to enroll. <em>No action required.</em></li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        PixelPals has several characters, games, and their propriety game engine that are not common words. They don’t want spell check to offer suggestions for them when using Messaging.<br>   <ul>
                <li> Add unique words to the custom dictionary.</li>
                </ul>
      </td>
      <td>
        <p><strong>Custom Dictionary</strong></p>
        <ul>
          <li>Download CSV template</li>
          <li>Edit CSV</li>
          <ul><li>Add PixelPals, PixelPunk, RainbowRaccoon, and CoinDash</li></ul>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Sometimes contractors finish a project but are asked to come back for another one a few weeks later.<br>   <ul>
                <li> Extend the time period for deleting inactive users.</li>
                </ul>
      </td>
      <td>
        <p><strong>Manage inactive user</strong></p>
        <ul>
          <li>Delete inactive users after 60 days</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Leadership is concerned about unprofessional changes to user profiles.<br><br>
        PixelPals fosters an inclusive and respectful workplace culture that respects individuals’ pronoun preferences.<br>   <ul>
                <li> Disable editing of certain user atttributes and enable the prounoun feature.</li>
                </ul>
      </td>
      <td>
        <p><strong>User Attributes &gt; Edit user attributes</strong></p>
        <ul>
          <li>Required user attributes
            <ul>
              <li>Enable first name, last name, and display name</li>
            </ul>
          </li>
          <li>Editable user attributes
            <ul>
              <li>Turn off all editable user attributes</li>
            </ul>
          </li>
          <li>Pronouns
            <ul>
              <li>Enable allow pronouns</li>
              <li>Enable Customizable by users</li>
            </ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Employees should be able to make use of powerful AI features.<br>   <ul>
                <li> Most AI features are on by default. Turn on summaries for call recordings.</li>
                </ul>
      </td>
      <td>
        <p><strong>Cisco AI Assistant &amp; AI features &gt; Customize</strong></p>
        <ul>
          <li>Calling – Enable AI-generated summaries for call recordings</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Security standards dictate specific password requirements.<br>   <ul>
                <li> Update the password policy.</li>
                </ul>
      </td>
      <td>
        <p><strong>Password policy</strong></p>
         <i>Hint: you will need to use the down carrot to open the Password policy options.</i>
        <ul>
          <li>Minimum character length = 10</li>
          <li>Days between password changes = 180</li>
          <li>Passwords can’t contain: PixelPals</li>
        </ul>
       
      </td>
    </tr>
    <tr>
      <td>
        Due to privacy concerns, virtual backgrounds are required for all video calls and meetings.<br>   <ul>
                <li> Enforce the use of virutal backgrounds.</li>
                </ul>
      </td>
      <td>
        <p><strong>Virtual backgrounds</strong></p>
        <ul>
          <li>Allow virtual backgrounds: Keep default settings</li>
          <ul><li>Enforce virtual backgrounds for internal and external: Enable</li></ul>
          <ul><li>Allow all admin-uploaded backgrounds for internal and external: Enable</li></ul>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## General template
[Organization default vs template settings](template_assets/OrgSettings.pdf){:target="_blank"}: Opens in a new tab<br>
<table>
  <thead>
    <tr>
      <th style="width:40%"><strong>Use Case</strong></th>
      <th style="width:60%"><strong>
        <a href="http://admin.webex.com/" target="_blank">Control Hub</a> &gt; Management &gt; Organization Settings &gt; Templates
      </strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        PixelPals Studios needs to apply specific organization settings to the contractors.<br>   <ul>
                <li> Create a template to be applied to the PPS Contractors Group.</li>
                </ul>
      </td>
      <td>
        <p><strong>Create General template</strong></p>
        <ul>
          <li>Template name: PPS Contractors</li>
          <li>Description: Security and privacy restrictions</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td colspan="2"><p><strong>Template Options</strong></p></td>
    </tr>
    <tr>
      <td>
        AI generated summaries could contain sensitive ideas, designs, or project plans that shouldn’t be shared outside the organization.<br>   <ul>
                <li> Disable summaries for Messaging, Meetings and recordings.</li>
                </ul>
      </td>
      <td>
        <p><strong>Messaging</strong></p>
        <ul>
          <li>Space summaries: Disable</li>
        </ul>
        <p><strong>Meetings</strong></p>
        <ul>
          <li>Disable all options</li>
        </ul>
        <p><strong>AI-generated summaries for recordings</strong></p>
        <ul>
          <li>Add AI-generated summaries to meeting recordings: Disable</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Personal insights often analyze collaboration patterns, meeting data, and internal communications, which may expose information about team workflows, project status, or confidential activities. Contractors do not need access to this information.<br>   <ul>
                <li> Disable Personal Insights for contractors.</li>
                </ul>
      </td>
      <td>
        <p><strong>Personal Insights</strong></p>
        <ul>
          <li>Show Personal Insights: Disable</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Contractors should not be able to upload their own or use PixelPal Studios branded virtual backgrounds.<br>   <ul>
                <li> Enable virtual backgrounds, but only those provided by Webex.</li>
                </ul>
      </td>
      <td>
        <p><strong>Virtual background</strong></p>
        <ul>
          <li>Allow Webex backgrounds: Enable</li>
          <ul><li>Disable all others</li></ul></ul>
             <ul><li>Enforce virtual backgrounds for internal and external: Enable</li>
          <ul><li>Allow all admin-uploaded backgrounds for internal and external: Enable</li></ul>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        PDFs of digital whiteboard could contain sensitive ideas, designs, or project plans that shouldn’t be shared outside the organization.
        <br>   <ul>
                <li> Disable whiteboard exporting.</li>
                </ul>
      </td>
      <td>
        <p><strong>Digital Whiteboard</strong></p>
        <ul>
          <li>Allow exporting a whiteboard as a PDF file: Disable</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>
        Create template and click next. 
      </td>
      <td>
        <ul><strong>Apply template to PPS Contractors Group.</strong></ul>
      </td>
    </tr>
  </tbody>
</table>

>![Think about it](template_assets/thinkingcat.png) Think about it: What organization settings might you need to restrict in your organization?
