# CelonisAutomation

	Note: Node.js must be installed on the test machine

	Please follow the steps below to run the automation code using cypress
	
	1. Clone this repo in you local machine.
	2. Open Terminal and navigate to the root folder 'CelonisAutomation'.
	3. Run 'npm init'. Keep pressing enter for all the prompts.
	4. Run command 'npm install cypress --save-dev' in the terminal. (Note:This will install Cypress locally as a dev dependency for your project.)
	5. After installation is complete, run command 'npx cypress open'. (Note: The command might timeout after 30 seconds, especially when runnnig for the first 			time. Please re-run if this happens.)
	6. Either run the Test Specs under 'Celonis/Automation'. Either one by one by clicking on it. Or, Run them all using 'Run 5 integration specs' on top right.
	
	Note: Testcases A003, A004, and A005 will fail under suite 'Validate Celonis Login Page' due to defect 'D006'
