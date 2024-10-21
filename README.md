# Google Sheets API for Job Applications

As a job seeker, I know firsthand how many people are constantly searching for new roles. To stay organised, I created a spreadsheet to track my applications. However, with the sheer number of positions I've applied for, I needed an easier way to manage this information. Specifically, I wanted to keep track of where I’ve applied, the details of each role, and information about the company.

The job search process is already challenging. From writing tailored cover letters and CVs to preparing for interviews, it's difficult to remember the specifics of every job—especially when a recruiter calls you about an application from three months ago!

That got me thinking—how can I use AI to make this process easier? While AI can help with writing cover letters and CVs, I already have versions I’m proud of. Then it hit me: why not use AI to analyse the job descriptions I add to my spreadsheet and extract key details about the roles and companies?

That’s great, but how do I actually do this? And how much does it cost?

After about five minutes of searching on Google, I found two methods that I felt confident in using.

## No-Coding Method:
In Google Sheets, you can utilise add-ons to integrate AI functionality. Here’s how you can set it up:

Go to Extensions: On the toolbar in Google Sheets, click on the "Extensions" menu.
Select Get Add-ons: From the drop-down menu, choose "Add-ons" and then click on "Get add-ons" (as shown in the image below).

<img width="1019" alt="Screenshot 2024-10-21 at 13 31 38" src="https://github.com/user-attachments/assets/d0d063d6-e2e5-4873-a4eb-2e32af51ca71">

Search for ChatGPT: In the search bar of the add-ons window, type in “ChatGPT” to find relevant tools.

<img width="982" alt="Screenshot 2024-10-21 at 13 55 07" src="https://github.com/user-attachments/assets/b8fd1b7a-34b3-47c9-bbc7-10b680861e45">

Choose an Add-on: There are several options, but I found Coefficient to be my favourite due to its functionality and the availability of a free trial.

<img width="931" alt="Screenshot 2024-10-21 at 13 32 23" src="https://github.com/user-attachments/assets/393e8989-b8aa-48b2-91e7-b8868a3f7fed">

Install and Enable the Add-on: Once installed, enable the add-on.

<img width="1006" alt="Launch" src="https://github.com/user-attachments/assets/2b67b144-1857-4582-aff5-1119e657664c">

After enabling it, you can use this tool just like any other function in Google Sheets. Below is an example of a prompt I used, along with the resulting information.

(Side note: I hope Toyota Connected doesn’t mind being used as an example here—haha!)

Here is an example of what I did:

<img width="1288" alt="Experience Prompt" src="https://github.com/user-attachments/assets/47a8bcde-1c74-42d7-8aee-bd8556b0d1a9">
<img width="1018" alt="Soft Skills Prompt" src="https://github.com/user-attachments/assets/0e814ace-c006-44e5-810d-25d4f9ec5789">
<img width="1293" alt="Technical Skills Prompt" src="https://github.com/user-attachments/assets/7771ffb4-3817-4ce6-b6de-1eb2dfc05e52">
<img width="2419" alt="Overview" src="https://github.com/user-attachments/assets/694aaf09-b549-486b-b840-d3e5b14f5059">

## Coding Method

While the no-coding method was a great way to streamline the process, I wanted to use my coding skills to gain a deeper understanding of how to connect to APIs and practise coding in a real-world scenario.

Here’s how I did it:

Add a Script in Google Sheets:
First, go to the Extensions menu and choose the option to add a script editor, as shown in the image below:

<img width="389" alt="Extensions" src="https://github.com/user-attachments/assets/208bb765-b01e-492d-97dc-65e9bea1386d">

Open the Script Editor:
In the script editor, you can start writing your code. This is where you’ll connect to the API and manipulate data.

<img width="755" alt="Code" src="https://github.com/user-attachments/assets/9f3d82c3-1918-4309-945a-b12bafe37506">

Example Script:
Here’s an example of what the script editor looks like once you’ve written your code:

<img width="1097" alt="Example" src="https://github.com/user-attachments/assets/7c56c8e3-ac52-4da2-9a39-2e9496a058dc">

API Overview:
The API I connected to provided a range of functionality that allowed me to automatically pull job details into my spreadsheet. This not only saved time but also improved the accuracy of the information I was tracking

<img width="1779" alt="Api Overview" src="https://github.com/user-attachments/assets/a1230e3e-5496-4d5c-ae3d-4fbd855d51ae">

