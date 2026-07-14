# Hack2Care 🚑

**Hack2Care** is a modern, AI-powered emergency response and first aid assistance platform designed to provide immediate guidance during critical situations, such as road accidents or medical emergencies.

### 🔗 Live Link
[**View Live Demo**](INSERT_LINK_HERE)

The application combines real-time patient assessment, AI-generated first aid instructions, and geolocation services to help bystanders provide life-saving support before professional medical help arrives.

## 🌟 Key Features

- **Emergency Logging**: Quickly report and log emergencies with precise GPS location.
- **AI First Aid Assistant**: Leverages Google Gemini AI to provide context-aware first aid instructions based on the patient's state (consciousness, breathing, bleeding).
- **Nearby Medical Facilities**: Automatically finds the closest hospitals, clinics, and pharmacies using the OpenStreetMap Overpass API.
- **Multilingual Support**: Built-in translation services to provide life-saving information in multiple languages.
- **Decision Tree Assessment**: A simple, guided interface to assess the victim's condition and determine the priority of care (Critical, Urgent, or Moderate).
- **Interactive Maps**: Visualize nearby medical help on an interactive map using Leaflet.

## 🛠️ Tech Stack

### Frontend
- **Framework**: React.js with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Components**: Radix UI
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Mapping**: Leaflet & React Leaflet
- **Data Fetching**: TanStack Query (React Query)
- **Routing**: Wouter

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Language**: TypeScript
- **ORM**: Drizzle ORM
- **AI Integration**: Google Generative AI (Gemini 1.5/2.5 Flash)
- **APIs**: OpenStreetMap Overpass API (for geolocation services)

### Database
- **Storage**: In-memory storage (MemStorage) for demonstration, ready for PostgreSQL integration via Drizzle.

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/S-Suraim/hack2care.git
   cd hack2care
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add your API keys:
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   PORT=5000
   ```

4. **Run the application**:
   ```bash
   npm run dev
   ```

5. **Access the app**:
   Open [http://localhost:5000](http://localhost:5000) in your browser.

## 📂 Project Structure

- `client/`: React frontend application.
- `server/`: Express backend and AI integration logic.
- `shared/`: Shared TypeScript schemas and types (Zod/Drizzle).
- `attached_assets/`: Static assets and design guidelines.

## 🛡️ License

This project is licensed under the MIT License - see the [package.json](package.json) file for details.

---
Developed with ❤️ for Hack2Care.
