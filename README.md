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

<img width="1019" alt="Screenshot 2024-10-21 at 13 31 38" src="https://github.com/user-attachments/assets/4e161a42-4e9a-4a9d-b3d6-9c5c22080f73">

Search for ChatGPT: In the search bar of the add-ons window, type in “ChatGPT” to find relevant tools.

<img width="982" alt="Screenshot 2024-10-21 at 13 55 07" src="https://github.com/user-attachments/assets/17194cde-dc7b-49be-9aec-f5eabb3b63ed">

Choose an Add-on: There are several options, but I found Coefficient to be my favourite due to its functionality and the availability of a free trial.

<img width="931" alt="Screenshot 2024-10-21 at 13 32 23" src="https://github.com/user-attachments/assets/a4af0744-a31a-426f-b40f-a05e5cd908b7">

Install and Enable the Add-on: Once installed, enable the add-on.

<img width="1006" alt="Launch" src="https://github.com/user-attachments/assets/f0a8db74-30b8-45f1-9c45-1e5a7567251a">

After enabling it, you can use this tool just like any other function in Google Sheets. Below is an example of a prompt I used, along with the resulting information.

(Side note: I hope Toyota Connected doesn’t mind being used as an example here—haha!)

Here is an example of what I did:

<img width="1288" alt="Experience Prompt" src="https://github.com/user-attachments/assets/ea0009c9-5bdf-486f-9dcd-54d5257e1593">
<img width="1018" alt="Soft Skills Prompt" src="https://github.com/user-attachments/assets/167aae4f-03f8-442b-8bbb-7daccb80a689">
<img width="1293" alt="Technical Skills Prompt" src="https://github.com/user-attachments/assets/3f926f1a-4fc5-415a-b6f7-76518bd60464">
<img width="2419" alt="Overview" src="https://github.com/user-attachments/assets/6d646121-c73d-4f58-ba74-d7155a811247">

## Coding Method

While the no-coding method was a great way to streamline the process, I wanted to use my coding skills to gain a deeper understanding of how to connect to APIs and practise coding in a real-world scenario.

Here’s how I did it:

Add a Script in Google Sheets:
First, go to the Extensions menu and choose the option to add a script editor, as shown in the image below:

<img width="389" alt="Extensions" src="https://github.com/user-attachments/assets/486942dc-1fd9-4be9-9316-fc395b04450f">

Open the Script Editor:
In the script editor, you can start writing your code. This is where you’ll connect to the API and manipulate data.

<img width="755" alt="Code" src="https://github.com/user-attachments/assets/ca600bec-1829-4990-96e7-2e9d453fb72d">

Example Script:
Here’s an example of what the script editor looks like once you’ve written your code:

<img width="1097" alt="Example" src="https://github.com/user-attachments/assets/ce1174a0-30e9-4b39-8615-1350203056b7">

API Overview:
The API I connected to provided a range of functionality that allowed me to automatically pull job details into my spreadsheet. This not only saved time but also improved the accuracy of the information I was tracking

<img width="1779" alt="Api Overview" src="https://github.com/user-attachments/assets/76caf0c5-306e-443a-a366-e5f1f61c2574">
