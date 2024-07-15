
# ResumeSmart Evaluator
![ResumeSmart Evaluator](https://raw.githubusercontent.com/arnab-4/ATS_Resume_Expert/main/Jobmatch-analyzer.jpg)

The **ResumeSmart Evaluator** is an AI-powered tool that analyzes resumes and job descriptions, providing valuable insights to job seekers. Here's what it offers:
## Features

1. **Resume Parsing and Analysis:**
   - Extracts key information from uploaded resumes (in PDF format).
   - Analyzes the content, including skills, experience, and education.

2. **Job Description Analysis:**
   - Processes and understands the requirements specified in a job description.
   - Identifies keywords and critical skills sought by employers.

3. **AI-Powered Matching:**
   - Utilizes the powerful Gemini Pro Vision model to determine compatibility between the resume and the job description.
   - Calculates a percentage match score.

4. **Detailed Feedback:**
   - Provides insights into the resume's strengths and weaknesses.
   - Offers suggestions for improvement, such as formatting enhancements or additional relevant details.

5. **User-Friendly Interface:**
   - Built using Streamlit, ensuring a simple and intuitive experience for users.

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/ResumeSmart-Evaluator.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd ResumeSmart-Evaluator
   ```

3. **Set Up a Virtual Environment (Recommended):**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

4. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Obtain a Google Gemini API Key:**
   - Visit [Google's GenerativeAI](https://developers.generativeai.google) to get your API key.

6. **Set Up Environment Variable:**
   - Create a `.env` file in the root directory and add your API key:
     ```
     API_KEY=your_gemini_api_key_here
     ```

7. **Run the Application:**
   ```bash
   streamlit run ats.py
   ```

## Usage

1. Access the application by opening your web browser and navigating to the address displayed in your terminal after running the application (usually http://localhost:8501).
2. Input the job description by pasting it into the provided text area.
3. Upload your resume (PDF format only) by clicking "Browse files."
4. Click "Tell Me About the Resume" to receive a detailed analysis, including strengths, weaknesses, and improvement suggestions.
5. Click "Percentage Match" to see how well your resume aligns with the job description, along with any missing keywords.

## Disclaimer

This application is intended for informational purposes only. The analysis and feedback provided are based on AI interpretations and should not be considered a guarantee of job interview or offer success.

---

Feel free to customize this README further based on your project's specifics. Good luck with your **ResumeSmart Evaluator**! If you need any more assistance, just let me know. 😊

![ResumeSmart Evaluator Screenshot](https://raw.githubusercontent.com/arnab-4/ATS_Resume_Expert/main/Screenshot%202024-07-15%20171114.png)

Is there anything else you'd like to add or modify? 🚀
