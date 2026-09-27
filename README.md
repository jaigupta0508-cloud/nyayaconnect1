# NyayaAI ⚖️

> **Bridging the Justice Gap in the New Era of Indian Law**

NyayaAI is a modern, highly polished LegalTech web application designed to help Indian citizens navigate the newly implemented criminal codes (BNS, BNSS, and BSA). It leverages AI to democratize legal knowledge and connects citizens directly with verified local advocates.

![NyayaAI Prototype Demo](./public/demo-placeholder.png)

## 🌟 Key Features

1. **Gemini AI Triage Engine**
   - Describe your legal issue in plain English.
   - Instantly maps your issue to the correct Bharatiya Nyaya Sanhita (BNS) or Bharatiya Nagarik Suraksha Sanhita (BNSS) codes.
   - Provides a clear, 3-step procedural roadmap.
2. **BSA Evidence Vault**
   - Section 61 Compliant Electronic Evidence Securing.
   - Uses the native browser Web Crypto API (`crypto.subtle`) to generate real, client-side SHA-256 cryptographic hashes of files to preserve metadata integrity.
3. **Local Legal Marketplace**
   - Custom CSS Interactive Radar Map.
   - Discover verified professionals specializing in your exact issue.
   - Transparent access to lawyer success rates, primary courts, and consultation fees.
4. **CPO Executive Dashboard (Protected)**
   - Visualizes monetization tiers (Freemium, Micro-fees, B2B SaaS).
   - Tracks regulatory compliance metrics (BCI, DPDP Act 2023, BSA Sec 61).

## 🚀 Tech Stack

- **Framework**: React (Vite)
- **Styling**: Tailwind CSS v4 (Premium dark mode, glassmorphism, glowing neon accents)
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **AI Integration**: Google Gemini API (`gemini-1.5-flash`)

## 🛠️ Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- A Google Gemini API Key (Get one free at [Google AI Studio](https://aistudio.google.com/app/apikey))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/nyaya-ai.git
   cd nyaya-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open in Browser**
   - Navigate to `http://localhost:5173`
   - Paste your Gemini API Key directly into the UI's "API Configuration" box on the AI Triage tab!

## 🔐 Security Note
For this prototype, the Gemini API key is securely saved in the user's browser `localStorage` to avoid hardcoding sensitive credentials into the frontend source code.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
