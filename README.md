🧭 SmartCompass

SmartCompass is an AR and AI-powered persuasive indoor navigation system designed for university buildings. It combines Visual Positioning Systems (VPS), persuasive technology strategies, and AI-driven personalization to enhance wayfinding, engagement, and user experience.
<img width="377" height="754" alt="image" src="https://github.com/user-attachments/assets/23cccb6d-37a6-487b-b039-e99a056c3b3c" />
<img width="487" height="966" alt="image" src="https://github.com/user-attachments/assets/1707666a-fa1b-499c-b5d1-1ebdac4fa67a" />



🚀 Features

Augmented Reality Navigation

Real-time AR overlays with directional arrows.

Supports multi-floor navigation: if a POI is on another floor, SmartCompass guides users to the nearest elevator/stairs, switches the floor scene, and continues navigation.

Visual Positioning System (VPS)

Marker and environment-based tracking for accurate positioning indoors.

Dynamic path recalculation when users deviate from the route.

Persuasive Technology Integration

Uses strategies like reminders, rewards, personalization, and social influence to make navigation engaging.

Encourages exploration of POIs (e.g., libraries, labs, student services) with gamified nudges.

AI Personalization

Tracks frequently visited areas, time spent, and time-of-day patterns.

Recommends optimized routes and suggests POIs based on user habits.

Adapts difficulty and level of guidance for first-time vs. experienced users.

Data Tracking & Analytics

Connected to MongoDB Realm to log:

Places visited

Time spent per POI

Distance walked

Supports visual history stats:

Daily/weekly trends

Total distance covered

Number of POIs visited

Engagement Dashboard (Future)

Displays progress charts, milestones, and streaks.

Persuasive feedback loops to keep users active.

🏛 Use Case

SmartCompass is being developed for Dalhousie University buildings, but the framework can be adapted to malls, hospitals, airports, or corporate campuses.

🛠 Tech Stack

Frontend / AR Engine: Unity + MultiSet SDK

Database: MongoDB Realm (cloud sync)

AI & Personalization: Custom ML models for behavior tracking

Backend: Realm Functions + optional APIs for advanced analytics

Platforms: iOS & Android (Unity cross-platform build)
