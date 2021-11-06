# Advanced RustServer Launcher
Rust Server Install and Startup Utility<br />
<br />
Main Download: https://github.com/StonerJezus/Advanced_RustServer_Launcher/archive/refs/heads/master.zip <br />
Open Batch Download: Not Available. <br />

<h1> Features </h2>
<details>
<summary>&nbsp;Start Example Creator </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This Will Activate Whenever One Of The Startup Batch Files Is Missing.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In Case You Already Created Them, You Can Re-do Them Through The Menu.
<hr /></details>
<details><summary>&nbsp;Main Branch & Beta Staging</summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Server Setup for Main Branch<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Server Setup for Beta-Staging
<hr /></details>
<details><summary>&nbsp;Vanilla Server & Modded Server </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On Startup The Server Will Ask You If You Want Your Server Vanilla Or Modded.<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Choosing Vanilla Will Prevent The Server From Activating<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Oxide & RustEdit DLL Check / Patch
<hr /></details>
<details><summary>&nbsp;Procedural Map, Hapis Island, Custom Map </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Server Setup for Procedural generated map<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Server Setup for Hapis Island map<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Server Setup for Custom map<br />
<hr /></details>
<details><summary>&nbsp;Oxide + RustEdit.dll Patcher</summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Will Download And Patch Oxide & The RustEdit.dll<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;( Both Optional )<br />
<hr /></details>
<details><summary>&nbsp;Automatic Patchers On Start-Up </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Depending on what type of map / server you choose to use,<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The system will check for updates and will automatically Patch Server Updates,<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Oxide, Checks for (needed) presence of the RustEdit.dll and makes sure <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;everything is on it's place and Up-to-Date before starting your Server!<br />
<hr /></details>
<details><summary>&nbsp;Automated Map Switcher </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Automated Map Switch Is Designed To Be Set Up In The Menu.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Every Time You Set It Up It Will Create a Text File Inside The "Important" Directory.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It Is Possible To Adjust It Manual Keep In Mind That In Case Of Doing This,<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There Has To Be ONE Empty Line Under The Date And Time!<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To Make The Automated Map Switch Activate Changing Out The Bat File, The Server<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Needs To Close Down And Started Up Within a Minute To Match The Set Time With The Current One.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;You Can Use Windows Task Scheduler For That.<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;THIS FUNCTION IS NOT TESTED A LOT<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;From My Own Testing It Seemed To Switch Out The Current Batch<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;And Also Seemed To Start With The New Settings!<br />
<hr /></details>
<details><summary>&nbsp;Client Side Map Wipe (Local Hosted Only) </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A Nice Tool For Map Developers That Host a Test Server Localy<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The System Will Ask You To Write The Letter Of The Hard Drive<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;You Installed Your Rust Client On.<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If You Have Your Rust Client Installed In a Sub-Directory<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;You Will Have To Write Everything That Go's In Front:<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\Steam\steamapps\common\Rust\maps<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Once You Set It Up Correctly, It Will Remember The Location<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To Change The Location, Go In The Menu Again. It Will<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Remove The Old Setting Every Time You Set It Up Again.<br />
<hr /></details>
<details><summary>&nbsp;Server Map Wipe </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Option to wipe Server Map & save files, but keep everything else.<br />
<hr /></details>
<details><summary>&nbsp;Player BP Wipe </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Option to wipe the Servers Player Data, but keep everything else.<br />
<hr /></details>

<details><summary>&nbsp;Port Forwarding Server Ports</summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Optional Server Port-Forwarding<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Choice to Use the given Ports from the Start Example Creator and<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;let the system Create all needed Port rules on your machines Firewall.
<hr /></details>
<details><summary>&nbsp;Complete Package Re-Install </summary><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This Will Back-Up The Entire Oxide Folder, Server Config,

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Maps And Player Data, And Sets Everything Else Back To First Use.<br />
</details><hr />

