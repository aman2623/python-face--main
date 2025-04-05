# Face Recognition Based Attendance System  

## Overview  
This project is a **Python-based GUI-integrated attendance system** that uses **face recognition** to mark attendance. The system captures and recognizes faces using **OpenCV** and stores attendance records in **CSV files**. It also includes a **Graphical User Interface (GUI)** built with **Tkinter**, making it user-friendly for schools, colleges, and workplaces.  

## Features  
✅ **Face Recognition** – Uses OpenCV's LBPHFaceRecognizer for accurate face recognition.  
✅ **GUI-based Interface** – Built with Tkinter for ease of use.  
✅ **Automatic Attendance Recording** – Saves attendance details (ID, Name, Date, Time) in CSV files.  
✅ **Daily Attendance Logs** – Creates a new attendance file for each day.  
✅ **Password Protection** – Ensures security when registering new students.  
✅ **Live Attendance Display** – Shows attendance details in tabular format.  

## Technologies Used  
- **Python**  
- **Tkinter** – GUI framework  
- **OpenCV** – Face detection & recognition  
- **NumPy** – Array processing  
- **Pandas** – Data management  
- **CSV Handling** – Stores student details & attendance records  
- **Datetime & Time** – Timestamps for attendance tracking  

## Installation  
### Prerequisites  
Ensure you have **Python** installed on your system. Then, install the required libraries using the following commands:  
```bash
pip install tk-tools
pip install opencv-contrib-python
pip install datetime
pip install pytest-shutil
pip install python-csv
pip install numpy
pip install pillow 
pip install pandas
pip install times

Usage
Run the Application
python main.py
Register Students
Enter the student’s ID and Name.
The system captures multiple face images for recognition.
Mark Attendance
The system detects and recognizes faces in real-time.
Attendance is automatically logged with a timestamp.
View Attendance Records
Attendance details are saved in daily CSV files for easy tracking.

File Structure
📂 Face Recognition Attendance System  
 ├── 📂 StudentDetails/           # Stores student information (CSV)  
 ├── 📂 TrainingImage/            # Captured face images  
 ├── 📂 Attendance/               # Daily attendance records  
 ├── haarcascade_frontalface_default.xml  # Pre-trained face detection model  
 ├── main.py                      # Main script  
 ├── install These libary.txt      # Required dependencies  
 ├── README.md                     # Documentation  
 └── .gitattributes                 # Git settings  

Future Enhancements
🔹 Integration with a database (MySQL, Firebase) for better data management.
🔹 Mobile app integration for remote attendance marking.
🔹 Improved recognition accuracy with deep learning models.

Contact
📧 Email: amandwivedi301@gmail.com

This is now **clean, structured, and easy to copy**. Let me know if you need any changes! 🚀
