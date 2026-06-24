# 📦 Ongkir Berapa (Shipping Cost Estimator)

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Project-blue?style=for-the-badge)](https://ongkir-berapa.vercel.app/)

**Ongkir Berapa** is a fast, utility-focused web application designed to check real-time shipping costs and logistics rates across Indonesia. Built with modern web technologies, this project demonstrates the ability to seamlessly integrate external APIs, manage complex asynchronous states, and deliver a frictionless user experience.

As a Frontend Developer, this repository highlights my proficiency in handling dynamic data fetching, creating intuitive search/autocomplete forms, and structuring a clean, minimalist UI that presents tabular data clearly.

## ✨ Core Features

*   **Real-time API Integration:** Fetches accurate, up-to-date shipping rates from external logistics APIs based on origin, destination, and package weight.
*   **Dynamic Search & Autocomplete:** Implemented optimized search inputs for easily finding and selecting provinces and cities.
*   **Robust State Management:** Handles API loading states, data validation, and error boundaries gracefully to ensure a smooth user journey.
*   **Clean & Responsive UI:** Designed with a "3D flat" aesthetic and minimalist approach, ensuring the interface remains uncluttered and highly readable across mobile and desktop devices.

## 🛠️ Tech Stack

*   **Frontend Framework:** [e.g., Svelte 5 / Next.js / React]
*   **Styling:** Tailwind CSS (Customized for a clean, modern, and accessible interface)
*   **Data Fetching & State:** [e.g., native fetch / Axios / TanStack Query]
*   **Deployment:** Vercel

## 🚀 Local Development

To run this project locally, you will need Node.js installed and a valid API key for the shipping provider (e.g., RajaOngkir).

1.  **Clone the repository:**
```bash
    git clone [https://github.com/Haresz/ongkir-berapa.git](https://github.com/Haresz/ongkir-berapa.git)
    cd ongkir-berapa
```

2.  **Install dependencies:**
```bash
    npm install
    # or yarn / pnpm install
```

3.  **Environment Variables:**
    Create a `.env` or `.env.local` file in the root directory and add your API key. *(Important: Never commit your actual `.env` file to GitHub)*.
```env
    VITE_SHIPPING_API_KEY=your_api_key_here
    VITE_API_BASE_URL=[https://api.example.com/v1](https://api.example.com/v1)
```

4.  **Run the development server:**
```bash
    npm run dev
    # or yarn dev / pnpm dev
```

5.  Open your browser and navigate to the local server URL (usually `http://localhost:5173` or `http://localhost:3000`).

---

**Muhammad Haris Al Fikri** | Web Programmer & Frontend Developer
