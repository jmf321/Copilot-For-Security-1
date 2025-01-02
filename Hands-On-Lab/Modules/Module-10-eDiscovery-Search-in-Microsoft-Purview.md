<h1> Module 10 - Embedded Features in Microsoft Purview</h1>
<h4>🎓 Level: 200 (Advanced)<h4>
<h4>⌛ Estimated time to complete this lab: 30 minutes</h4>
<h2>Objectives </h2>
</p></p>
This module walks you through how to use Microsoft Security Copilot to assist with generating a script within Microsoft Purview to discover specific desired content. 
<h2>Prerequisites </h2>
</p></p>
* You have Microsoft Security Copilot enabled
</p></p>
* You have added the necessary amount of SCU's to complete the Additional Modules (15 SCUs if continuing directly on from the Beginner and Advanced Modules or 8 if you have re-installed Security Copilot).
 </p></p>
* You must have access to Microsoft Purview in the same tenant as Microsoft Security Copilot so Security Copilot features are available in Microsoft Purview  
</p></p>
<h4>Note: This module will focus on embedded capabilities found with Microsoft Purivew when Microsoft Copilot for security is enabled. You can perform similar steps using the stand alone option for Microsoft Security Copilot</h4>
</p></p>
<h2>Exercise 1: Using Security Copilot to Create eDiscovery Search Queries</h2>
In this exercise, we will show you how to access Microsoft Purview and using AI to generate eDiscovery search queries to find various artifacts.
</p></p>
1: Go to purview.microsoft.com. Click View all Solutions to see all options
</p></p>
<img width="887" alt="purview1" src="https://github.com/user-attachments/assets/16bd84bc-b127-4b2b-bdec-ac131563c69a">
</p></p>
2: Select the eDiscovery button
</p></p>
<img width="848" alt="purview2" src="https://github.com/user-attachments/assets/0f23071e-4ff6-4009-a2ad-a5e6540a7f4f">
</p></p>
3: You can create a new case or click Cases to select an existing case. For this example, we will just go to an existing case.
</p></p>
<img width="326" alt="purview3" src="https://github.com/user-attachments/assets/c08791d5-9534-4454-bea3-4f7da5acb204">
</p></p>
</p></p>
<img width="406" alt="Purview4" src="https://github.com/user-attachments/assets/74c8c215-50b4-4697-8296-ca61af6f9376">
</p></p>
4: You can create a new search or jump into an existing search like I’m doing here
</p></p>
<img width="469" alt="Purview5" src="https://github.com/user-attachments/assets/b9b15599-56bd-4dd2-a5cd-c29c5910c8d9">
</p></p>
5: Select "Draft with Security Copilot"
</p></p>
<img width="460" alt="Purview6" src="https://github.com/user-attachments/assets/87a88d11-fc2b-432e-9a66-40982f2e74e2">
</p></p>
6: Here you can ask in natural language to ask Microsoft Security Copilot what to search for. 
</p></p>
<img width="917" alt="Purview7" src="https://github.com/user-attachments/assets/f872341e-7830-44be-aeec-e948498f661f">
</p></p>
7. You could click the Suggested Prompts button to get an idea of some prompts you could use. 
</p></p>
<img width="388" alt="Purview8" src="https://github.com/user-attachments/assets/bd45fe4d-a1a9-4677-b9b8-80ace61b4d3b">
</p></p>
8. For my example, I’ll ask finding conversations containing specific keywords as shown. I'll click Refine to have Copilot clean this up into something that can be translated into a KQL result. 
</p></p>
<img width="361" alt="Purview9" src="https://github.com/user-attachments/assets/825818b5-964b-4808-9f40-b05f46382f01">
</p></p>
9: You should see a refined version of your request. If it looks good, choose to accept it
</p></p>
<img width="362" alt="Purview10" src="https://github.com/user-attachments/assets/03cf7752-8d3b-49c7-a0f9-014fb79bd95c">
</p></p>
10: Now choose to Generate KQL. This will create you KQL code you can use to hunt for your desired data. 
</p></p>
<img width="705" alt="Purview11" src="https://github.com/user-attachments/assets/8070653c-3dc6-41f4-a5d4-adf774c461f9">
</p></p>
11: Simply copy the code and run it to find your desired data. 
</p></p>
<h4>Now it’s your turn. Try opening a new case or opening an existing case and use Microsoft Security Copilot. Use the sample prompts and adjust to fit your eDiscovery needs. AI can simplify your eDiscovery process!</h4>
</p></p>
<h2>Exercise 2: Summarize Evidence Collected via eDiscovery with Security Copilot</h2>
</p></p>
12: Now lets explore how to use AI to summarize evidence collected via eDiscovery capabilities within Microsoft Purview. Click "Home" and select eDiscovery. Then click "Cases" to bring up your cases. You could also create a new case. 
</p></p>
<img width="736" alt="PurviewE1" src="https://github.com/user-attachments/assets/59baf5d3-0576-4d76-9cd1-d397701c0d4d">
</p></p>
13. Next click "Review sets". 
</p></p>
<img width="494" alt="PurviewE2" src="https://github.com/user-attachments/assets/254b67f5-2912-4d35-9453-567944b1b61c">
</p></p>
14. Next, im going to choose the existing review set. You could also create a new one if needed. 
</p></p>
<img width="617" alt="PurviewE3" src="https://github.com/user-attachments/assets/166e6d2a-55b7-439f-88fe-267ca824ea66">
</p></p>
15.Finally, open the review set.
</p></p>
<img width="302" alt="PurviewE4" src="https://github.com/user-attachments/assets/5d9bdc9d-b898-4020-a6b7-614d1b286dae">
</p></p>
16. I'm now going to create a filter query that looks at file classes that equals any conversation as shown. 
</p></p>
<img width="642" alt="PurviewE5" src="https://github.com/user-attachments/assets/1bad58a3-77f5-4f7a-8f4e-a1098ce080d5">
</p></p>
17. Choose a review set within the source, you will see a Security Copilot Summarize button. Click that
</p></p>
<img width="799" alt="PurviewE6" src="https://github.com/user-attachments/assets/ee2d3209-05e2-4b6f-84bd-c41bedc8bb66">
</p></p>
18. Security Copilot will summarize what was found, which you could continue to ask Security Copilot about the conversation as shown in my example. 
</p></p>
<img width="926" alt="PurviewE7" src="https://github.com/user-attachments/assets/2345bd07-f652-4c7d-9659-ad2d6bf87898">
</p></p>
19. The same concepts even apply across different languages. My next example shows conversations I would need to translate to understand. 
</p></p>
<img width="920" alt="PurviewE8" src="https://github.com/user-attachments/assets/d1c4b7df-b0fa-45a5-ad9f-4c15fda680cc">
</p></p>
<h2>Exercise 3: Summarizing DLP alerts with Security Copilot</h2>
</p></p>
20. Let's switch our focus to Data Loss Prevention. One challenge can be understanding the cause and impact associated with DLP alerts. This is another area Security Copilot can help. Let's explore this by first accessing the Data Loss Prevention section with Microsoft Purview and select Alerts. 
</p></p>
<img width="213" alt="PurviewD1" src="https://github.com/user-attachments/assets/b7c78421-dbbc-4609-9675-9c5744f4d607">
</p></p>
21. Choose an alert and you should see Security Copilot provides a summary. 
</p></p>
<img width="802" alt="PurviewD2" src="https://github.com/user-attachments/assets/4333669e-4de8-4c8a-8531-8f87288be4f7">
</p></p>
22. You not only get a summary, but you can also take these findings to the stand stand-alone of Security Copilot to continue your investigation with other tools and resources by clicking the three dots and choosing Open in Security Copilot. 
</p></p>
<img width="406" alt="PurviewD3" src="https://github.com/user-attachments/assets/1ee769a4-77c1-45e9-aebe-43bfcb30310d">
</p></p>
<img width="696" alt="PurviewD4" src="https://github.com/user-attachments/assets/b55611d0-4a78-4d9b-a0cb-5cc5cbc872a8">
</p></p>
This feature gives the analyst a very quick view of the alert so they can decide what is the next best action. Maybe it is clicking to get more details within Microsoft Purview. Maybe its taking these finds to the stand alone version of Security Copilot to either investigate other resources or create a message using the power of AI summary capabilities. Maybe it’s an alert that can be ignored. The point is that AI makes this decision process much faster using the alert summary capabilities of Security Copilot built into Microsoft Purview. 

Please click <a href="Module-11-Embedded-Features-in-Microsoft-Intune.md">here</a> to go to the next Advanced Module (Microsoft Intune) or click <a href="Deleting-SCU.md">here</a> to delete the SCUs and complete the course.
