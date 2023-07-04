Steps

1. Install python3 from https://www.python.org/downloads/
2. Create Virtual environment
   - python3 -m venv custom-gpt
   - cd custom-gpt

     // FOR WINDOW
   - bin/activate.bat

     // FOR LINUX/MAC
   - source bin/activate.bat
3. Clone repo
   - git clone https://github.com/nainglynndw/custom-chatGpt-OwnKnowledgeBase.git
4. Install Deps
   - cd custom-chatGpt-OwnKnowledgeBase
   - pip3 install -r requirements
5. Create openai api_key
   - Go to https://platform.openai.com/
   - Create an account
   - Go to Profile
   - Go to API KEYS
   - Create an API KEY
   - COPY API KEY
6. Update API KEY in app.py
   - Open app.py
   - Replace xxxxxxxxxxxxxxxxxxxxxxx with your {API_KEY}
7. Copy Your pdfs into "docs" folder
8. Run the custom-gpt
   - python3 app.py
9. Open Local URL in the log
