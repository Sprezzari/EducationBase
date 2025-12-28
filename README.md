# 🎓 **EducationBase** - Educational Training Management System

A robust and scalable system for managing a vast database of educational trainings, courses, and professional training programs. Connects traditional academic structures with continuous learning opportunities.

---

## ✨ **Features**

- 📚 **Comprehensive Database**: 600+ bachelor's, technical, and technologist courses
- 🔧 **Modular Architecture**: Clear separation of responsibilities
- 🛡️ **Security**: Centralized YAML configuration
- ⚡ **Scalability**: Ready for database growth
- 📊 **Structured Data**: JSON for easy maintenance and import

---

## 🏗️ **Project Architecture**

```
EducationBase/
├── config.yml                 # Database configuration
├── config_loader.py          # YAML configuration loader
├── database_manager.py       # MySQL connection and schema manager
├── data_inserter.py         # JSON data inserter
├── data_constants.json      # JSON database (600+ records)
├── main.py                  # Main orchestration script
├── requirements.txt         # Python dependencies
└── README.md               # This file
```

---

## 🚀 **Quick Start**

### **Prerequisites**

- Python 3.8+
- MySQL Server 8.0+
- pip (Python package manager)

### **Installation**

1. **Clone the repository**
```bash
git clone https://github.com/your-user/EducationBase.git
cd EducationBase
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Configure the database**
Edit `config.yml` with your MySQL credentials:
```yaml
database:
  host: localhost
  port: 3306
  user: root
  password: your_password
  database: peoplecore
```

4. **Run the system**
```bash
python main.py
```

---
