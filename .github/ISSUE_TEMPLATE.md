Thank you for reporting an issue or suggesting an enhancement. We appreciate your feedback - to help the team to understand your needs, please complete the below template to ensure we have the necessary details to assist you. If you have a actual question, we would ask you to use [SharePoint Developer Group](http://aka.ms/sppnp-community) at Microsoft Tech Community. Thanks!

#### Which PnP repository should you use to report the issue? 

- PnP Samples - https://github.com/OfficeDev/PnP

#### Category
[X] Bug
[ ] Enhancement

#### Environment
[X] Office 365 / SharePoint Online
[ ] SharePoint 2016
[ ] SharePoint 2013

If SharePoint on-premises, what's exact CU version: 

#### Expected or Desired Behavior
I am trying to get the Yammer Group by Id using C#. It was working fine last year. However, it has stopped working for me now. I am getting error shown as below.

Could you please fix / provide suggestion to this ?

I have tried the latest version of the packages (3.7.1903) and issue still exists.

var YammerGroup = YammerUtility.GetYammerGroupById(XXXXXXX, YammerAccessToken);

Error: JSON integer 70230110216192 is too large or small for an Int32. Path '[0].stats.last_message_id', line 1, position 1019.

#### Observed Behavior

Error: JSON integer 70230110216192 is too large or small for an Int32. Path '[0].stats.last_message_id', line 1, position 1019.

#### Steps to Reproduce


