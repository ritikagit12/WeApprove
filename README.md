# WeApprove – Loan Approval Prediction System  

## Project Overview  
WeApprove is an AI-powered loan approval prediction system that helps users determine their loan eligibility based on key financial and personal details. It leverages machine learning to analyze user data and predict approval outcomes efficiently. The platform also features a smart NLP-based chatbot for assisting users and a real-time help desk chatbot for support.  

## Features  
- **Loan Eligibility Prediction**: AI/ML model-based prediction of loan approvals  
- **User Roles**: Admins, Loan Applicants  
- **NLP-based Chatbot**: Smart assistant to guide users through the loan application process  
- **Help Desk Chatbot**: Provides real-time support for user queries  
- **Secure Authentication**: User login and signup with JWT authentication  
- **Application Management**: Users can apply for loans and track their status  
- **Admin Dashboard**: Admins can manage applications, view analytics, and oversee system operations  

## Tech Stack  
- **Frontend**: React.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Machine Learning**: Python (Flask API for ML model), Scikit-learn, Pandas, NumPy  
- **Chatbot**: NLP-based chatbot using Dialogflow/Rasa  
- **Authentication**: JWT-based authentication  
- **Email Notifications**: Nodemailer  

## Installation Guide  
### Backend Setup  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-repo/WeApprove.git
   cd WeApprove  
   ```  
2. Install dependencies:  
   ```sh
   npm install  
   ```  
3. Set up environment variables (`.env` file) with MongoDB URI, JWT secret, and other keys.  
4. Start the backend server:  
   ```sh
   npm start  
   ```  

### Frontend Setup  
1. Navigate to the frontend directory:  
   ```sh
   cd client  
   ```  
2. Install dependencies:  
   ```sh
   npm install  
   ```  
3. Start the frontend server:  
   ```sh
   npm start  
   ```  

### Machine Learning API Setup  
1. Navigate to the ML model directory:  
   ```sh
   cd ml-model  
   ```  
2. Install Python dependencies:  
   ```sh
   pip install -r requirements.txt  
   ```  
3. Run the Flask server:  
   ```sh
   python app.py  
   ```  

## Usage  
- **Applicants**: Sign up, enter financial details, and receive loan predictions  
- **Admin**: Monitors applications, manages users, and oversees predictions  
- **Chatbot**: Assists users with loan-related queries and FAQs  

## Contribution  
- Fork the repository  
- Create a feature branch:  
  ```sh
  git checkout -b feature-name  
  ```  
- Commit changes and push to GitHub  
- Open a pull request  

## License  
This project is open-source under the MIT License.  

## Contact  
For queries or contributions, contact Ritika Shrivastava.
