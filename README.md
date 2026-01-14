# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

## Adding the attached hero image

Place the attached image file you provided in the project root `public` folder as `public/sula-hero.jpg`.
The homepage will display this image at the top of the page. If you prefer the image inside the build assets, copy it to `src/assets` and update imports accordingly.

## Low-Fidelity Wireframes

I added three low-fidelity SVG wireframes to `public/wireframes/` to help visualize layout and UX decisions:

- `public/wireframes/wireframe-home.svg` — top-fold homepage layout (header, hero, wines preview)
- `public/wireframes/wireframe-header.svg` — header variations (desktop and mobile)
- `public/wireframes/wireframe-hero.svg` — hero treatment options (cover vs contain, CTAs)

Open those SVG files in your browser or VS Code to view the simple mockups.

## Usability Notes (summary)

- Use images >= 1920px width for hero to avoid upscaling blur.
- Keep a dark gradient overlay on hero backgrounds for headline/CTA legibility.
- On small screens reduce hero height and simplify CTAs to avoid pushing content below the fold.
- Use square crops for logo/favicons (serve a `favicon.png` or `.ico` for best compatibility).
- Ensure nav contrast and keyboard accessibility; anchor links should smooth-scroll and have clear focus states.


**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/features/custom-domain#custom-domain)
