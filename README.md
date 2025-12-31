# Blood & Organ Donation Management System

A comprehensive web-based platform designed to streamline and manage blood and organ donation processes, connecting donors with patients in need through an efficient digital interface.

## 🌐 Live Demo

**[https://organblood.pythonanywhere.com/](https://organblood.pythonanywhere.com/)**

## 📋 Overview

The Blood & Organ Donation Management System is a full-stack web application that facilitates the coordination between blood/organ donors, patients requiring donations, and administrative staff. The platform aims to bridge the critical gap between those in need and willing donors, potentially saving lives through efficient resource management.

## ✨ Features

### For Patients
- **Patient Registration & Login**: Secure authentication system for patients
- **Request Blood/Organs**: Submit requests for specific blood types or organ donations
- **Track Request Status**: Monitor the progress of donation requests
- **Medical Profile Management**: Maintain detailed medical information and history

### For Donors
- **Donor Registration & Login**: Easy onboarding process for potential donors
- **Profile Management**: Update personal information, blood type, and donation history
- **Donation Scheduling**: View and schedule donation appointments
- **Eligibility Verification**: Check donation eligibility based on medical criteria

### For Administrators
- **Admin Dashboard**: Centralized control panel for system management
- **User Management**: Oversee patient and donor accounts
- **Request Processing**: Review and approve donation requests
- **Inventory Tracking**: Monitor blood and organ availability
- **Report Generation**: Generate analytical reports on donation activities

## 🚀 Technology Stack

- **Backend**: Python (Flask/Django)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite/PostgreSQL
- **Hosting**: PythonAnywhere
- **Authentication**: Session-based authentication with secure password hashing

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment (recommended)

### Local Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/blood-organ-donation-system.git
   cd blood-organ-donation-system
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

5. **Initialize the database**
   ```bash
   python manage.py migrate
   # or
   flask db upgrade
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   # or
   flask run
   ```

7. **Access the application**
   ```
   Open your browser and navigate to: http://localhost:5000
   ```

## 📁 Project Structure

```
blood-organ-donation-system/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── patient/
│   ├── donor/
│   ├── admin/
│   └── base.html
├── models/
│   ├── patient.py
│   ├── donor.py
│   └── admin.py
├── routes/
│   ├── patient_routes.py
│   ├── donor_routes.py
│   └── admin_routes.py
├── utils/
│   └── validators.py
├── config.py
├── app.py
├── requirements.txt
└── README.md
```

## 🔐 Security Features

- Secure password hashing using bcrypt/PBKDF2
- Session-based authentication
- CSRF protection
- SQL injection prevention through ORM
- Input validation and sanitization
- Role-based access control (RBAC)

## 🎯 Use Cases

1. **Emergency Blood Requirement**: Patients can quickly find compatible blood donors
2. **Organ Transplant Coordination**: Streamline organ matching and allocation
3. **Donation Camps**: Organize and manage blood donation drives
4. **Donor Network**: Build a community of regular donors
5. **Medical Records**: Centralized access to donation history

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines
- Follow PEP 8 style guide for Python code
- Write descriptive commit messages
- Add tests for new features
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Your Name** - *Initial work* - [YourGitHub](https://github.com/yourusername)

## 🙏 Acknowledgments

- Medical professionals who provided domain expertise
- Open-source community for various libraries and tools
- PythonAnywhere for hosting services

## 📧 Contact

For questions, suggestions, or support:
- **Email**: your.email@example.com
- **Project Link**: [https://github.com/yourusername/blood-organ-donation-system](https://github.com/yourusername/blood-organ-donation-system)
- **Live Demo**: [https://organblood.pythonanywhere.com/](https://organblood.pythonanywhere.com/)

## 🗺️ Roadmap

- [ ] SMS/Email notifications for donation requests
- [ ] Mobile application (iOS/Android)
- [ ] Integration with hospital management systems
- [ ] AI-based donor-patient matching
- [ ] Multi-language support
- [ ] Real-time inventory tracking
- [ ] Geolocation-based donor search
- [ ] Donation reminder system

## 📊 Project Status

🟢 **Active Development** - This project is actively maintained and accepting contributions.

---

**⭐ If you find this project useful, please consider giving it a star on GitHub!**
