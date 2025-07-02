# Resume Tracker

A Natural Language Processing (NLP) web application built with Streamlit that classifies uploaded resumes (PDF, DOCX, TXT) into job categories using a trained Support Vector Machine (SVM) model and TF-IDF vectorization.

**Live Demo**: [resumetracker-j2fczttpyma3dqqmk7ism6.streamlit.app](https://resumetracker-j2fczttpyma3dqqmk7ism6.streamlit.app)

---

## 📌 Features

- Upload resumes in PDF, DOCX, or TXT formats.
- Automatic classification into predefined job categories.
- Utilizes TF-IDF vectorization for text processing.
- Employs a trained SVM model for accurate classification.
- Interactive and user-friendly interface powered by Streamlit.

---

## 🖼️ Screenshots

### Home Page
![Home Page](images/home_page.png)

### Upload Resume
![Upload Resume](images/upload_resume.png)

### Classification Result
![Classification Result](images/classification_result.png)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

```bash
git clone https://github.com/Arkya187/Resume_Tracker.git
cd Resume_Tracker
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

---

## 🧠 How It Works

1. **Resume Upload**: Users upload resumes.
2. **Text Extraction**: Text is extracted from the file.
3. **TF-IDF Vectorization**: Text is converted to numerical format.
4. **SVM Classification**: The trained model predicts the job category.
5. **Result Display**: The result is shown on the web app.

---

## 📂 Project Structure

```
Resume_Tracker/
├── app.py
├── Project.ipynb
├── UpdatedResumeDataSet.xls
├── clf.pkl.gz
├── encoder.pkl
├── tfidf.pkl
├── requirements.txt
├── README.md
└── images/
    ├── home_page.png
    ├── upload_resume.png
    └── classification_result.png
```

---

## 📊 Dataset

The project uses `UpdatedResumeDataSet.xls` containing resumes labeled with job roles.

---

## 🛠️ Technologies Used

- Python
- Streamlit
- scikit-learn
- pandas, NumPy
- PyPDF2, python-docx

---

## 📈 Future Enhancements

- Use BERT or advanced NLP models.
- Skill extraction.
- Resume storage with a database.
- Better UI and filters.

---

## 🤝 Contributing

Feel free to fork the repo and submit pull requests.

---

## 📄 License

This project is under the MIT License.
