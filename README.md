# 🏥 MediRecommend

MediRecommend is a smart healthcare recommendation platform built using **Next.js and Google Maps API**. It helps users find nearby hospitals and suitable doctors based on their symptoms and location.

The platform simplifies healthcare discovery by combining geolocation services, medical data, and intelligent analysis.

---

## 🚀 Project Description

MediRecommend allows users to:

- Enter their symptoms for analysis
- Receive department recommendations
- Select their current or manual location
- View nearby hospitals sorted by distance
- Access hospital details and ratings
- Find relevant doctors

It reduces the time and confusion involved in choosing appropriate medical services.

---

## 🛠️ Tech Stack

- Frontend: Next.js (React)
- Backend: Next.js API Routes
- Styling: Tailwind CSS
- APIs:
  - Google Maps API
  - Google Places API
  - Google Geocoding API
- Language: TypeScript / JavaScript

---

## ✨ Features

1. 🧠 Symptom-based department recommendation  
2. 📍 Automatic and manual location detection  
3. 🏥 Distance-based hospital listing  
4. ⭐ Hospital ratings and details  
5. 👨‍⚕️ Doctor information display  
6. 🗺️ Live map integration  
7. 📞 Direct navigation and call support  

---

## 📂 Project Structure
## 📁 Project Structure

```
medirecommend/
│
├── app/
│   ├── api/
│   │   ├── geocode/
│   │   ├── hospitals/
│   │   ├── hospital-details/
│   │   └── symptoms/
│   │
│   ├── location/
│   │   └── page.tsx
│   │
│   ├── search/
│   │   └── page.tsx
│   │
│   ├── hospitals/
│   │   └── [id]/
│   │       └── page.tsx
│   │
│   ├── data/
│   │   └── doctors.ts
│   │
│   ├── lib/
│   │   └── haversine.ts
│   │
│   ├── layout.tsx
│   ├── page.tsx
│   └── globals.css
│
├── public/
├── .env
├── package.json
└── README.md
```


---

## 🔑 Environment Setup

Create a file named `.env.local` in the root folder:
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=your_google_maps_api_key


Enable the following APIs in Google Cloud Console:

- Maps JavaScript API  
- Places API  
- Geocoding API  

---

## ⚙️ Installation

Clone the repository:
git clone <[repository-link](https://github.com/Aardra06/medirecommend)>
cd medirecommend

Install dependencies:
npm inst
## ▶️ Run the Project
Start the development server:
npm run dev


Open in browser:
 https://medirecommend-g7om.vercel.app/
 # 🔄 Application Flow


User
↓
Enter Symptoms
↓
Department Recommendation
↓
Location Selection
↓
Nearby Hospital Search
↓
Hospital Details



![Home](https://raw.githubusercontent.com/Aardra06/medirecommend/main/1st%20pg.jpeg)

![Symptoms](https://raw.githubusercontent.com/Aardra06/medirecommend/main/2nd%20pg.jpeg)

![Hospitals](https://raw.githubusercontent.com/Aardra06/medirecommend/main/3rd%20pg.jpeg)

![Details](https://raw.githubusercontent.com/Aardra06/medirecommend/main/4th%20pg.jpeg)

## 🎥 Demo Video

Demo Video Link: https://drive.google.com/file/d/1YF3lZg-Gm52bISgF6y7nv65Pc_UjX1LR/view?usp=drive_link

## 📡 API Documentation
### 1. Geocode API
Endpoint:
/api/geocode?address=<location>
Purpose: Converts location name to latitude and longitude.

### 2. Hospitals API
Endpoint:
/api/hospitals?lat=<lat>&lng=<lng>&department=<dept>
Purpose: Fetches nearby hospitals based on location and department.

### 3. Hospital Details API
Endpoint:
/api/hospital-details?placeId=<id>


Purpose: Fetches detailed hospital information.

---

## 👨‍💻 Team Members

- Jaisy Sunil  
- Aardra SV

---

## 📜 License

This project is licensed under the MIT License.

---

## 🔮 Future Scope

- AI-based diagnosis using machine learning models
- Online appointment booking system
- Hospital review and feedback system
- Emergency nearest-hospital mode
- Multi-language support
- Real-time doctor availability tracking

---

## 🤖 AI Tools Used

- ChatGPT for development support
- Rule-based symptom analysis system

---

## ✅ Checklist Compliance

✔ Project description  
✔ Tech stack  
✔ Features  
✔ Installation steps  
✔ Run commands  
✔ Screenshots section  
✔ Demo video section  
✔ Architecture section  
✔ API documentation  
✔ Team details  

---

Made with ❤️ for Hackathon Submission
