[index.html.html](https://github.com/user-attachments/files/22587359/index.html.html)
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Loan Prequalifier Texas</title>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.jsx"></script>
  </body>
</html>
[package.json](https://github.com/user-attachments/files/22587360/package.json)
{
  "name": "loan-prequalifier-texas",
  "version": "1.0.0",
  "private": true,
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "@vitejs/plugin-react": "^4.0.0",
    "autoprefixer": "^10.4.0",
    "postcss": "^8.4.0",
    "tailwindcss": "^3.3.0",
    "vite": "^4.5.0"
  }
}
[postcss.config.js](https://github.com/user-attachments/files/22587362/postcss.config.js)
export default {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
}
[tailwind.config.js](https://github.com/user-attachments/files/22587363/tailwind.config.js)
export default {
  content: ["./index.html", "./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
[vite.config.js](https://github.com/user-attachments/files/22587364/vite.config.js)
export default function App() {
  return (
    <div className="min-h-screen flex items-center justify-center bg-gray-100">
      <div className="bg-white p-8 rounded shadow-md w-96">
        <h1 className="text-2xl font-bold mb-4">Loan Prequalifier - Texas</h1>
        <form className="space-y-4">
          <input type="text" placeholder="Full Name" className="w-full p-2 border rounded" />
          <input type="number" placeholder="Requested Amount" className="w-full p-2 border rounded" />
          <input type="number" placeholder="Monthly Income" className="w-full p-2 border rounded" />
          <button type="submit" className="w-full bg-blue-600 text-white p-2 rounded">Check Eligibility</button>
        </form>
      </div>
    </div>
  )
}
[index.css.css](https://github.com/user-attachments/files/22587366/index.css.css)
