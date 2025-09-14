A. What triggers this workflow to run? - Push to main.
B. What are the four main steps this workflow performs? - 
    •	Checkout
	•	Setup deployment
	•	Upload files
	•	Deploy
C. What does the "Checkout code" step do and why is it necessary? - Fetches the code from the repository so that subsequent steps can operate on it.
D. What is the purpose of the environment configuration? - Sets GitHub Pages as the deployment target.
E. How does this automated deployment improve reliability compared to manual deployment? - Eliminates human errors, is repeatable, and independent of manual actions. It also speeds up the development process by deploying changes instantly after approval.
F. What would happen if you pushed code to a different branch? - The workflow would not run.