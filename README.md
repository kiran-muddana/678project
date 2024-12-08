### **Setup Instructions for Food Safety Recall Analysis System**  

#### **Clone the Repository**  
```
git clone https://github.com/kiran-muddana/678project.git
cd 678project
```  

#### **Set Up Environment**  
1. **Install Python Dependencies**:  
   ```
   pip install -r requirements.txt
   ```  

2. **Set Environment Variables**:  
   Create a `.env` file in the project root and add the following configuration:  
   ```
   DB_USER=<your_mysql_username>
   DB_PASSWORD=<your_mysql_password>
   DB_HOST=<your_mysql_host>
   DB_NAME=<your_database_name>
   OPENAI_API_KEY=<your_openai_api_key>
   ```  
  

#### **Run the Application**  
1. Start the application using Streamlit:  
   ```
   streamlit run .\app.py
   ```  

2. Open the system interface through the URL provided in the terminal after running the application.  
