# Snipora

Snipora is a full-stack collaborative code execution and snippet-sharing platform designed to empower developers of all skill levels. Inspired by modern IDEs like VS Code, it enables users to write, execute, and share code seamlessly across multiple programming languages. Whether you're testing ideas, learning new languages, or sharing solutions with the community, Snipora provides an intuitive and efficient environment.

---

## Purpose

Snipora bridges the gap between code execution and collaboration. It offers developers a platform to:

- Execute code snippets instantly without setting up local environments.
- Collaborate with other developers by sharing reusable snippets.
- Explore and learn from a growing repository of community-driven code.
- Track coding activity with aggregated insights and history.

---

## Functionality

### Core Features

1. **Integrated Code Execution**
   - Supports multiple languages, including JavaScript (free) and nine additional languages (premium).
   - Displays success or error messages.

2. **Snippet Sharing and Discovery**
   - Share code snippets with titles, summaries, and descriptions.
   - Search, filter, and star favorite snippets.
   - View snippets in list or grid view with smooth transitions.

3. **User Profiles and Insights**
   - Track total code executions, starred snippets, and favorite languages.
   - Access a detailed history of code executions with results.

4. **Community Interaction**
   - Add comments (regular text or code) to shared snippets.
   - Preview comments before posting.

5. **Secure Premium Access(Lemon Squeezy)**
   - Unlock advanced features and languages via a secure payment gateway.

6. **Modern UI**
   - Built with Next.js and Tailwind CSS for a visually appealing interface.

---

## Setup Instructions

### Prerequisites

Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/codree8/snipora.git
   cd snipora
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   - Create a `.env.local` file in the project root.
   - Add the following variables:
     ```env
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-clerk-publishable-key>
     CLERK_SECRET_KEY=<your-clerk-secret-key>
     CONVEX_DEPLOYMENT=<your-convex-deployment>
     NEXT_PUBLIC_CONVEX_URL=<your-convex-url>
     ```

4. **Start the Development Server**:
   ```bash
   npm run dev
   ```

   Access the application at `http://localhost:3000`.

### Deployment

Follow the deployment instructions for Next.js to deploy on platforms like Vercel, AWS, or Netlify.

---

## Standout Features

- **Multi-Language Code Execution**: Instant execution of code in 10 programming languages, with real-time feedback.
- **Snippet Sharing**: Share and explore reusable snippets with detailed metadata.
- **Profile Insights**: Monitor coding activity and identify growth areas.
- **Community Engagement**: Comment on snippets and interact with other developers.
- **Secure Payments**: Lifetime access to premium features via encrypted payment processing.

---

- **Website**: [Snipora](https://snipora.vercel.app/)


---

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
