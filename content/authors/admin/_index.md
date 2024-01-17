---
# Display name
title: 吕志豪

# Name pronunciation (optional)
name_pronunciation: Zhihao Lyu

# Full name (for SEO)
first_name: Zhihao
last_name: Lyu

# Status emoji
status:
  icon: 😎

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Master Student Majoring in Computer Science

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Northeastern University
    url: https://www.northeastern.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: "mailto:lv.zh@northeastern.edu"
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/TotallyNewGuy
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/zhihao-lyu/

education:
  - area: Master of Science in Computer Science
    institution: Northeastern University
    date_start: 2020-09-01
    date_end: 2023-12-31
    summary: |
      GPA: 3.9/4.0

      Talk: _A Semantic Parsing Method for SQL using Large Language Models with Data Augmentation_ ([slides](https://docs.google.com/presentation/d/1p6mkSGGIAY6-vZUgrB0VX6h-uHQuTmW8ZNS6YAsKHnM/edit?usp=sharing)). Advised by Prof. [Jeongkyu Lee](https://www.khoury.northeastern.edu/people/jeongkyu-lee/).
    
      Thesis: _Using a Language Model's Perplexity for Evaluating a Trajectory's Outlierness_. Advised by Prof. [Mario Nascimento](https://www.khoury.northeastern.edu/people/mario-nascimento/) and Prof. [Michal Aibin](https://www.khoury.northeastern.edu/people/michal-aibin/).

    button:
      text: "Read Thesis"
      url: "https://totallynewguy.github.io/uploads/capstone_paper.pdf"

  - area: Bachelor of Engineer in Urban Planning
    institution: Beijing University of Civil Engineering & Architecture
    date_start: 2015-09-01
    date_end: 2020-06-30
    summary: |
      GPA: 3.5/4.0

      Courses included:
      - Urban and Rural Planning and Design
      - Urban Transportation Planning
      - Urban Geography
      - The Principle of Geographic Information System
work:
  - position: Capstone Research
    company_name: Northeastern University
    company_url: ""
    company_logo: ""
    date_start: 2023-08-01
    date_end: ""
    summary: |2-
      - Leveraged perplexity of large language models like BERT to identify trajectory outliers, contributing to the detection of taxi fraud or changes in self-driving car routes.
      - Constructed a customized vocabulary using over 50,000 GPS coordinates and created a adaptive mapping, which link coordinates to words using their spatial distribution and density.
      - Treated each trajectory as a sentence and employed a 7:3 split for training and testing data, introducing artificially missing and drifting coordinates to augment the training data.
      - Applied 16 × 16 road netwrok and relative position bias to enhance the model's spatial awareness. Training with Transformer encoder with BERT-style tasks achieved an ~0.8 accuracy and ~0.7 F1 score.
      - Calculated perplexity score of unseen trajectory, employing K-means for binary classification on scores to identify outliers. F1 score of the prediction results surpasses the state-of-the-art model by 9% to 16%.

  - position: Research Assistant
    company_name: MIT Transit Lab
    company_url: "https://www.transitlab.mit.edu/"
    company_logo: ""
    date_start: 2023-08-01
    date_end: ""
    summary: |
      - Collaborated with Chicago Transit Authority, funded by the Department of Energy, to address public transportation service reliability issues, employing machine learning algorithms for bus scheduling.
      - Established a cloud computing platform using Flask, Cloud Task and Cloud Functions in Google Cloud Platform to store and continuously update bus status, including GPS coordinates, speed, and arrival time.
      - Utilized Data Frame Algebra in Pandas to merge these real-time data and calculate service reliability metrics such as load balancing, waiting time, and cycle time. Updated bus scheduling strategy every minute, and offered a web application for experts to evaluate scheduling strategy using React.js.
      - Successfully operated the system for three researchers and dozens of dispatchers for months, collecting over 10,000 high-quality data points to improve algorithm performance.

  - position: Research Talk
    company_name: Northeastern University
    company_url: ""
    company_logo: ""
    date_start: 2023-07-01
    date_end: 2023-10-31
    summary: |
      -	Employed abstract syntax tree to parse SQL into various components and implemented a method for generating synthetic SQL based on adjustable semantic rules.
      -	Trained a large language model on the synthetic dataset to automate SQL segmentation and labeling, treating it as a Named Entity Recognition task.
      -	Introduced syntax errors and semantic errors into the dataset as data augmentation, strengthening the fault tolerance capability of the system.

  - position: Teaching Assistant
    company_name: Northeastern University
    company_url: ""
    company_logo: ""
    date_start: 2022-01-01
    date_end: ""
    summary: |
      -	Selected as a Teaching Assistant for 3 courses: Object-Oriented Design, Computer Network, and Algorithms.
      -	Conducted weekly office hours to address students' inquiries and provided assistance with their homework.
      -	Developed weekly assignments and laboratory exercises, evaluated homework, and graded exams.

  - position: Data Engineer Intern
    company_name: The Commons XR
    company_url: "https://thecommonsxr.com/"
    company_logo: ""
    date_start: 2023-01-01
    date_end: 2023-04-01
    summary: |
      -	Led two individuals from the product and data team to construct a metrics monitoring webpage (Azure base). Developed to resolve a long-standing data problem highlighted by the data team.
      -	Designed the UI/UX using TypeScript with MUI & React.js and embedded Power BI to provide real-time dashboards on the front end. Used JWT in cookies to deliver personalized data and Redis for caching, resulting in lightning-fast loading speeds.
      -	Built robust Restful APIs with Nest.js. Leveraged Spark and Python to subsample data, reducing the data volume in SQL Server by 70%, accelerating query speed, and greatly improving data team productivity.
      -	Utilized Stream Analytics to read data from the Event Hub. Employed windowing functions to subsample data from 30 to 0.5 msg/s, dramatically reducing the workload of browsers and databases.

  - position: Cloud Engineer Intern
    company_name: Sleep Number Lab
    company_url: "https://www.sleepnumber.com/"
    company_logo: ""
    date_start: 2022-05-01
    date_end: 2022-08-01
    summary: |
      -	Assisted the Cloud team (AWS based) in building a Distributed Data Platform to capture 1 billion bio-data daily using Spring and Kafka, including a real-time Data Transformation Pipeline (~1s lag) for the Machine Learning team from Kafka Connect to S3.
      -	Optimized an Lambda function with multiprocessing techniques, resulting in a 30% cost reduction and reducing the average processing time within the pipeline by 46%.
      -	Utilized SQL-like queries to extract and store data into DynamoDB and S3, triggered through EventBridge.
      -	Migrated MQTT brokers from self-managed servers to SaaS and developed an automation script for over 1 million IoT devices using Python for seamless provision in IoT Core through the usage of Cognito and IAM.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Java
        description: ""
        percent: 90
        # icon: code-bracket
      - name: Python
        description: ""
        percent: 90
        # icon: chart-bar
      - name: JavaScript
        description: ""
        percent: 80
        # icon: circle-stack
      - name: SQL
        description: ""
        percent: 70
        # icon: circle-stack
      - name: Spring
        description: ""
        percent: 85
        # icon: circle-stack
  - name: Research Interests
    color: "#eeac02"
    color_border: "#f0bf23"
    items:
      - name: Spatio-Temporal Data Mining
        description: ""
        percent: 100
        # icon: person-simple-walk
      - name: Intelligent Transportation
        description: ""
        percent: 90
        # icon: cat
      - name: Smart City
        description: ""
        percent: 80
      - name: Deep Learning
        description: ""
        percent: 80
      - name: IoT Network
        description: ""
        percent: 70

languages:
  - name: English
    percent: 80
  - name: Chinese
    percent: 98
# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
# awards:
#   - title: Neural Networks and Deep Learning
#     url: https://www.coursera.org/learn/neural-networks-deep-learning
#     date: "2023-11-25"
#     awarder: Coursera
#     icon: coursera
#     summary: |
#       I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.
#   - title: Blockchain Fundamentals
#     url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     date: "2023-07-01"
#     awarder: edX
#     icon: edx
#     summary: |
#       Learned:
#       - Synthesize your own blockchain solutions
#       - Gain an in-depth understanding of the specific mechanics of Bitcoin
#       - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm
#   - title: "Object-Oriented Programming in R"
#     url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
#     certificate_url: https://www.datacamp.com
#     date: "2023-01-21"
#     awarder: datacamp
#     icon: datacamp
#     summary: |
#       Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.
---

As a student with dual majors in Computer Science and Urban Planning , I am committed to integrating A.I. to enhance our living environment. I am set to graduate from Northeastern University this year and in the process of applying for a Ph.D. program as I aspire to advance further in my research journey.

Currently, I am serving as a research assistant at MIT Transit Lab, where I am working on utilizing machine learning to optimize bus dispatching. Recently, I am working on my capstone research, introducing a novel approach that enables accurate and efficient identification of trajectory outliers using Large Language Model.

My research interests are Spatio-Temporal Data Mining, Intelligent Transportation System, Smart City, Deep Learning, IoT Network and Cloud Computing.
