# Setup

```
mamba create -p venv python=3.11 pip -y
mamba activate venv
pip install -r requirements-dev.txt
pip install -r requirements.txt
```

# ExpenseTracker

Empower users to achieve financial clarity through intelligent expense tracking and insightful financial analytics

```
ExpenseTracker/
├── app/
│ ├── main.py # FastAPI app initialization
│ ├── core/ # Core configurations
│ │ ├── config.py # Settings management
│ │ ├── database.py # Database setup
│ │ └── security.py # JWT & password utilities
│ ├── models/user.py # SQLAlchemy models
│ ├── schemas/user.py # Pydantic schemas
│ ├── crud/user.py # Database operations
│ └── api/
│ ├── deps.py # Dependencies
│ └── endpoints/ # API routes
├── alembic/ # Database migrations
├── requirements.txt # Dependencies
├── .env # Environment variables
└── run.py # Application runner
```
