# 🏆 Zwickly — University Engagement Platform
> (Scroll down for screenshots)
# 
> 🥇 **Hackathon Winner** in the Engagement Category (2025)  
> A full-stack university engagement platform built to unify student life at a German university — from timetable and Mensa menus to events, trams, and AI-powered features.

---

## 🚀 Overview

**Zwickly** is a full-stack platform designed to bring together everything a student needs in one place — **student portal**, **admin dashboard**, and an **AI-enabled chatbot**.

Our goal was to make the **German university experience digital, interactive, and fun** — similar to how social platforms connect people, Zwickly connects students with their campus.

---

## 🧩 Core Features

### 🎓 Student Portal
- 📅 **Real-Time Timetable** — Extracted via scraping APIs from the university website.  
- 🍽️ **Mensa Menu Integration** — Live daily menus from the university dining API.  
- 🚋 **Transport Updates (VMS API)** — Real-time tram schedules to the city center.  
- 📢 **Campus Events** — View, register, and explore trending events by category (Career, Music, Sports, etc.).  
- 📚 **German Word of the Day** — Learn new German words with meanings for cultural integration.  
- 🧾 **Upcoming Exams & Campus News** — Pulled dynamically from university APIs.  
- 🧍‍♂️ **MySpace (Student Requests)** — Students can send event proposals to the admin for approval.

---

### ⚙️ Admin Portal
- 📊 **Comprehensive Analytics Dashboard**  
  - Total users, events, likes, prosts (posts), and engagement metrics.  
  - Data connected to **PostgreSQL backend** via **Supabase**.  
- 🗂️ **Event Management System**  
  - Approve student-requested events.  
  - Create or edit events directly.  
  - Manage campus data and analytics with ease.

---

### 🤖 Chatbot Portal
- 💬 **AI-Driven Chatbot** connected to the entire university dataset.  
- ⚙️ Powered by **GROQ API** and **Supabase Edge Functions**.  
- 🧠 Handles queries about timetables, Mensa, events, trams, and more — providing a smooth conversational experience for students.

---

### 🧠 AI Integration — RCNN Prost Detector
- 🥤 Users can upload an image of themselves with a beverage (bottle/mug).  
- 🔍 Our **RCNN model (via OpenCV)** detects the beverage.  
- 👍 If detected, it automatically increments the “prost” (cheers) count.  
- 🎯 Purpose: To encourage social engagement and sustainable habits through gamification.

---

## 🏗️ Tech Stack

### 💻 Frontend
- **React**  
- **JavaScript / TypeScript**
- **HTML / TailwindCSS**
- **Supabase Edge Functions (for chatbot & event integrations)**
- **Some of the frontend template was implemented via Loveable for faster implementation**

### 🗄️ Backend
- **Supabase** (for Authentication, APIs, and PostgreSQL Database)
- **PostgreSQL** (Database schema and analytics storage)
- **OpenCV + RCNN** (Prost detection system)
- **Python (OpenCV / RCNN Model Integration)**
- **GROQ API** (for chatbot intelligence)
- **VMS Transport API** (Real-time tram data)
- **Custom scraping APIs** (for timetable, Mensa, and event data)

---

## 🧑‍💻 My Contributions (Dhruvkumar Bhavinbhai Patel)

- 🧩 Designed and implemented **database schema** in **PostgreSQL**.  
- 🔌 Integrated the **backend with Supabase** for authentication and data handling.  
- 🧠 Implemented **R-CNN model integration** with **OpenCV** for prost detection.  
- 💬 Developed **chatbot functions** and integrated **GROQ API** using **Supabase edge functions**.  
- 🖥️ Contributed to **frontend development** (Lovable framework).  
- 📊 Created the **complete analytics dashboard** and connected it with the backend.  

---

## 📱 Screenshots
Student and Admin portal :
<img width="1413" height="901" alt="image (4)" src="https://github.com/user-attachments/assets/491592fc-273f-4f32-a055-b73f348a73ac" />
<img width="1408" height="802" alt="image (5)" src="https://github.com/user-attachments/assets/942f7d5b-d818-4295-8d75-283af7ae9728" />
<img width="1149" height="838" alt="image (7)" src="https://github.com/user-attachments/assets/1ef0e2c6-a102-4690-bdd6-83e58c1fb693" />
<img width="1710" height="818" alt="image (1)" src="https://github.com/user-attachments/assets/e41b26c9-809e-47ea-8cf2-946521716df2" />
<img width="1326" height="625" alt="image (8)" src="https://github.com/user-attachments/assets/aaa672f7-5360-4fd3-bfa5-4e27d49c3e3c" />
<img width="1340" height="459" alt="image (9)" src="https://github.com/user-attachments/assets/a7b1d694-2f60-4160-ad50-84bda86bb450" />
<img width="1366" height="441" alt="image (11)" src="https://github.com/user-attachments/assets/44eb25ab-b9ee-4653-ac6a-2011ed93396b" />
Chatbot :

<img width="928" height="530" alt="image (10)" src="https://github.com/user-attachments/assets/b7f6a7a4-e16e-4962-9afd-229f24256ee9" />

