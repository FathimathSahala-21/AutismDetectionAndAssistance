
# ADAS Web Dashboard 

This repository contains the web frontend and backend APIs for the **Autism Detection and Assistance System (ADAS)**. It offers a seamless platform for screening, monitoring emotional states, and receiving AI-generated support.

## Features

-  Upload images for autism screening
-  Fill autism questionnaire (AQ-10)
-  View test and diagnosis results
-  Experts can chat with parents, and review results
-  Recommends Personalized study materials 

## Tech Stack

- **Frontend**: HTML, CSS, Bootstrap, JavaScript, jQuery
- **Backend**: Python, Django, Django REST Framework
- **Chatbot**: LangChain + LangGraph + LLMs
- **Database**: MySQL

## Folder Overview

```
📂 autism-web
 ┣ 📁 templates/
 ┣ 📁 static/
 ┣ 📁 expert_chat/
 ┣ 📄 views.py
 ┣ 📄 models.py
 ┣ 📄 urls.py
 ┣ 📄 emotion_view.py
```

## Setup Guide

1. Clone repo:
   ```bash
   git clone https://github.com/FizzaSadath/autism-web.git
   cd autism-web
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run server:
   ```bash
   python manage.py runserver
   ```


## Connected Modules

- [`autism-video`](https://github.com/FathimathSahala-21/autism-video)
- [`autism-flutter-part`](https://github.com/FathimathSahala-21/autism-flutter-part)
- [`autism-web`](https://github.com/FathimathSahala-21/autism-web)
