# Abord Security Services Limited

## Run locally in VS Code

```bash
npm install
npm run dev
```

## Build for production

```bash
npm run build
```

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial Abord Security website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/abord-security-react.git
git push -u origin main
```

For VPS deployment, upload the contents of `dist` to your Nginx web root and use `try_files $uri $uri/ /index.html;` for React routes.

The contact form is visual only until connected to EmailJS, Formspree, Laravel API, or another backend.
