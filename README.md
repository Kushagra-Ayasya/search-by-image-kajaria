## 📂 Project Structure

```
/frontend   → React-based UI for image and text search  
/backend    → Python Flask backend for processing image/text and returning results
```

---

## 🚀 Frontend – React

### 📌 Requirements
- Node.js
- npm

### ▶️ Setup & Run
```bash
# Navigate to the frontend folder
cd frontend

# Install dependencies
npm install

# Run the development server
npm run dev
```

---

## 🧠 Backend – Python (Flask)

### 📌 Requirements
- Python 3.8+
- pip

### ▶️ Setup & Run
```bash
# Navigate to the backend folder
cd backend

# Install dependencies
pip install -r requirements.txt
pip install flask-cors
pip install open-clip-torch

# Run the Flask server
python app.py
```

### 🔌 Available API Endpoints

| Method | Endpoint    | Description                         |
|--------|-------------|-------------------------------------|
| POST   | `/upload`   | Upload image and get product matches |
| POST   | `/search`   | Search for products by description  |

---

## 🛠️ Technologies Used

**Frontend:**
- React
- Tailwind CSS
- React Router DOM

**Backend:**
- Flask
- Flask-CORS
- OpenCLIP (open-clip-torch)
- PyTorch
- PIL
- FAISS ( Facebook AI Similarity Search )

---


---

## 📃 License

This project is licensed under the MIT License.
