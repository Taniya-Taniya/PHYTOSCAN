🌿 Phytoscan – AI-Powered Leaf Identifier

Phytoscan is a real-time web application that allows users to identify plant leaves by simply uploading an image. It uses the powerful **Plant.id API** to recognize the plant and fetch detailed information such as common names, descriptions, and medicinal or practical uses.

Built using **Python**, **Streamlit**, and the **Plant.id API**, Phytoscan is designed to make plant knowledge easily accessible for students, gardeners, and nature lovers.

---

## 🚀 Features

- 📤 Upload any leaf image (JPG, PNG)
- 🌱 Real-time identification using Plant.id API
- 🧾 Displays plant name, description, common names, and uses
- ⚠️ Includes fallback demo mode if API fails or internet is not available
- 🌐 Streamlit UI – fast, simple, and lightweight

---

## 🛠️ Tech Stack

- **Frontend & Backend:** Streamlit (Python)
- **Image Processing:** PIL (Python Imaging Library)
- **API Integration:** Plant.id (https://plant.id/)
- **Deployment:** Streamlit Cloud / Localhost

---

## 🔍 How to Run Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Taniya-Taniya/PHYTOSCAN.git
   cd PHYTOSCAN
Install dependencies:
pip install -r requirements.txt

Run the app:
streamlit run app.py
