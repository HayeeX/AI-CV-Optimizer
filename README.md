# AI-CV-Optimizer
An AI-powered tool to optimize your CV for any job description. Upload your resume, paste the job details, and get an ATS-friendly version in seconds. Helps you beat the bots and land more interviews. Powered by Google Gemini.

AI CV Optimizer
A simple, powerful web tool that helps you tailor your CV to any job description in seconds. This application uses Google's Gemini AI to analyze your current CV and a target job description, then generates an optimized version that is ATS-friendly and ready to impress recruiters.

Features
Easy File Upload: Upload your CV in .pdf, .docx, or .txt format.

AI-Powered Optimization: Pastes a job description and let the AI rewrite your CV to match the role's key requirements.

ATS-Friendly Formatting: The output is structured to be easily parsed by Applicant Tracking Systems.

Download as .docx: Export your newly optimized CV as a professionally formatted Microsoft Word document, ready to be sent out.

Client-Side Processing: All file parsing happens directly in your browser, ensuring your data remains private.

How to Use It Locally
Download the Code: Clone this repository or download the cv_optimizer.html file.

Get an API Key: You'll need a free API key from Google AI Studio.

Add the Key: Open cv_optimizer.html in a text editor and paste your API key into the designated spot:

const apiKey = "YOUR_API_KEY_GOES_HERE";

Open in Browser: Open the cv_optimizer.html file in any modern web browser.

Start Optimizing: Upload your CV, paste a job description, and click the "Optimize" button!

Technologies Used
HTML, CSS, JavaScript: The core of the application.

Tailwind CSS: For modern, responsive styling.

Google Gemini 2.5 Flash: The AI model powering the CV optimization.

Libraries:

pdf.js for parsing PDF files.

mammoth.js for parsing .docx files.

docx for generating .docx files.

This tool is intended to be a starting point. Always review and personalize the generated CV before submitting an application.