**NOTE**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• All Wipes Will Back Up Old Information To The  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\\.AdvancedServerProcessing\OldServerData&nbsp;&nbsp;&nbsp;&nbsp;Directory
<br /><hr />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Functionality Manual](https://github.com/StonerJezus/advanced-server-starter/blob/main/RustServer/Functionality%20Manual.txt)&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Umod Rust Plugins](https://umod.org/plugins?page=1&sort=title&sortdir=asc&categories=rust)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Rust Map Editor](https://www.rustedit.io)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<div align="center">

```batch
  
||==================================================================================================||
||                         W A R N I N G     W A R N I N G     W A R N I N G                        ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                   Do NOT Change The Layout of The Package, This Will Break It!                   ||
||                                                                                                  ||
||                         Do NOT Rename The  "Advanced Server Starter.exe"                         ||
||                                                                                                  ||
||       ALWAYS Make Sure You Get This Package Directly From Github, LoneDesign or Codefling!       ||
||                                                                                                  ||
||  Do Not Remove Anything From The "Important" Directory, This Has a Chance of Breaking The Tool.  ||
||                                                                                                  ||
||                                                                                                  ||
||                                                                                                  ||
||      ALL WIPES WILL BACK UP OLD INFO TO   \.AdvancedServerProcessing\Important\OldServerData     ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
||                          1.    S T A R T   E X A M P L E   C R E A T O R                         ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                This Will Activate Whenever One Of The Startup Batch Files Is Missing.            ||
||                In Case You Already Created Them, You Can Re-do Them Through The Menu.            ||
||                                                                                                  ||
||                               NEW : Optional Server Port-Forwarding                              ||
||                                                                                                  ||
||==================================================================================================||
||                     2.    M A I N   B R A N C H   &   B E T A -  S T A G I N G                   ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                                  - Server Setup for Main Branch                                  ||
||                                  - Server Setup for Beta-Staging                                 ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
||                               3.    V A N I L L A  /  M O D D E D                                ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||           On Startup The Server Will Ask You If You Want Your Server Vanilla Or Modded.          ||
||                                                                                                  ||
||                      Choosing Vanilla Will Prevent The Server From Activating                    ||
||                               The Oxide & RustEdit DLL Check / Patch                             ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
||            4.    P R O C E D U R A L  M A P ,  H A P I S  M A P ,  C U S T O M   M A P           ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                            - Server Setup for Procedural generated map                           ||
||                               - Server Setup for Hapis Island map                                ||
||                                  - Server Setup for Custom map                                   ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
||                    5.    O X I D E   &   R U S T E D I T . D L L   P A T C H E R                 ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                         Will Download And Patch Oxide & The RustEdit.dll                         ||
||                                      ( Both Optional )                                           ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
||                          6.    A U T O M A T E D    M A P    S W I T C H                         ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                   The Automated Map Switch Is Designed To Be Set Up In The Menu.                 ||
||                                                                                                  ||
||          To Make The Automated Map Switch Activate Changing Out The Bat File, The Server         ||
||  Needs To Close Down And Started Up Within a Minute To Match The Set Time With The Current One.  ||
||                                                                                                  ||
||                          You Can Use Windows Task Scheduler For That.                            ||
||                                                                                                  ||
||                                THIS FUNCTION IS NOT TESTED A LOT                                 ||
||                  From My Own Testing It Seemed To Switch Out The Current Batch                   ||
||                       And Also Seemed To Start With The New Settings!                            ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
||                               7.    S E R V E R    M A P    W I P E                              ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                     This Will Remove EVERYTHING In The Server Maps Directory                     ||
||                 Including Player Data, And Backs It Up To The Back-Up Directory.                 ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
||                               8.    C L I E N T    M A P    W I P E                              ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                   A Nice Tool For Map Developers That Host a Test Server Localy                  ||
||                                                                                                  ||
||                   The System Will Ask You To Write The Letter Of The Hard Drive                  ||
||                                You Installed Your Rust Client On.                                ||
||                                                                                                  ||
||                     If You Have Your Rust Client Installed In a Sub-Directory                    ||
||                       You Will Have To Write Everything That Go's In Front:                      ||
||                                 \Steam\steamapps\common\Rust\maps                                ||
||                                                                                                  ||
||                    Once You Set It Up Correctly, It Will Remember The Location                   ||
||                       To Change The Location, Go In The Menu Again. It Will                      ||
||                       Remove The Old Setting Every Time You Set It Up Again.                     ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
||                            9.    C O M P L E T E    R E - I N S T A L L                          ||
||==================================================================================================||
||                                                                                                  ||
||                                                                                                  ||
||                     This Will Back-Up The Entire Oxide Folder, Server Config,                    ||
||                 Maps And Player Data, And Sets Everything Else Back To First Use.                ||
||                                                                                                  ||
||                                                                                                  ||
||==================================================================================================||
```
</div>