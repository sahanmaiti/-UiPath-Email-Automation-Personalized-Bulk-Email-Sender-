📧 Automated Email Sender using UiPath

Mini Project – Empowering Automation
Created with using UiPath

🚀 Overview

This UiPath mini-project automates the process of sending personalized emails to multiple recipients using data stored in an Excel file. It eliminates the need for manual email composition, reduces human error, and significantly speeds up communication for HR teams, marketing departments, or anyone who deals with bulk emailing.

✅ Built as part of the Empowering Automation initiative.

⸻

🧠 Problem Statement

In many organizations, HR departments need to send individual emails to employees regarding updates, onboarding, or announcements. Manually drafting each email is time-consuming and error-prone.

💡 This project solves that by:
	•	Reading names and email addresses from an Excel sheet
	•	Automatically sending customized emails
	•	Logging email status back into Excel

⸻

✨ Features
	•	📊 Reads employee data (Name & Email) from Excel
	•	✉️ Sends personalized emails using Outlook or SMTP
	•	🔁 Loops through each recipient automatically
	•	✅ Marks status (“Sent”/“Failed”) and timestamp in Excel
	•	🔐 Secure credential handling using UiPath Assets or Windows Credential Manager
	•	📄 Optional email templates for flexible content

⸻

🛠️ Technologies Used
	•	UiPath Studio (tested on 2023.10 or above)
	•	Excel Application Scope
	•	Send Outlook Mail Message / Send SMTP Mail Message
	•	Secure Credentials (via Windows or Orchestrator)
	•	VB.NET for dynamic message generation

⸻

📂 Folder Structure

📦 AutomatedEmailSender
├── Data/
│   └── EmployeeList.xlsx           # Input Excel file with Name and Email columns
├── Assets/
│   └── EmailTemplate.txt           # Optional: dynamic email body
├── Screenshots/                    # Optional: for GitHub preview
├── Main.xaml                       # Main UiPath workflow
└── README.md                       # You’re reading it!


⸻

📥 How to Use
	1.	Clone or download this repository.
	2.	Open Main.xaml in UiPath Studio.
	3.	Modify the file path of the Excel sheet inside Excel Application Scope.
	4.	Optionally update EmailTemplate.txt with your custom message. Use placeholders like .
	5.	Configure your preferred email method:
	•	For Outlook: Ensure Outlook is installed and logged in.
	•	For SMTP (e.g., Gmail): Enable “Less Secure Apps” or use an App Password.
	6.	Run the workflow.

⸻

📝 Example Email Template (Assets/EmailTemplate.txt)

Hi <Name>,

Hope you're doing well!

This is a personalized email sent to you via UiPath automation.

Best regards,  
Your Company HR Team


⸻

🔧 Customization Options
	•	Add more columns like Department, Joining Date and use them in the email body
	•	Send attachments dynamically
	•	Add CC/BCC recipients
	•	Use HTML email body for richer formatting

⸻

🧪 Test Data Example (EmployeeList.xlsx)

Name	Email
John Doe	john.doe@example.com
Priya Shah	priya.shah@example.com


⸻

📌 Best Practices
	•	Avoid hardcoding credentials – use UiPath Assets or Windows Credential Store
	•	Use Try-Catch blocks for better error handling
	•	Log activities using Write Line or Log Message for debugging

⸻

📸 Screenshots

(Optional: Upload screenshots to the Screenshots folder and display them using markdown below)

⸻

🏁 Outcome
	•	✅ 100% accuracy in sending personalized emails
	•	⏱️ Reduced time and manual effort
	•	📈 Increased efficiency in communication processes

⸻

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

⸻

📃 License

This project is licensed under the MIT License.

⸻
