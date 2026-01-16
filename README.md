# ResumeAI - AI-Powered Resume Analysis Tool

A modern web application that provides comprehensive resume analysis using artificial intelligence to help job seekers optimize their resumes for better ATS (Applicant Tracking System) compatibility and overall quality.

## Features

- **Resume Upload & Analysis**: Upload PDF/text resumes or paste resume content directly
- **ATS Score Calculation**: Get detailed scores for resume optimization
- **Skill Assessment**: Identify technical and soft skills from resume content
- **Improvement Suggestions**: Receive actionable feedback for resume enhancement
- **Contact Integration**: Built-in contact form for user inquiries

## Tech Stack

### Frontend
- **React 18** - Modern JavaScript library for building user interfaces
- **TypeScript** - Type-safe JavaScript for better development experience
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework

### Backend Services
- **EmailJS** - Client-side email sending for contact forms
- **Supabase** - Backend-as-a-Service for future database and API needs

## Team
This project was developed by:

- **[Aayan]** - Project Lead & Full-Stack Developer
- **[Gauri]** - Frontend Developer & UI/UX Designer
- **[Vaibhavi]** - Backend Developer & API Integration
- **[Faizan]** - Libraries and Database

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd resume-insight-ai-main
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:8080](http://localhost:8080) in your browser

### Building for Production

```bash
npm run build
npm run preview
```

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # shadcn/ui components
│   ├── Header.tsx      # Navigation header
│   ├── Footer.tsx      # Site footer
│   └── ...
├── pages/              # Page components
│   ├── Index.tsx       # Home page with resume analyzer
│   ├── About.tsx       # About page
│   └── Contact.tsx     # Contact form page
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
└── integrations/       # External service integrations
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please contact us through the contact form on our website or reach out to [aayanbshaikh1219@gmail.com].

---

**Built with ❤️ by [Group_7-CSSE-C]**
