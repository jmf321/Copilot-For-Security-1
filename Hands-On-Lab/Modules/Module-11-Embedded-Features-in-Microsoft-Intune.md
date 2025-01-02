<h1> Module 11 -Embedded Features in Microsoft Intune</h1>
<h4>🎓 Level: 200 (Advanced)<h4>
<h4>⌛ Estimated time to complete this lab: 30 minutes</h4>
<h2>Objectives </h2>
</p></p>
This module showcases some powerful features that become available in Microsoft Intune when Microsoft Security Copilot is enabled. Features focus on improving device posture meaning ensuring you are running the most secure build, understanding details about assets, quickly understanding the impact of existing policies, comparing devices and other useful details obtained at machine speed. 
</p></p>
<h4>Note: Similar outcomes can be accomplished using the standalone Microsoft Security Copilot dashboard as seen within the embedded experience. </h4>
<h2>Prerequisites </h2>
</p></p>
* You have Microsoft Security Copilot enabled
</p></p>
* You have added the necessary amount of SCU's to complete the Additional Modules (15 SCUs if continuing directly on from the Beginner and Advanced Modules or 8 if you have re-installed Security Copilot).
</p></p>
* You must have access to Microsoft Intune in the same tenant as Microsoft Security Copilot so Security Copilot features are available in Microsoft Intune  
</p></p>
<h2>Exercise 1: Accessing Microsoft Intune and analyzing a device</h2>
</p></p>
At this point, we assume you have completed step one and have at least read only access to Microsoft Intune, which exists in the same tenant as Microsoft Security Copilot. 
</p></p>
1: Go to Intune.microsoft.com. This will bring you to the main Intune dashboard. Let’s click devices on the left to take us to the Device overview page. On that page, choose your Windows devices. 
<img width="1012" alt="intune2" src="https://github.com/user-attachments/assets/9a4b6bce-8bed-4a6a-83b9-296447e8ec18">
</p></p>
2: Now pick a system and click it. I’m choosing one that is out of compliance. 
</p></p>
<h4>Note: You could just hover next to a device and you will see a Security Copilot button popup allowing you to access the AI-generated insights on that device. </h4>
</p></p>
<img width="885" alt="Intune3" src="https://github.com/user-attachments/assets/26f8010d-4fcc-4126-90ad-a52cec4458cc">
</p></p>
3: Now click Explore this device. You may also see Copilot (preview) pop up to advertise what we are about to get into. 
</p></p>
<img width="821" alt="Intune4" src="https://github.com/user-attachments/assets/485bf15e-c77b-46ec-b3fa-ea620db6c4db">
</p></p>
4: If you have the overview pop up, click "not now". You should see some Copilot AI-generated insights available to choose to quickly understand the device of interest. 
</p></p>
<img width="407" alt="Intune5" src="https://github.com/user-attachments/assets/81baa3f5-7828-4bbe-b185-c750680e8595">
</p></p>
5: Let’s try out "Summarize this device". It should take a few seconds and generate a nice summary of the current state of this device. Noice there are other options on the bottom such as seeing what is installed on this device.
</p></p>
<img width="383" alt="Intune6" src="https://github.com/user-attachments/assets/f3cfbab3-2527-4235-9f67-d118b6bb2ae4">
</p></p>
6: Try clicking what apps are installed. It will ask the App type, which for my example, I’m choosing "Managed apps" and clicking submit. 
</p></p>
<img width="403" alt="Intune7" src="https://github.com/user-attachments/assets/8e919781-1109-4822-bb88-3fe64286f376">
</p></p>
<h2>Exercise 2: Analyzing error code</h2>
</p></p>
7: Click the x to close out the pop up and select "Analyze error code"
</p></p>
<img width="771" alt="Intune8" src="https://github.com/user-attachments/assets/7531f956-9379-4107-8820-8924e0697047">
</p></p>
8: Once again, you may see the Copilot pop up advertising what we are about to get into. Choose to Dismiss that and you will find an Error Code bar you can fill in to analyze a error code. This is where you can put in error codes to analyze. 
</p></p>
<img width="431" alt="Intune9" src="https://github.com/user-attachments/assets/c6bbed87-d807-4ba3-add3-f85551b0b241">
</p></p>
9: When you submit an error code, you will get a quick explanation of what it is. This is a much better approach to understanding error messages vs searching the Internet for an explanation. 
</p></p>
<img width="386" alt="Intune10" src="https://github.com/user-attachments/assets/afefb40e-9bcc-4cbd-bbaf-1adcd54efd3e">
</p></p>
<h2>Exercise 3: Comparing devices</h2>
</p></p>
10: Now let’s close that and move on to the next topic, which is using AI to quickly compare two devices. Click "Compare to another device"
</p></p>
<img width="706" alt="Intune11" src="https://github.com/user-attachments/assets/011fbee1-5ba9-429b-82d6-41e396e68a74">
</p></p>
11: This will bring up a window asking for another device to compare against as well as what you are comparing for. Try putting in another device ID and choose an item to compare against. For my example, I'm going to compare "Configuration profiles". 
</p></p>
<img width="369" alt="Intune12" src="https://github.com/user-attachments/assets/2b84328d-b747-4bec-96b2-54e62d047ab6">
</p></p>
<h2>Exercise 4: Comparing devices with AI help</h2>
</p></p>
12: Now let’s close the pop up and move on to the next topic. Click on the left devices. 
</p></p>
<img width="539" alt="Intune13" src="https://github.com/user-attachments/assets/dd0656f1-ee8c-4a54-a44b-9ad9a73e23b4">
</p></p>
13: Now click Configuration
</p></p>
<img width="630" alt="Intune14" src="https://github.com/user-attachments/assets/7d3f90a3-ba89-433e-8de3-c4c1b994dac9">
</p></p>
14: Now let’s choose to build a new Policy by clicking "Create". Then click "New Policy"
</p></p>
<img width="640" alt="Intune15" src="https://github.com/user-attachments/assets/db27f2dd-8329-4cd2-bedc-ea81dc3ca282">
</p></p>
15: This will bring up a pop up. Let’s build a policy profile for Windows 10 or Later and use the profile type "Settings catalog". Click create
</p></p>
<img width="441" alt="Intune16" src="https://github.com/user-attachments/assets/23d3632d-1e40-48f3-8ba4-d55c069bc0af">
</p></p>
16: Let’s give it a name and click "next"
</p></p>
<img width="620" alt="Intune17" src="https://github.com/user-attachments/assets/fadb076e-ea17-4b3b-b3be-f775d6e3540e">
</p></p>
17: Now you will see the Configuration settings options. Click +Add settings. This will bring up the Settings picker. Within that, choose Microsoft Edge, then from that drop down choose Application Guard settings. Click select all these settings. 
</p></p>
<img width="953" alt="Intune18" src="https://github.com/user-attachments/assets/ae345740-fd75-462c-ac15-90aab6b82df9">
18: Click the X on the top corner to close the popup. You will see more Application Guard settings. A common challenge is understanding what all these configuration settings mean. You can click on the Security Copilot button to get a explaining of what the setting means. For example, I’m looking at what Application Guard Container Proxy means. On the right, a pop up comes up explaining all the details of what this configuration setting can do. 
</p></p>
<img width="926" alt="Intune19" src="https://github.com/user-attachments/assets/fe5b368a-4cbe-429e-93d4-3682b3a941d3">
</p></p>
<h2>Exercise 5: Summarize More Details</h2>
</p></p>
19: Now let’s close that popup and go back to Devices. Another point to explore how AI can summarize different configuration settings within Microsoft Intune. Click a device and select a policy configuration to explain. I'll pick an example of Purview Edge browser extension. You can pick any one you have within your environment. 
</p></p>
<img width="766" alt="Intune21" src="https://github.com/user-attachments/assets/6d34de60-ca53-4fee-9ab5-c77ae40852d1">
</p></p> 
20: Within policies, you will see the "Summarize with Copilot" to get details of the policy. 
</p></p>
<img width="924" alt="Intune22" src="https://github.com/user-attachments/assets/a32eb4ae-3eba-429a-ac68-403601b4ab44">
21: This can be super helpful to quickly understand what policies you have and help with decisions on when to use or remove such policies. 
</p></p>
<h2>Exercise 6: Run a query</h2>
</p></p>
22: Next, let’s close that and click devices. Then click "All devices" and choose a device. 
</p></p>
<img width="698" alt="Intune23" src="https://github.com/user-attachments/assets/117f3438-4ee5-4a29-8798-2aa32e576b73">
</p></p>
23: Now let’s choose "Device query". Then click Query with Copilot. 
</p></p>
<img width="776" alt="Intune24" src="https://github.com/user-attachments/assets/ffeac6b3-7a40-44d7-94da-5845e73667a7">
</p></p>
You will see options to query Copilot against. For example, I'll choose "show me all active processes". 
</p></p>
<img width="425" alt="Intune25" src="https://github.com/user-attachments/assets/58a7a457-f3fe-4cb8-a24b-f44d30af84fa">
</p></p>
You can also choose to add processes. Click add and run.
</p></p>
<img width="373" alt="Intune26" src="https://github.com/user-attachments/assets/e139593c-4ba9-416f-b652-09e801822f74">
</p></p>
You will see the results of what is running on the endpoint. 
</p></p>
<img width="1280" alt="Intune27" src="https://github.com/user-attachments/assets/ba5d1150-e89b-49c4-803b-714c2f04f552">
</p></p>
<h4>These are just some of the powerful capabilities that become available when Microsoft Security Copilot is enabled in your environment.</h4>
Please click <a href="https://aka.ms/CfSModule12">here</a> to go to the next Advanced Module (Microsoft Entra) or click <a href="https://aka.ms/CFSDeleteSCU">here</a> to delete the SCUs and complete the course.
