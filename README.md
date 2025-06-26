# 🧠 Request Header Parser Microservice

> A simple Node.js and Express project that parses HTTP request headers and returns essential user information.

---

## 🎯 Objective

Build an API endpoint `/api/whoami` that returns a JSON object with the following properties:

* `ipaddress`: the client's IP address
* `language`: the preferred languages from the request headers
* `software`: the client software information (OS + browser) from the `User-Agent`

---

## 🛠 Tech Stack

* 🧩 **Node.js** + **Express**
* 🌐 CORS for remote testing (enabled)
* 📂 HTML + TailwindCSS frontend (for styling)

---

## 🚀 Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-user/FCC-RequestHeaderParserMicroservice
   cd FCC-RequestHeaderParserMicroservice
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   npm start
   # or with nodemon
   npm run dev
   ```

4. Visit:

   ```bash
   http://localhost:3000/api/whoami
   ```

   You'll receive a response like:

   ```json
   {
     "ipaddress": "::1",
     "language": "fr-FR,fr;q=0.9,en-US;q=0.8,en;q=0.7",
     "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64)..."
   }
   ```

---

## 📁 Project Structure

```
.
├── public/
│   └── style.css           # Tailwind styles
├── views/
│   └── index.html          # Frontend page
├── index.js                # Main server file
├── package.json            # Node config
└── README.md               # This file
```

---

## 📜 License

Open source under the MIT License.

---

Made with 💻 by Charles LINDECKER
[🔗 LinkedIn](https://www.linkedin.com/in/charles-lindecker)
