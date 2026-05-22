# my_career_coach
UI Layer: Responsible for handling all frontend functionality using React, operating within a web-based environment to deliver user interaction and presentation.

Logic Core: Manages the backend processing and system intelligence using Python. It orchestrates all core logic, including data processing through a large language model (Gemini), which is treated as a black-box reasoning engine for generating outputs.


Structure:

MY_CAREER_COACH/
├── logic_core/
│   ├── main.py
│   ├── authentication.py
│   ├── resume_upload.py          
│   ├── LLMprocessing.py
│   ├── report.py
│   └── datastore.py
│
└── UI/
    ├── App.js
    ├── Screens/
        ├── login_screen.js
        ├── resumeupload.js
        └── dashboard.js
           