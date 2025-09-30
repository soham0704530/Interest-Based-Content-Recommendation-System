📌 Interest-Based Content Recommendation System  

This repository contains my solution for the **ML Intern Assignment at AMBRIX**, focusing on building an **AI-powered lifestyle network recommendation system**.  
The project recommends the **top 3 posts for each user** by leveraging their profile interests, past engagement patterns, and content attributes.  

---

## 🚀 Project Overview  
- **Goal**: Recommend personalized content to users.  
- **Input Data**:  
  - **Users.csv** → User profiles with demographics & interests.  
  - **Posts.csv** → Post metadata and content attributes.  
  - **Engagements.csv** → Historical engagement logs (likes, comments, shares).  
- **Output**: A ranked list of **Top 3 recommended posts** per user.  

---

## ⚙️ Workflow  
1. **Data Loading & Exploration** – Load datasets and analyze structure.  
2. **Preprocessing** – Handle missing values, encode categorical features, and normalize attributes.  
3. **Feature Engineering** – Build user–post interaction features, content similarity, and engagement scores.  
4. **Recommendation Approach**  
   - **Content-Based Filtering** → Match users’ interests with post attributes.  
   - **Collaborative Filtering** → Learn from user–post engagement history.  
   - **Hybrid Ranking** → Combine signals to generate final recommendations.  
5. **Evaluation** – Metrics such as **Precision@K, Recall@K, and Hit Rate**.  
6. **Output** – Generate **Top-3 recommended posts** per user.  

---



# Navigate into the repository
cd <repo-name>
