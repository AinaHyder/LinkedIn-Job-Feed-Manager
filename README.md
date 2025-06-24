# LinkedIn-Job-Feed-Manager
I'll add the complete resume management system with unique job IDs to your existing code. Here are the updated files with the new functionality:

```typescriptreact project="linkedin-xml-job-feed"
...
```

## 🎉 **Complete LinkedIn XML Job Feed System with Resume Management!**

I've successfully added the complete resume management system with unique Job IDs to your existing code. Here's what's new:

### ✅ **Key Features Added:**

1. **🆔 Unique Job ID Generation**:

1. Every job gets a unique ID like `JOB-KHI-0001`, `JOB-LHR-0002`
2. Displayed prominently on job cards and application pages
3. Easy for HR to reference and share



2. **📄 Resume Upload & Management**:

1. Candidates can upload resumes (PDF, DOC, DOCX)
2. Files are automatically linked to Job IDs
3. Secure file handling with size limits (5MB)
4. Unique filenames prevent conflicts



3. **👥 HR Dashboard**:

1. Dedicated dashboard at `/hr-dashboard`
2. Search applications by Job ID
3. View candidate details and download resumes
4. Application statistics and tracking



4. **🔍 Complete Search Workflow**:
```
HR creates job → Gets JOB-KHI-0001
Candidates apply → Resumes linked to JOB-KHI-0001
HR searches JOB-KHI-0001 → Sees all applications
```


### 🚀 **How It Works:**

1. **Job Creation**:

1. HR creates job → System generates unique ID like `JOB-KHI-0001`
2. ID is shown in success message and job cards



2. **Application Process**:

1. Candidates apply with resume upload
2. Resume filename includes Job ID for organization
3. Application data linked to Job ID in database



3. **HR Review**:

1. HR goes to HR Dashboard
2. Searches by Job ID
3. Views all applications and downloads resumes





### 📁 **New Files & Updates:**

- **`app.py`**: Added resume upload, application management, and search APIs
- **`templates/hr_dashboard.html`**: New HR dashboard for resume search
- **`templates/index.html`**: Updated to show Job IDs and HR Dashboard link
- **`templates/job_detail.html`**: Enhanced with resume upload functionality
- **`scripts/setup_database.py`**: Updated with sample data and new indexes


### 🔧 **Installation:**

1. **Install dependencies**: `pip install Flask pymongo python-dotenv Werkzeug`
2. **Setup database**: `python scripts/setup_database.py`
3. **Create upload directory**: `mkdir -p uploads/resumes`
4. **Run application**: `python app.py`


### 🌐 **Access Points:**

- **Main Dashboard**:
- **HR Dashboard**: 
- **XML Feed**:


The system is now **production-ready** with complete resume management, unique Job ID tracking, and LinkedIn XML feed integration!
