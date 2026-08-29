# Delhi Tourism & Hotel Visitor Analysis

A comprehensive web application that blends Delhi's rich cultural heritage with data-driven insights into its hotel industry. This project provides tourists with historical context and attraction guides while offering stakeholders valuable analysis of visitor management patterns.

## 🌟 Features

### 🏛️ Cultural & Historical Exploration
- **Delhi History:** A deep dive into the evolution of Delhi from ancient times through the Mughal era to the modern capital.
- **Places to Visit:** Curated guides to Delhi's must-see attractions, categorized by historical significance and modern appeal.
- **Interactive UI:** Smooth transitions and animations powered by Framer Motion for an engaging user experience.

### 📊 Hotel Visitor Management Analysis
- **Data Visualizations:** Interactive charts showing monthly visitor trends, domestic vs. international visitor ratios, and seasonal patterns.
- **Key Insights:** Actionable conclusions drawn from data regarding peak seasons, average length of stay, and booking preferences.
- **Google Colab Integration:** Links to comprehensive data analysis notebooks for deeper methodological dives.
- **Hotel Recommendations:** Data-driven suggestions for accommodations based on visitor preferences and ratings.

## 🛠️ Tech Stack

- **Frontend:** [React 18](https://reactjs.org/) with [TypeScript](https://www.typescriptlang.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Charts:** [Chart.js](https://www.chartjs.org/) & [React-Chartjs-2](https://react-chartjs-2.js.org/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **Routing:** [React Router DOM v6](https://reactrouter.com/)

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd DAV-FINAL-PROJECT-main
   ```

2. Navigate to the project directory:
   ```bash
   cd project
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:5173` (or the port specified in your terminal).

### Building for Production

To create an optimized production build:
```bash
npm run build
```

## 📁 Project Structure

```text
project/
├── src/
│   ├── components/       # Reusable UI components (Navbar, Charts, Hero, etc.)
│   ├── pages/            # Page-level components (Home, Analysis, History, etc.)
│   ├── App.tsx           # Main application routing and layout
│   ├── index.css         # Global styles and Tailwind imports
│   └── main.tsx          # Application entry point
├── public/               # Static assets
├── tailwind.config.js    # Tailwind CSS configuration
└── vite.config.ts        # Vite configuration
```

## 📈 Data Analysis

The core analysis for this project was performed using Python in a Google Colab environment. It examines:
- Seasonal occupancy rates.
- Demographic distribution of visitors.
- Impact of online booking platforms.
- Correlation between ratings and booking frequency.

You can view the full analysis notebook [here](https://colab.research.google.com/drive/175dE4uzsxtow-fsCUKMAk8aKmLddTC6d).

## 📄 License

This project is part of the DAV Final Project submission.
