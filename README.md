![Typing Animation](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00FF00&width=500&lines=Hi+there%2C+I'm+Aryan+Deshpande+%F0%9F%91%8B&center=true&repeat=true)

I’m a pre-final year B.Tech IT student at VIT Vellore with a strong interest in cloud computing, ML, cross-platform app development, and backend systems. Over the last couple of years, I’ve worked on projects ranging from mobile apps in Flutter to cloud-native pipelines on AWS, while also gaining hands-on experience with backend and ML frameworks.



## 🛠 Technologies & Tools

*Languages & Web*: C++, Python, Dart, SQL, HTML, CSS

*Cloud*: AWS (SageMaker AI, EC2, S3, Lambda, Glue, Athena, IAM)

*Backend & Databases*: Express.js, PostgreSQL, SQLPlus

*Frameworks & Libraries*: Flutter, Pandas, Matplotlib

*Tools*: Power BI, Postman, Git, Android Studio

*Certifications*: AWS Certified Cloud Practitioner - [Credential](https://cp.certmetrics.com/amazon/en/public/verify/credential/80cd8d2e71484067a23086ef76302ace), Generative AI using IBM Watsonx - [Credential](https://drive.google.com/file/d/1aWUVry3rcbPaR7BpjFLM3YnGW8KCAsbj/view?usp=drive_link)



## 📚 Projects


### [ML Pipeline on AWS](https://github.com/dshryn/etl-pipeline-aws) ☁️

Production-style ML (including ETL) pipeline that ingests flight-delay CSVs and implements a medallion architecture (Bronze - Silver - Gold) on S3 to enable reliable analytics and inference.

_Highlights:_

- **Medallion architecture:** Bronze - Silver - Gold layers on S3 for incremental refinement, data quality, and easier downstream consumption.  
- **Cost-efficient querying:** Athena CTAS/UNLOAD workflows using Parquet formats and partitioning for fast, low-cost queries.  
- **Modeling & serving:** XGBoost classifier (artifacts stored in S3) and deployed real-time inference via FastAPI, containerized with Docker, with an Nginx frontend on EC2. ([Serverless variant repo](https://github.com/dshryn/serverless-etl-aws)).  
- **Analyst access:** Exposed Gold tables to Power BI via Athena using the ODBC driver for self-service BI and reporting.

Tech Used: AWS S3, Athena, EC2, XGBoost, FastAPI, Docker, Nginx, Power BI (ODBC)



### [Hackulus'25 Backend Portal](https://github.com/dshryn/hackulus25-be-express) 🖥️
Official backend for Hackulus’25, SIAM-VIT’s flagship hackathon with 300+ participants.  

_Highlights:_

- **REST API Development:** Designed and deployed secure endpoints for managing tracks, submissions, and admin workflows.  
- **High Reliability:** Achieved >99% uptime and minimal runtime errors during the event through robust system design.  
- **Authentication & Validation:** Implemented JWT-based authentication, comprehensive input validation, and structured error handling.  
- **Deployment & Scalability:** Deployed on Render for real-time performance and smooth scalability during the hackathon.  

Tech Used: Node.js + Express.js (backend), PostgreSQL, REST APIs, JWT Authentication, Render



### [Geo PhotoVault App](https://github.com/dshryn/geo-photovault-app) 🌐📱
A smart photo vault app built with Flutter that automatically organizes images by location metadata.

*Key Features:*

- Auto-organization: Photos sorted into folders by city.
- Search: Retrieve images instantly with place-based keywords.
- Interactive Map: Explore all saved photos on a Google Maps interface.
- Themes: Light/dark theme support with persistent user preferences.

Tech Used: Flutter, image_picker, geolocator, Google Maps API, path_provider


### [Chemical Reaction Catalyst Prediction](https://github.com/dshryn/graph-catalyst-ml) 🔬⚗️  
ML system that predicts the most suitable catalyst for a given chemical reaction using graph-based molecular representations.

_Highlights:_

- **Graph-Based Machine Learning:** Utilizes Morgan fingerprints (via RDKit) to encode reaction SMILES from the ORDerly dataset.  
- **Full Preprocessing Pipeline:** Includes reaction cleaning, normalization, agent explosion, data balancing & malformed-line handling.  
- **Model Training Suite:** Custom training pipeline with adjustable fingerprint size, class weights, chunked loading and joblib-based artifacts.  
- **API + Frontend:** FastAPI backend with a minimalist frontend for quick catalyst predictions.  
- **Local Debugging:** CLI inference script for rapid testing with real Reaction SMILES.

**Tech Used:** RDKit, Scikit-learn, FastAPI, Uvicorn, Pandas, NumPy, Joblib, Morgan Fingerprints, ORDerly Dataset




### Playlist Converter App 🎧🔁
A cross-platform app that lets users transfer playlists between Spotify, YouTube Music, and SoundCloud. (In progress)

_Highlights:_

- Multi-platform Support: Secure auth and playlist selection for all three music services.
- Filtering & Transfer: Easy-to-use UI for selecting and transferring playlists.
- Backend: REST API built with Express.js + PostgreSQL for secure handling.
- Status Tracking: Displays auth and sync status for each music service.

Tech Used: Flutter, Node.js + Express.js (backend), PostgreSQL, REST APIs



Kindly [visit my repositories](https://github.com/dshryn?tab=repositories) for more such projects.



## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=dshryn&show_icons=true&title_color=00BFFF&icon_color=00BFFF&text_color=ffffff&bg_color=0d1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dshryn&layout=compact&title_color=00BFFF&text_color=ffffff&bg_color=0d1117)

![GitHub Streak](https://streak-stats.demolab.com?user=dshryn&theme=dark&ring=00BFFF&fire=00BFFF&currStreakLabel=00BFFF&background=0D1117&dates=ffffff)



## 📫 Contact

- *Email*: [dshryng@gmail.com](mailto:dshryng@gmail.com)
- *LinkedIn*: [Aryan Deshpande](https://www.linkedin.com/in/aryan-deshpande-aabb2228a/)

