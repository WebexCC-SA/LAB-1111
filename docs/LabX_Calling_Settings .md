# Lab X- Calling Settings


#Service Settings
#####Control Hub->Services-> Calling -> Service Settings
Put a blurb here about service settings

| Service Settings| Can Override | On by Default |
|---|---|---|
| Voicemail – defaults for voicemail forwarding/deletion/passcodes | No |Default Setting|
| Manage User Calling Data – point out a couple of simple things to edit in the bulk file | Yes, with CSV | N/A |
| Device Line Key templates- Create line key for 9851 to use later when we add devices | With device template | N/A |

##<span style="color:blue"><b>Lab Activity</span></b>
|Control Hub Navigation|Task|
| --- | --- |
| Services-> Calling-> Service settings-> Voicemail | IT security policies dictate that voicemail passwords be reset at a regular interval.<br>Set the number of days after which passcode expires to 30 |
|Services-> Calling -> Service settings -> Line Key Templates | All users will have 9851 phones. They will all need to have a speed dial and a second line configured on their phones. <br> Configure line key template - info here.|

#Client Settings
#####Services-> Calling -> Client Settings
Put a blurb here about Client settings

| Client Settings | Override | On by default |
|---|---|---|
| In-call feature access | With calling template | Yes |
| DND Status Sync | No | Yes |
| Hide Calling Settings | At user level only | All options on |

#Templates
#####Services-> Calling -> Client Settings -> Templates
Put a blurb here about Templates

| Setting| On by default |
|---|---|
| In-call feature access | All options on |
| Microsoft Team Integration – off | No |
| Emergency call disclaimer - off | No |

##<span style="color:blue"><b>Lab Activity</span></b>

| Navigation| Task |
|---|---|
| user.webex.com -> Settings -> Calling| In a new tab: Log in as Charles Holland (your admin log in credentials)<br>Call Settings – Note that the Block Caller ID setting is available<br>Voicemail – Note all voicemail settings are available.<br> <br>Company policy dictates that users cannot block their caller id or manage any of their voicemail settings in the Webex App and/or User Hub (user.webex.com) <br><br>In Control Hub:<br>Call settings – disable Block Caller ID<br>Voicemail – disable all voicemail features<br><br>Go to User.webex.com, log in as Charles Holland (your admin log in credentials) to check that the settings have been removed. <br>(You may need to reload the page or log out/back in. Changes could take a few minutes) |
| Control Hub->Services-> Calling-> Client settings-> Templates -> Create template | XYZ group should not be able to share content or request/give remote control of shared content.<ol><li>Template name: Disable Sharing</li><li>Disable<ol><li>Request remote control</li><li>Give remote control</li><li>Screen sharing</li></ol></li><li>Apply template to XYZ group</li></ol>

