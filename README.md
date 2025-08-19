Quizzerly
Get exam ready only with Quizzerly! Upload a PDF, extract content, and generate a clean multiple‑choice quiz with AI.

Getting Started
Sign Up/Log In: Use the auth pages to create an account and access the app.
Dashboard: View your activity and saved quizzes.
Quiz Generator: Upload a PDF and generate an interactive quiz, or extract text client‑side for large files.
Quizzerly makes it simple to turn study material into concise, answerable questions with clear feedback.

Features
Upload PDFs: Drag and drop or select a PDF to analyze.
Client‑side text extraction: For large PDFs, text is extracted in the browser with pdfjs-dist to avoid server limits.
AI quiz generation: Uses Gemini to create exactly N multiple‑choice questions.
Results view: Score, rank, and printable results page.
Supabase auth: Email/password authentication with protected routes.
Usage
Open Quizzerly in your browser.
Upload a PDF and choose the number of questions.
Generate the quiz and answer interactively.
View your results and print or try again.
Installation
Click Me
Deployment (Vercel)
Set these env vars in Vercel Project Settings:

NEXT_PUBLIC_SUPABASE_URL
NEXT_PUBLIC_SUPABASE_ANON_KEY
GEMINI_API_KEY
Auth/Protected routes and the dashboard are configured as dynamic to avoid prerender env lookups.

Tech Stack
Next.js App Router, React
Supabase (auth)
pdfjs‑dist, pdf‑parse (optional)
Gemini (text generation)
