
# Talent Forge

🚀 **Your AI-Powered Career Coach**

Talent Forge is an intelligent career assistant designed to help job seekers optimize their resumes, prepare for interviews, and stay updated with industry trends. Whether you're a fresher or an experienced professional, Talent Forge provides the tools you need to land your dream job.

## 🌟 Inspiration

Job hunting is tough. Many candidates struggle with creating ATS-friendly resumes, preparing for interviews, and understanding industry expectations. We wanted to create a solution that simplifies this process, making career growth more accessible and efficient for everyone.

## 🎯 What It Does

- **AI-Powered Resume Checker** – Get instant feedback and ATS compatibility analysis.
- **Mock Interview Preparation** – Practice with AI-driven interview questions.
- **Industry Insights & Trends** – Stay updated with relevant job market data.
- **Career Path Guidance** – Personalized recommendations based on your skills and goals.

## 🛠️ Built With

- **Frontend:** Next.js, ShadCN UI, Tailwind CSS
- **Backend:** Node.js, Prisma
- **Database:** Neon DB
- **AI Integration:** Gemini AI
- **Event Handling:** Inngest
- **Deployment:** Vercel

## 🚧 Challenges We Faced

- Fine-tuning AI to provide meaningful resume feedback.
- Optimizing database queries for real-time career recommendations.
- Ensuring a seamless and responsive UI/UX.

## 🎉 Accomplishments

- Successfully built a fully functional career assistant.
- Implemented AI-driven resume analysis and interview prep.
- Deployed a scalable and efficient system using modern technologies.

## 📚 What We Learned

- Advanced AI integration for real-world applications.
- Optimizing full-stack performance and database efficiency.
- Creating an intuitive and user-friendly job search platform.

## 🔮 What's Next

- **Real-time job recommendations** based on user preferences.
- **Enhanced AI coaching** for career growth strategies.
- **More integrations** with LinkedIn and job portals.

## 🚀 Getting Started

### Prerequisites
- Node.js & npm installed
- PostgreSQL database setup

### Installation
```bash
# Clone the repository
git clone https://github.com/your-repo/talent-forge.git

# Navigate to the project folder
cd talent-forge

# Install dependencies
npm install
```

### Environment Variables
Create a `.env` file and add your credentials:
```env

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=


NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
  
DATABASE_URL=


GEMINI_API_KEY=
```

### Running the Project
```bash
# Run migrations
npx prisma migrate dev --name init

# Start the development server
npm run dev
```

## 🌐 Live Demo
Check out the deployed version here: [Talent Forge](https://talent-forge-cux7.vercel.app/)

## 🤝 Contributing
Feel free to fork the repo, create issues, or submit PRs to improve Talent Forge.

## 📜 License
This project is open-source and available under the MIT License.

---

💡 **Talent Forge – Empowering Careers with AI!**
