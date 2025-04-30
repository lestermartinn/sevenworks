# SevenWorks

SevenWorks is a modern, real-time resume builder built with Next.js, Firebase, and @react-pdf/renderer. Instantly create, edit, autosave, and download professional resumes with a live PDF preview.

## Features
- Live editing of personal, experience, and education information
- Real-time PDF preview and instant updates as you type
- Autosave and autoload of form data to Firestore (per user session)
- Download your resume as a PDF
- User authentication (Firebase Auth)
- Responsive, modern UI

## Video Demo
https://www.youtube.com/watch?v=ybUhvRTBgKY

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm, yarn, or pnpm
- Firebase project (Firestore & Auth enabled)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/alexlautin/sevenworks.git
   cd sevenworks
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Configure Firebase:**
   - Add your Firebase config to `src/app/lib/firebase.ts`.
   - Enable Firestore and Authentication in your Firebase project.

4. **Run the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

5. **Open the app:**
   Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure
- `src/app/editor/components/` — Main editor, PDF template, and UI components
- `src/app/editor/formcontext.tsx` — Form data context and Firestore integration
- `src/app/editor/components/business_template.tsx` — PDF template logic
- `src/app/editor/components/DownloadButton.tsx` — PDF download logic
- `src/app/lib/` — Firebase client setup

## Deployment
Deploy easily on [Vercel](https://vercel.com/) or your preferred platform. See [Next.js deployment docs](https://nextjs.org/docs/app/building-your-application/deploying).

## License
MIT

---

Made by Alex Lautin, Andy Blumberg, Parker Wischover, Lester Martin, Chris Kim, Tomas Lee, and Andrea Valentino
