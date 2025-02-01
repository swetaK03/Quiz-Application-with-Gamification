# Knowledge Quest - Interactive Quiz Application

A modern, gamified quiz application built with React, TypeScript, and Tailwind CSS. Test your knowledge while enjoying engaging gameplay elements like streaks, points, and detailed performance statistics.

![Knowledge Quest Screenshot](https://images.unsplash.com/photo-1516321497487-e288fb19713f?auto=format&fit=crop&q=80&w=2070)

## 🚀 Features

- **Interactive Quiz Interface**
  - Multiple-choice questions with dynamic scoring
  - Real-time progress tracking
  - Streak counter for consecutive correct answers
  - Time tracking per question
  - Beautiful, responsive design

- **Gamification Elements**
  - Points system based on question difficulty
  - Streak multiplier for consecutive correct answers
  - Performance statistics and analytics
  - Interactive answer selection with visual feedback

- **Performance Analytics**
  - Detailed end-of-quiz statistics
  - Accuracy percentage
  - Average response time
  - Highest streak achieved
  - Total score calculation

## 🛠️ Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Lucide React (for icons)
- Vite (for build tooling)

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v18 or higher)
- npm (v8 or higher)

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/knowledge-quest.git
   cd knowledge-quest
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and visit:
   ```
   http://localhost:5173
   ```

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── QuizCard.tsx    # Question display component
│   └── QuizResults.tsx # Results summary component
├── hooks/
│   └── useQuiz.ts      # Quiz logic and state management
├── types/
│   └── quiz.ts         # TypeScript interfaces
├── App.tsx             # Main application component
└── main.tsx           # Application entry point
```

## 🎮 Usage

1. Start the quiz by visiting the application URL
2. Answer multiple-choice questions by clicking on options
3. Track your progress through the progress bar
4. Build streaks by answering correctly consecutively
5. View detailed statistics after completing the quiz
6. Restart the quiz to try improving your score

## 🔄 API Integration

The application fetches quiz data from:
```
https://api.jsonserve.com/Uw5CrX
```

Expected API response format:
```typescript
interface Question {
  id: number;
  question: string;
  options: string[];
  correctAnswer: number;
  points: number;
}
```

## 🛠️ Development

- Run development server:
  ```bash
  npm run dev
  ```

- Build for production:
  ```bash
  npm run build
  ```

- Preview production build:
  ```bash
  npm run preview
  ```

## 🧪 Testing

The application includes comprehensive testing:

```bash
npm run test
```

## 📦 Building for Production

1. Create a production build:
   ```bash
   npm run build
   ```

2. The build output will be in the `dist` directory

## 👥 Authors

- Your Name - Initial work -(https://github.com/swetaK03)

## 🙏 Acknowledgments

- React Team for the amazing framework
- Tailwind CSS for the utility-first CSS framework
- Lucide for beautiful icons
