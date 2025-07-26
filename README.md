# 👚 DrobeMate – Your Smart Wardrobe Companion

DrobeMate is a modern wardrobe management system built with Django and PostgreSQL. 
It helps users organize their clothing, plan daily outfits, and get smart suggestions based on weather conditions.

## 🌟 Features
- ✅ Upload and manage clothing items with categories (e.g., tops, bottoms, footwear)
- 🗓️ Plan and save outfits for specific dates or events
- 🌤️ Weather-based outfit suggestions (Coming Soon!)
- 🧠 AI-based personalized outfit recommendations (Future enhancement)
- 🛍️ Shopping integration for missing wardrobe items (Future enhancement)


## ⚙️ Tech Stack
| Tech          | Description              |
|---------------|--------------------------|
| Python 3.9     | Backend Language          |
| Django         | Web Framework             |
| PostgreSQL     | Database                  |
| React.js       | Frontend (handled by teammate) |
| HTML/CSS       | For basic template testing (if needed) |


## 🚀 Getting Started
### 🔧 Prerequisites
- Python 3.9 installed
- PostgreSQL installed and configured (optional for later)
- `pip` package manager

---

### 📁 Project Setup (Development)

```bash
# 1. Clone the repository (once pushed)
git clone https://github.com/<your-username>/drobemate.git
cd drobemate

# 2. Create virtual environment
python3 -m venv drobemateenv

# 3. Activate the environment
source drobemateenv/bin/activate

# 4. Install Django
pip install django

# 5. Start the development server
python3 manage.py runserver
