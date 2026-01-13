## 🚀 Live Deployment

**Live Application:** [https://ostad-batch-09-9d49.onrender.com/]

**Deployment Platform:** Render

**Deployment Date:** January 13, 2026

### Deployment Configuration

- **Platform:** Render (Serverless Functions)
- **Runtime:** Python 3.9
- **Framework:** Django 4.2
- **Static Files:** WhiteNoise
- **Database:** SQLite (ephemeral - stored in /tmp)

### Project Settings

**Framework Preset:** Other  
**Output Directory:** `staticfiles_build`

- Subsequent requests are faster

### Local Development

To run this project locally:
```bash
# Clone repository
git clone https://github.com/Imran4191/Ostad_batch-09.git
cd Ostad_batch-09

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver
```

Visit: `http://127.0.0.1:8000/`