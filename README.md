# **NER-Based Resume Ranking**  

## **Overview**  
This project implements **resume ranking** using **Named Entity Recognition (NER)** with **SpaCy**, extracting key information from resumes and job descriptions to match candidates with job requirements efficiently.  

## **Features**  
✅ Extracts and categorizes entities from resumes and job descriptions (e.g., **DIPLOME, CERTIFICATION, POSTE, EXPERIENCE, COMPETENCES, CONTACT**).  
✅ Computes **cosine similarity** to rank resumes based on extracted keywords.  
✅ Supports **French & English** resumes and job descriptions.  
✅ Provides a structured output for **recruiters** to make data-driven hiring decisions.  

## **Technology Stack**  
- **Python** (Core implementation)  
- **SpaCy** (NER model for entity recognition)  
- **Scikit-learn** (Cosine similarity for ranking)  
- **PDF Extractor** (To process resumes)  

## **Installation & Setup**  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/NER-based-resume-ranking.git
   cd NER-based-resume-ranking
   ```  
2. **Run the main script**:  
   ```bash
   python main.py
   ```  

## **Usage**  
1. Upload multiple resumes (PDF format).  
2. Extract text and apply **NER model**.  
3. Compute similarity scores between resumes and job descriptions.  
4. Get a **ranked list of resumes** based on relevance.  

## **Future Enhancements**  
🔹 Allow recruiters to **assign weights** to keywords for better ranking.  
🔹 Integrate with a **full recruitment platform** (including online interviews).  
🔹 Add **visualization & dashboard** for better insights.  

## **Contributors**  
👤 **Abdelhakim Azelag** – *AI & Data Engineering Student*  

📌 **Feel free to contribute!** Open an issue or submit a pull request. 🚀  
