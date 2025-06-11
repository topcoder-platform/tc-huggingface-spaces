---
title: Topcoder Hugging Face Space Template with Docker + Next.js
emoji: 🗄️
colorFrom: blue
colorTo: purple
sdk: docker
pinned: false
app_port: 3000
---

# Topcoder Hugging Face Space Template with Docker + Next.js

This project, bootstrapped using [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app), demonstrates how to use `@huggingface/transformers` in [Next.js](https://nextjs.org) in the Topcoder Huggig Face organization.

Original repo source: https://github.com/huggingface/transformers.js-examples/tree/main/next-server

## Instructions

1. Clone the repository:

   ```sh
   git clone https://github.com/topcoder-platform/tc-huggingface-spaces.git
   ```

2. Change directory to the `spaces/space-demo-template` project:

   ```sh
   cd tc-huggingface-spaces/spaces/space-demo-template
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

4. Run the development server:

   ```sh
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
6. You can start editing the page by modifying `app/page.js` (Next.js) and `app/api/classify/route.js` (Transformers.js). The page auto-updates as you edit the file.
7. Enjoy developing at Topcoder with Hugging Face.
