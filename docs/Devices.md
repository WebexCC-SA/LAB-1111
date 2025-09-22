# Lab 8 - Devices and workspaces
Webex devices and workspaces enable secure collaboration by supporting meetings, calling, and content sharing in both personal and shared spaces.

- In this lab
    - Create and configure both shared and personal workspaces
    - Explore the features available for each type of workspace
    - Get hands-on experience with Cisco's Workspace Designer

### Assigning devices

<table>
  <tbody>
    <tr>
      <th style="width:40%;"><p><strong>Use case &amp; solutions</strong></p></th>
      <th style="width:60%;"><a href="http://admin.webex.com/" target="_blank"><strong>Control Hub</strong></a><strong> navigation</strong></th>
    </tr>
    <tr>
      <td style="width:40%;">
        Remember that line application template we implemented in the Calling lab?<br><br>Let’s take a look to see if it was assigned to our users’ existing devices!
      </td>
      <td style="width:60%;">
          <strong>Management &gt; Devices &gt; Select any Cisco 9851</strong><ul>
          <li>Device Management &gt; Configure Layout &gt; Line Key Configuration</li>
          <li>Notice the speed dial we configured in the Calling lab.
          <ul><li>It’s that easy to apply that template to multiple devices!</li>
        </ul></ul>
      </td>
    </tr>
    <tr>
      <td style="width:40%;">
       Anita Perez has a phone in the office but will also need a physical phone in her home office.<br><ul>
          <li>Assign a Cisco 9841 to Anita Perez.</li>
        </ul>
      </td>
      <td style="width:60%;">
        <strong>Management &gt; Devices &gt; Add device</strong><ul>
          <li>Personal usage</li>
          <li>User: Anita Perez</li>
          <li>Cisco Desk Phone: Cisco 9841</li>
          <li>Setup: By Activation code</li>
          <li>Activation code will be provided.</li>
          <li>This code would then be entered on the device by Anita, but we will not need it for this lab.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### Workspaces
<table>
  <tbody>
    <tr>
      <th style="width:40%;"><p><strong>Use case &amp; solution</strong></p></th>
      <th style="width:60%;"><p><a href="http://admin.webex.com/" target="_blank"><strong>Control Hub</strong></a><strong> navigation</strong></p></th>
    </tr>
    <tr>
      <td style="width:40%;">
        <p>Users in the office need a quiet space to focus and make phone calls using their own identities.</p>
        <ul>
          <li>Set up an existing workspace with a hotdesking device. <a href="https://www.webex.com/us/en/workspaces/hot-desk.html" target="_blank">Hotdesking</a> allows users to sign in and book a shared phone for their workday.</li>
        </ul>
      </td>
      <td style="width:60%;">
        <p><strong>Management &gt; Workspaces &gt; Workspace 1</strong></p>
        <ul><li>Actions: Edit
        <ul>
          <li>Name: Quiet Pod 1</li>
          <li>Type: Focus Area</li>
          <li>Capacity: 1</li>
        </ul></ul>
        <ul><li>Overview<ul><li>Devices: Add device
          <li>Cisco Desk Phone: Cisco 9871
            <ul>
              <li>By Activation Code</li>
              <li>This code would then be entered on the device, but we will not need it for this lab.</li>
            </ul></ul> <ul><li>Scheduling
        <ul>
          <li>Hot desk sign in: Enable</li>
        </ul></ul>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="width:40%;">
          <p>The RainbowRaccoon game development team needs a dedicated workspace for team meetings that has a device to make collaboration efficient.</p>
          <ul><li>Set up a workspace to accommodate the large team with a Cisco Room device that can host Webex Meetings.</li>
        </ul>
      </td>
      <td style="width:60%;">
        <p><strong>Management &gt; Workspaces &gt; Add workspace</strong></p>
        <ul>
          <li>Name: Rainbow Think Tank</li>
          <li>Type: Meeting Room</li>
          <li>Capacity: 15</li>
          <li>Location: PPS Corporate</li>
          <li>Floor: RainbowRaccoon floor (may need to scroll)</li>
          <li>Device: Cisco Room and Desk device</li>
          <li>Meetings: Device hosted meetings</li>
          <li>Site: Choose Webex url from drop down</li>
          <li>Activation code will be provided.
          <ul><li>This code would then be entered on the device, but we will not need it for this lab.</li>
          <li>The device will not appear in Control Hub until it has been activated, which we are not doing.</li></ul>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

>![Think About It](template_assets/thinkingcat.png)**Consider the workspaces and devices in your organization**<br>

* Where are the devices physically located?<br>
    * Campus, building, floors<br>
* How are the spaces used?<br>
    * Meetings rooms, open areas, huddle rooms, kiosks<br>
* How many people typically occupy those spaces?<br>
* What is each space’s capacity, and how does it affect device placement and use?<br>
* How will the devices support collaboration and user needs in each environment?<br>

### Workspace Designer

![Reimagine Workspaces](<template_assets/reimagine-workspaces.gif>)

<table>
  <tbody>
    <tr>
      <td style="width:30%;">
        <p>
          <a href="https://www.webex.com/us/en/workspaces/workspace-designer.html" target="_blank"><strong>Click here to open Workspace Designer</strong></a>
        </p>
        <ul>
          <li>Practice creating a room design</li>
        </ul>
      </td>
      <td style="width:70%;">
        <p>
          Cisco Workspace Designer is a free, web-based tool that helps organizations design and deploy video-enabled hybrid workspaces efficiently. It provides customizable room blueprints and a 3D configurator to take meeting rooms from inspiration to reality.
        </p>
      </td>
    </tr>
  </tbody>
</table>

