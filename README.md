# feynnlabs-code
#  AI-Powered Personalized Learning Path Generator

This project is an **AI-powered learning path generator** that recommends a personalized study roadmap for learners based on their skills, goals, and available time. It automatically selects courses from a catalog, ranks them according to relevance, and generates a week-by-week learning plan with interactive visualizations.

---

##  Features
-  **Learner Profile** → Define your current skills, weak areas, and target role.  
- **Course Catalog** → Input a catalog of courses with metadata (title, tags, level, duration).  
-  **Recommendation Engine** → Suggests best-fit courses using rule-based scoring (AI-ready for embeddings).  
- **Path Planner** → Generates a weekly learning plan based on available hours.  
- **Visualizations** (all visible inline in Colab):
  - Bar chart → Course vs. hours  
  - Line chart → Weekly time allocation  
  - Pie chart → Distribution of hours by course  
  - Gantt chart → Course schedule over weeks  

=== Recommendations ===
- Data Structures in C++ (1.00) → matches weak skill
- System Design Basics (1.00) → matches weak skill
- Intro to Python (0.50) → level aligned
- Machine Learning 101 (0.00) → generic match
- Deep Learning Foundations (0.00) → generic match

=== Weekly Path ===
Week 2: Data Structures in C++ — 15h
Week 3: System Design Basics — 20h
Week 4: Intro to Python — 10h
Week 5: Machine Learning 101 — 20h
Week 6: Deep Learning Foundations — 25h

