# 👋 Hi! I'm Hieu (Calvin) Hoang.

I’m a **data science enthusiast** with a strong foundation in **machine learning and AI** and a passion for leveraging data to solve real-world problems.  

- 🎓 **Senior at UC Davis**, pursuing a **B.S. in Statistical Data Science** with a **Minor in Technology Management**.  
- 📊 **Data Science Coordinator @ ASUCD Pantry**, optimizing food inventory with predictive modeling.  
- 🌍 **Youth Advisory Council Member @ JFF**, working to enhance career navigation tools for young adults.  
- 💡 Currently learning about **AI Agents and Generative AI** to explore their potential in automation and decision-making.  
- 🔍 Interested in **machine learning, data visualization, and applied AI in healthcare, business, and technology**.  

🌟 Always open to connecting and collaborating—feel free to reach out! 🚀  

---

## 🛠 Projects:

- **[Oprina: Conversational AI Avatar Assistant](https://devpost.com/software/oprina-conversational-ai-avatar-assistant?ref_content=user-portfolio&ref_feature=in_progress)**
  - **Inspiration:**
    - Create a voice assistant with a lifelike avatar that handles email and calendar through natural conversation, designed for hands-free productivity with a smooth, reliable experience.
  - **What it does:**
    - Provides a conversational AI avatar assistant that manages email and calendar tasks through voice commands.
    - Features a lifelike avatar interface for natural human-computer interaction.
    - Handles productivity tasks seamlessly without requiring manual input.
  - **How we built it:**
    - Developed using React and TypeScript for the frontend interface.
    - Implemented FastAPI with Python for the backend services.
    - Integrated Google ADK, Gmail API, and Google Calendar API for email and calendar management.
    - Utilized Vertex AI and Gemini 2.0 Flash for advanced AI capabilities.
    - Incorporated HeyGen API for avatar generation and animation.
    - Used Supabase for database management and Google Cloud for deployment.
  - **Key Features:**
    - Voice-activated email and calendar management
    - Lifelike AI avatar with natural conversation capabilities
    - Hands-free productivity workflow
    - Integration with Google services (Gmail, Calendar)
    - Real-time AI processing with Gemini 2.0 Flash
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=react,typescript,python,gcp" style="margin: 0 15px;"/>
      </a>
    </p>

- **[EpiAccess: Epidemic Forecasting & Healthcare Analysis Dashboard](https://github.com/calvinhoang203/EpiAccess)**
  - **Inspiration:**
    - Develop a comprehensive tool for analyzing infectious disease trends and understanding global healthcare access patterns to support educational research and emergency preparedness planning.
  - **What it does:**
    - Analyzes 63,115 real epidemic records from COVID-19, SARS, and Monkeypox outbreaks across 222 countries.
    - Generates 6-month epidemic forecasts using both traditional exponential smoothing and PyTorch neural networks with confidence intervals.
    - Clusters 175 countries into 4 distinct healthcare access categories using K-means algorithm based on health expenditure patterns.
    - Provides interactive disease mapping with choropleth and bubble visualizations.
    - Generates AI-powered insights in plain English with confidence scoring and trend analysis.
    - Features "what-if" scenario planning showing how historical outbreaks would unfold in 2025.
  - **How we built it:**
    - Built comprehensive data processing pipeline using Pandas to unify datasets from multiple sources (Kaggle, World Bank).
    - Implemented dual forecasting system: exponential smoothing for transparency and PyTorch neural networks for complex pattern recognition.
    - Developed healthcare access clustering using scikit-learn K-means with 3-year averaging (2020-2022) for pandemic stability.
    - Created interactive Streamlit dashboard with three main components: Disease Trends, Disease Map, and Healthcare Access Analysis.
    - Integrated Plotly for dynamic visualizations and implemented statistical analysis with correlation metrics and efficiency ratios.
  - **Key Outcomes:**
    - Successfully processed and analyzed 63,000+ epidemic records with real-time interactive visualizations.
    - Achieved reliable trend analysis for educational purposes with clear confidence scoring and limitation transparency.
    - Identified 4 distinct global healthcare access patterns: High Access-Advanced Economy, Medium-High Access-Developing, High Priority-Limited Resources, and Low Access-Resource Constrained.
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=vscode,python,sklearn" style="margin: 0 15px;"/>
      </a>
    </p>

- **[BrainBoost: Academic Success Coach](https://github.com/calvinhoang203/Brain-Boost-Academic-Success-Coach)**
  - **Inspiration:**
    - Provide students with a personalized, data-driven “coach” to track daily habits and predict academic performance.
  - **What it does:**
    - Allows users to input daily metrics—study hours, sleep hours, social activities, physical activity, extracurriculars, and screen time.
    - Predicts letter-grade category and stress level using a Gradient Boosting model (0.9087 overall accuracy) trained on 2,000+ student records.
    - Visualizes progress over time in an interactive Streamlit dashboard, showing habit history alongside predicted outcomes.
    - Generates tailored recommendations in three categories—“Study Strategy,” “Wellness,” and “Balance”—based on predicted grade gaps and stress levels.
    - Includes a simulation tab where users adjust habit sliders to see potential effects on predicted GPA and stress.
  - **Key Outcomes:**
    - Gradient Boosting model achieved 0.8175 letter-grade accuracy and 1.0000 stress-level accuracy, for an overall 0.9087 accuracy.
    - Empowered students to identify habit changes likely to improve GPA trajectories and manage stress effectively.
  - **How we built it:**
    - Preprocessed the Student Lifestyle Dataset (2,000 records) in Pandas; engineered features such as Study–Sleep interaction, Social–Study ratio, Total Activity, Study Efficiency, and Life Balance.
    - Trained multiple classifiers (Logistic Regression, Random Forest, XGBoost, Decision Tree, Gradient Boosting) in scikit-learn and saved the best-performing pipeline in `stacked_multioutput_predictor.pkl`.
    - Developed a Streamlit app (`app.py`) to load the model and a `StandardScaler` (`scaler.pkl`), capture user inputs, perform real-time feature engineering, and display predictions.
    - Built interactive tabs:
      1. **Input Habits:** Numeric inputs for six daily activities, interactive time-allocation progress bar, and “Critical” warnings for unrealistic inputs.
      2. **Progress:** Displays latest predicted grade, stress level, time-to-graduation estimate, plus a line chart and table of habit history.
      3. **Recommendations:** Provides personalized tips for improving study habits, wellness, and work-life balance, and includes interactive sliders so users can adjust daily habits and immediately see how those changes might impact their predicted GPA and stress levels.
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=vscode,python,sklearn,git" style="margin: 0 15px;"/>
      </a>
    </p>

- **[SHIPSmart](https://github.com/calvinhoang203/SHIPSmart)**
  - **Inspiration:**
    - Help UC SHIP students avoid surprise medical bills by estimating healthcare costs up front.
  - **What it does:**
    - Provides a real-time cost estimation and claims automation system.
    - Allows users to input plan details and claim data to calculate expected reimbursements.
    - Automates rebate processing to expedite refunds.
  - **How we built it:**
    - Co-developed during HackDavis 2025 with SwiftUI on iOS.
    - Integrated Python back-end logic and the Cerebras API for machine learning calculations.
    - Leveraged OpenAI/Gemini and SQL to process and analyze insurance data in real time.
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=swift,python,git" style="margin: 0 15px;"/>
      </a>
    </p>

- **[Aggie Reminder](https://github.com/calvinhoang203/Aggie-Reminder)**
  - **Inspiration:**
    - Enhance volunteer management and communication at Aggie House.
  - **What it does:**
    - Provides an admin portal to monitor volunteer work hours.
    - Sends automated email reminders via the SendGrid API.
    - Implements an automatic reminder feature using JavaScript in a Google Sheets App Script.
  - **How we built it:**
    - Developed with Node.js for server-side logic.
    - Built with HTML, CSS, and JavaScript for a responsive frontend.
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=vscode,nodejs,html,css,javascript" style="margin: 0 15px;"/>
      </a>
    </p>

- **[Pantry Tracking Website](https://pantry-tracking-website-7zzcmgcztslfzoswphhjgd.streamlit.app/)**
  - **Description:**
    - A web-based dashboard for tracking pantry inventory in real-time.
  - **How it works:**
    - Built with Python, allowing users to input, update, and visualize inventory data.
    - Efficiently manages distributed products and remaining stock.
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=vscode,python,css" style="margin: 0 15px;" />
      </a>
    </p>

- **[Exploring the Impact of Stroke, Heart Disease, and Diabetes on Mobility Challenges](https://github.com/calvinhoang203/Exploring-the-Impact-of-Stroke-Heart-Disease-and-Diabetes-on-Mobility-Challenges)**
  - **Project Overview:**
    - Uses the BRFSS 2015 dataset to analyze and predict heart disease indicators.
    - Leverages health metrics such as BMI, smoking habits, physical activity, and healthcare access.
  - **Inspiration:**
    - Motivated by the alarming prevalence of heart disease and the need for early intervention.
  - **Dataset Overview:**
    - Based on the Heart Disease Health Indicators from the 2015 BRFSS survey.
    - Consists of 22 columns covering health metrics, demographics, and lifestyle factors.
  - **Analysis Details:**
    - **Objectives:** Identify key predictors of heart disease, build and evaluate predictive models, and provide actionable insights.
    - **Methods:** Exploratory Data Analysis, Feature Engineering, and Model Building using algorithms like Logistic Regression and Random Forest.
    - **Results & Learnings:** Highlighted significant predictors (e.g., HighBP, HighChol) and gained insights into lifestyle impacts on heart disease risk.
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=anaconda,python,sklearn" style="margin: 0 15px;"/>
      </a>
    </p>

- **[Analysis-of-Amazon-Sales-Trend](https://github.com/calvinhoang203/Analysis-of-Amazon-Sales-Trend)**
  - **Project Overview:**
    - Conducts an in-depth analysis of customer behavior using the Amazon Sales Dataset.
    - Focuses on product review categories, review lengths, and their impact on product engagement.
  - **Key Questions Explored:**
    - What information does the dataset provide?
    - Which products are top-rated based on the number of ratings?
    - Is there a correlation between ratings count and average product rating?
    - Which products have the most discounted prices, and how do discounts relate to review counts?
    - What are the top products by click-through rates and by category?
    - How do review characteristics (e.g., length) correlate with product ratings?
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=anaconda,python" style="margin: 0 15px;"/>
      </a>
    </p>

- **[Marvel-Universe-Explorer](https://github.com/calvinhoang203/Marvel-Universe-Explorer)**
  - **Project Overview:**
    - A fun, interactive web project that dives into the Marvel Universe.
    - Retrieves data from the Marvel API to showcase characters, comics, and creators.
  - **Inspiration:**
    - Sparked by a childhood fascination with Marvel heroes and their incredible stories.
  - **Features:**
    - **Home:** Introductory section guiding users through the site.
    - **Marvel Characters Gallery:** Displays characters with images and descriptions.
    - **Marvel Comics Gallery:** Lists comics with cover images, titles, and issue numbers.
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=vscode,html,css,javascript" style="margin: 0 15px;"/>
      </a>
    </p>

- **[MealBuddy](https://github.com/calvinhoang203/MealBuddy)**
  - **Overview:**
    - An AI-powered meal planning app designed to help users track ingredients, generate personalized meal suggestions, and monitor nutritional intake.
  - **Features (In Progress):**
    - **Ingredient Tracking:** Search, add, edit, and delete ingredients with nutritional breakdown (calories, protein, fats, water, sugar).
    - **AI-Powered Chatbot:** Provides recipe suggestions using Google Gemini AI based on user-provided ingredients, with integrated YouTube video links for cooking instructions.
    - **Dynamic Dashboards:** Displays nutritional summaries with circular trackers and pie charts for calories, water, protein, carbs, and fats.
    - **Profile Management:** Manage user data (name, age, gender, height, weight) with authentication through Firebase and Google Sign-In, including password reset and logout functionality.
    - **Searchable Fridge Inventory:** Filter and manage stored ingredients with real-time updates using Firestore snapshot listeners.
    - **Themed UI:** Automatically adapts to system light/dark themes using a custom color scheme.
  - **Tech Stack:**
    - **Frontend:** React Native, HTML, CSS, JavaScript, TypeScript.
    - **Backend:** Firebase for authentication and database management, Google Gemini API for AI integration.
    - **AI Integration:** Google Gemini API for personalized meal recommendations and YouTube Data API for video retrieval.
  - **Technologies used:**  
    <p align="center">
      <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=vscode,react,firebase,html,css,javascript,typescript" style="margin: 0 15px;"/>
      </a>
    </p>

---

## 💻 Skills

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=anaconda,swift,gitlab,vscode,firebase,react,typescript,python,sklearn,javascript,nodejs,html,css,git,github" style="margin: 0 15px;" alt="Skills" />
  </a>
</p>

---

## 📊 GitHub Stats:

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=calvinhoang203&show_icons=true&theme=radical&hide_border=false&count_private=true" alt="GitHub Stats" height="180em" />
  <img src="https://streak-stats.demolab.com/?user=calvinhoang203&theme=radical&hide_border=false" alt="GitHub Streak" height="180em" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=calvinhoang203&layout=compact&theme=radical&hide_border=false&langs_count=6" alt="Top Languages" height="180em" />
</p>

---

## 📫 Connect with Me:
- **GitHub**: [calvinhoang203](https://github.com/calvinhoang203)
- **LinkedIn**: [Hieu Hoang](https://linkedin.com/in/yourname)
