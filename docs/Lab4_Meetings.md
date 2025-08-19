# Lab X- Calling Settings

![Table1](/../docs/template_assets/Table1.png)
##Service Settings
Control Hub -> Services -> Calling -> Service Settings

Put a blurb here about service settings

| Service Settings| Can Override | On by Default |
|---|---|---|
| Voicemail – defaults for voicemail forwarding/deletion/passcodes | No |Default Setting|
| Manage User Calling Data – point out a couple of simple things to edit in the bulk file | Yes, with CSV | N/A |
| Device Line Key templates- Create line key for 9851 to use later when we add devices | With device template | N/A |

###<span style="color:blue"><b>Lab Activity</span></b>
|Control Hub Navigation|Task|
| --- | --- |
| Services-> Calling-> Service settings-> Voicemail | IT security policies dictate that voicemail passwords be reset at a regular interval.<br>Set the number of days after which passcode expires to 30 |
|Services-> Calling -> Service settings -> Line Key Templates | All users will have 9851 phones. They will all need to have a speed dial and a second line configured on their phones. <br> Configure line key template - info here.|

##Client Settings
Control Hub -> Services-> Calling -> Client Settings

Put a blurb here about Client settings

| Client Settings | Override | On by default |
|---|---|---|
| In-call feature access | With calling template | Yes |
| DND Status Sync | No | Yes |
| Hide Calling Settings | At user level only | All options on |


###<span style="color:blue"><b>Lab Activity</span></b>

| Navigation| Task |
|---|---|
|[user.webex.com](https://user.webex.com) -> Settings -> Calling| In a new tab: Log in as Charles Holland (your admin log in credentials)<br>Call Settings – Note that the Block Caller ID setting is available<br>Voicemail – Note all voicemail settings are available.<br> <br>|
|[Control Hub](https://admin.webex.com)-> Services-> Calling -> Client Settings| Company policy dictates that users cannot block their caller id or manage any of their voicemail settings in the Webex App and/or [User Hub](https://user.webex.com)<br><br>Disable: Block Caller ID<br>Voicemail: Disable all voicemail features|
|[user.webex.com](https://user.webex.com)-> Settings -> Calling|Check that the settings have been removed when you are logged in as Charles Holland
!!! note    
    You may need to reload the page or log out/back in. Changes could take a few minutes.

##Templates
Control Hub -> Services-> Calling -> Client Settings -> Templates

Put a blurb here about Templates

| Setting| On by default |
|---|---|
| In-call feature access | All options on |
| Microsoft Team Integration – off | No |
| Emergency call disclaimer - off | No |

###<span style="color:blue"><b>Lab Activity</span></b>

| Navigation| Task |
|---|---|
| Control Hub->Services-> Calling-> Client settings-> Templates -> Create template | XYZ group should not be able to share content or request/give remote control of shared content.<ol><li>Template name: Disable Sharing</li><li>Disable<ol><li>Request remote control</li><li>Give remote control</li><li>Screen sharing</li></ol></li><li>Apply template to XYZ group</li></ol>

<table style="border-color: blue; background-color: white; width: 900px;" border=".5" cellspacing="1" cellpadding="1">
<tbody>
<tr style="height: 84.5px;">
<td style="width: 496.391px; height: 84.5px;">
<p><strong>General Template</strong></p>
<p><strong>Management-&gt; Organization Settings</strong></p>
<p><em>(Relevant to Webex Suite optimization)</em></p>
</td>
<td style="width: 20.6094px; height: 84.5px;">
<p><strong>On by default</strong></p>
</td>
<td style="width: 54px; height: 84.5px;">
<p><strong>Override with template</strong></p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Webex web client&rsquo;s idle timeout</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Control Hub&rsquo;s idle timeout</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Allow bring your own device</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>External communication</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Custom Dictionary</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>User attributes: Profile Attributes</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>&nbsp;</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<ul>
<li>Required user attributes</li>
</ul>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<ul>
<li>Editable user attributes</li>
</ul>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>&middot;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Pronouns</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;">
<p>&nbsp;</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>User attributes: Custom attributes</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p><strong><a href="https://help.webex.com/en-us/n6x6b78/What-Is-People-Insights">People Insights Profiles</a></strong></p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">
<p>Yes</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Recommended Messages&nbsp;</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Cisco AI Assistant &amp; AI features</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>&nbsp;</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;" scope="rowgroup">
<ul>
<li>Control Hub, Messaging, Meetings</li>
</ul>
</td>
<td style="width: 20.6094px; height: 35px;" scope="rowgroup">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;" scope="rowgroup">
<p>Yes</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;" scope="rowgroup">
<ul>
<li>Calling</li>
</ul>
</td>
<td style="width: 20.6094px; height: 35px;" scope="rowgroup">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;" scope="rowgroup">
<p>Yes</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>AI-generated summaries for recordings</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Personal insights</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">
<p>Yes</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Customized branding for Webex</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Personalized email settings</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;">&nbsp;</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Scheduling in the Webex app</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">
<p>&nbsp;</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Simultaneous interpretation</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;">
<p>&nbsp;</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Virtual Background</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">
<p>Yes</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Digital whiteboard</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">
<p>Yes</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Webex sidebar: Allow user customization</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>No</p>
</td>
<td style="width: 54px; height: 35px;">
<p>&nbsp;</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p>Default Landing Screen for Webex App</p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">
<p>&nbsp;</p>
</td>
</tr>
<tr style="height: 5px;">
<td style="width: 496.391px; height: 35px;">
<p><strong><a href="https://help.webex.com/en-us/article/kb37to/Turn-Carbon-Aware-Mode-on-or-off-for-users">Carbon Aware Mode</a></strong></p>
</td>
<td style="width: 20.6094px; height: 35px;">
<p>Yes</p>
</td>
<td style="width: 54px; height: 35px;">
<p>&nbsp;</p>
</td>
</tr>
</tbody>
</table>    