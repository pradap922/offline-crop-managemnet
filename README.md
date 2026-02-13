# Offline-crop-managemnet

🌾 Offline Smart Crop Planner
An intelligent offline agricultural decision-support system that recommends suitable crops based on soil type and generates a complete crop lifecycle plan including sowing methods, fertilizer schedules, irrigation intervals, water requirements, and harvest timelines.

This project is built using Flask (Python) + HTML/CSS/JavaScript + JSON-based rule engine and works entirely offline.

🚀 Key Features
🌱 15 Major Soil Types Supported

🌾 Soil-Based Crop Recommendation

📋 Complete Crop Lifecycle Planning

🧪 Fertilizer Recommendation

💧 Water Level Classification (Low / Medium / High)

📅 Auto-Generated Irrigation Calendar

🖨️ Printable PDF Crop Plan

🔒 100% Offline System

⚙️ Rule-Based Logic Engine

🧠 System Workflow
Login
   ↓
Home
   ↓
Soil Selection (15 Types)
   ↓
Recommended Crops
   ↓
Crop Planner
   ├─ Sowing Method
   ├─ Crop Duration
   ├─ Fertilizer Schedule
   ├─ Water Requirement
   ├─ Irrigation Calendar
   └─ Harvest Time
🌍 Soil Types Covered
Red Soil

Black Soil

Alluvial Soil

Laterite Soil

Loamy Soil

Sandy Soil

Clay Soil

Peaty Soil

Saline Soil

Alkaline Soil

Forest Soil

Mountain Soil

Desert Soil

Marshy Soil

Chalky Soil

🌾 Crop Lifecycle Details Provided
For each crop, the system provides:

✔ Sowing Method

✔ Crop Period (Days)

✔ Fertilizer Used

✔ Water Requirement Level

✔ Irrigation Interval

✔ Auto-Generated Irrigation Schedule

✔ Harvest Time

🏗️ Project Architecture
Backend
Python

Flask REST API

JSON Data Storage

Rule-Based Crop Engine

Frontend
HTML5

CSS3

JavaScript

LocalStorage (State Handling)

Data Layer
soils.json

crops.json

planner.json

📂 Project Structure
offline-smart-crop-planner/
│
├── backend/
│   ├── app.py
│   └── data/
│       ├── soils.json
│       ├── crops.json
│       └── planner.json
│
├── frontend/
│   ├── login.html
│   ├── home.html
│   ├── soil.html
│   ├── crops.html
│   ├── planner.html
│   ├── css/
│   ├── js/
│   └── assets/
│
└── README.md
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/yourusername/offline-smart-crop-planner.git
cd offline-smart-crop-planner/backend
2️⃣ Install Dependencies
pip install flask
3️⃣ Run Application
python app.py
4️⃣ Open Browser
http://127.0.0.1:5000
🖨️ PDF Export
The planner page includes a built-in PDF export feature using browser print functionality.

Click "Download PDF"

Select "Save as PDF"

Save crop plan offline

🔒 Offline Capability
No Internet Required

No Database Server Required

No External APIs

Fully JSON-Based Data Storage

📊 Rule-Based Crop Logic
The system uses a rule engine:

Soil → Crop Mapping

Crop → Lifecycle Planning

Crop Period + Irrigation Interval → Irrigation Calendar Generation

This ensures structured and predictable agricultural planning.

🎓 Academic Use
This project demonstrates:

Full-Stack Development

REST API Design

JSON Data Management

Agricultural Technology Application

Rule-Based Logic Systems

Suitable for:

Final Year Projects

Agricultural Tech Demonstrations

Academic Submissions

🏷️ Technologies Used
Python

Flask

HTML

CSS

JavaScript

JSON

LocalStorage
