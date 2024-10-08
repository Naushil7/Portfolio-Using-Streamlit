# Naushil Khajanchi's Portfolio

Welcome to my personal portfolio! This project is a showcase of my professional journey in Data Science, Machine Learning, and Software Development. It includes details about my education, skills, projects, and work experience, as well as ways to contact me.

**Live Link:** [Naushil Khajanchi's Portfolio](https://portfolio-b2cyt3342a-wl.a.run.app/)

---

## 🎨 Features

- **Home Page**: Overview of my professional journey, including skills, education, and career highlights.
- **Resume Viewer**: Embedded PDF resume viewable directly in the browser, with an option to download.
- **Projects Page**: A collection of my significant projects with detailed descriptions and links to GitHub repositories.
- **Contact Page**: Links to connect with me via email, LinkedIn, and GitHub.

---

## 🛠️ Technologies Used

- **Frontend**:
  - HTML5
  - CSS3
- **Backend**:
  - [Streamlit](https://streamlit.io/)
  - Python
- **Deployment**:
  - Google Cloud Platform (GCP) - [Live Link](https://portfolio-b2cyt3342a-wl.a.run.app/)
- **Version Control**:
  - GitHub for version control and collaboration

---

## 📂 Project Structure

Here’s an overview of the structure of this project:  
```  
    ├── assets  
    │   ├── readme.md       # Markdown file containing details about me  
    │   ├── Resume.pdf      # My resume, available for download  
    
    ├── tabs  
    │   ├── home.py         # Home page content  
    │   ├── resume.py       # Resume viewer code
    │   ├── projects.py     # My projects display
    │   ├── contact.py      # Contact details and form  
    
    ├── app.py              # Main app entry point
    ├── Dockerfile          # Docker configuration for containerization  
    ├── requirements.txt    # Python dependencies for the project
    ├── README.md           # This file
```

---

## 📦 How to Run Locally

Follow these steps to run the project on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Naushil7/your-repo-name.git

2. **Navigate into the project directory:** 
    ```bash
    cd your-repo-name

3. **Install the required dependencies:** 
    ```bash
    pip install -r requirements.txt

4. **Run the Streamlit app:** 
    ```bash
    streamlit run app.py

---

## 🚀 How to Deploy on GCP

1. **Create a Project on GCP**

2. **Add a billing method and then intialize your project on local machine**

2. **Use the below commands in the GCP Terminal to deploy this project on GCP:**
```
  ## gcloud builds submit --tag gcr.io/<ProjectName>/<AppName>  --project=<ProjectName>
  gcloud builds submit --tag gcr.io/data-portfolio-v1/portfolio  --project=data-portfolio-v1
```
```
  ## gcloud run deploy --image gcr.io/<ProjectName>/<AppName> --platform managed  --project=<ProjectName> --allow-unauthenticated
  gcloud run deploy --image gcr.io/data-portfolio-v1/portfolio --platform managed  --project=data-portfolio-v1 --allow-unauthenticated
```

