<h1 align="center">Hi 👋, I'm Anthony</h1>

<p align="center">
  <b>Software Engineer | Backend, Cloud & AI Systems</b>
</p>

I'm a software engineer and University of Toronto Computer Science & Mathematics graduate based in Toronto.

I currently work on production cloud and automation systems in financial services, with experience across Python, AWS, Snowflake, Terraform, CI/CD, backend development, and AI-enabled workflows.

Outside of work, I enjoy building projects involving automation, machine learning, data, and software systems. I also like playing games like Animal Crossing :)

---

# 🚀 Featured Projects

## 💰 PersonalFinanceApp

PersonalFinanceApp is a local-first personal finance platform I built to aggregate, organize, and analyze my financial data while keeping sensitive information under my control.

It has evolved from a budgeting dashboard into a broader personal financial system with:

- 🏦 **Account & transaction management** with Plaid synchronization and CSV imports
- 🧠 **Rule-based + AI-assisted cleanup** for transaction categorization and merchant normalization
- 🏪 **Canonical merchant management** with aliases, merge/split workflows, matching rules, and merchant logos
- 📊 **Financial analytics** for spending, income, cash flow, savings rate, budgets, trends, and period-over-period insights
- 🔁 **Recurring transaction detection** using cadence, merchant, and amount-pattern analysis
- 📈 **Investment tracking** with RBC Direct Investing PDF statement imports, holdings, portfolio history, allocation, contributions, and investment income
- 💵 **Monthly budgeting** with category-level progress and spending exclusions
- 🔐 **Local-first architecture** with encrypted financial integration credentials and separate sandbox/production data

**Tech:** Next.js · React · TypeScript · Tailwind CSS · FastAPI · Python · SQLAlchemy · SQLite · Alembic · Plaid · Pydantic · Recharts · Pytest · Vitest

## 📈 StockAlertSystem

An automated stock and ETF monitoring system that evaluates configurable technical-analysis rules and sends actionable alerts to Discord.

* Built a **configuration-driven rules engine** for monitoring stocks and ETFs using indicators including RSI, 50/200-day moving averages, and 52-week highs.
* Defined separate buy, sell-watch, trend-weakness, and drawdown conditions using composable `all` / `any` rule logic.
* Automated market monitoring with **GitHub Actions**, retrieving price history through Yahoo Finance and evaluating conditions on scheduled runs.
* Integrated **Discord webhooks** to deliver alerts and daily market open/close price summaries to a private channel.
* Implemented persistent state, alert fingerprinting, and configurable cooldowns to prevent duplicate or excessive notifications.
* Designed the system around YAML configuration so symbols, rule thresholds, data intervals, and messages can be changed without modifying application logic.
* **Tech Stack:** Python, pandas, yfinance, GitHub Actions, Discord Webhooks, YAML, REST APIs

## 🏝️ Animal Crossing Villager Popularity Prediction & Recommender

A machine learning application that predicts villager popularity and generates personalized recommendations for *Animal Crossing: New Horizons*.

* Combined structured villager metadata with **CLIP image embeddings** to build multimodal popularity-prediction models.
* Engineered preprocessing pipelines using categorical encoding, feature scaling, PCA, and visual embeddings.
* Built a similarity-based recommendation system that generates suggestions from a user's favorite villagers.
* Developed an interactive **Streamlit** application for exploring predictions, model configurations, and recommendations.
* **Tech Stack:** Python, pandas, scikit-learn, CLIP, Streamlit, NumPy

## 📷 Cilindir — 3D Reconstruction / VR

A university software-engineering project developed in collaboration with a startup exploring immersive remote collaboration.

* Worked in a team of 7 across pose estimation, 3D reconstruction, and Unreal Engine development.
* Built part of a pipeline for transforming camera-based pose data into realistic 3D human models using **PIFuHD**.
* Integrated computer-vision and 3D reconstruction tooling toward creating lifelike avatars for virtual meetings.
* **Tech Stack:** Python, PyTorch, PIFuHD, COLMAP, OpenCV

---

# 🛠️ Other Projects

## 📚 Bargain Bin Quizlet

A Java flashcard study application with authentication, flashcard management, public set discovery, and quizzes.

**Tech Stack:** Java

## 🌱 ProtoPlant

An Arduino-powered agricultural robot that monitors soil temperature, humidity, and light conditions and displays measurements through a web dashboard.

**Tech Stack:** Python, Arduino, JavaScript, HTML/CSS

## 🎲 Chinese Checkers AI

A Java implementation of Chinese Checkers featuring an AI opponent using board evaluation and best-move selection.

**Tech Stack:** Java

## 👽 Untitled Maze Game

A 3D sci-fi horror game featuring raycasting, A* pathfinding, and networked multiplayer.

**Tech Stack:** Java

---

# 💻 Technologies

**Languages:** Python, Java, SQL, JavaScript/TypeScript, C#, C++

**Cloud & DevOps:** AWS, Terraform, GitLab CI/CD, GitHub Actions, Docker, Linux

**Data & Backend:** Snowflake, PostgreSQL, MySQL, REST APIs, ETL & data pipelines

**AI / ML:** Amazon Bedrock, SageMaker, Textract, Comprehend, scikit-learn, PyTorch, CLIP

**Frontend:** React, Streamlit

---

# 📫 Connect

* [LinkedIn](https://www.linkedin.com/in/anthony-chen-ca/)
* [GitHub](https://github.com/anthony-chen-ca)

Thanks for stopping by! 👋
