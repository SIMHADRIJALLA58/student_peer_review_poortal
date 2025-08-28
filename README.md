student_peer_review_poortal:
The Student Peer Review Portal is a web-based application designed to help students and instructors improve the learning process through peer evaluation. The portal allows students to submit assignments or projects and receive constructive feedback from their classmates. This promotes collaboration, critical thinking, and self-improvement.

Features:
Students can submit assignments or projects online.
Peers can review, rate, and provide feedback on submissions.
Ensures fairness and anonymity in peer evaluations.
Instructors can monitor submissions and reviews to maintain quality.
Helps students develop reviewing, analytical, and communication skills.

Technology Stack:
Backend: Flask (Python)
Frontend: HTML, CSS, JavaScript
Database: MongoDB Atlas (or local database)

1.Clone the repository

git clone https://github.com/your-username/student-peer-review-portal.git
cd student-peer-review-portal

2.Create and activate virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3.Install dependencies

pip install -r requirements.txt

4.Configure MongoDB Atlas

Create a free cluster in MongoDB Atlas
Copy your connection string
Replace <your_connection_string> in app.py

5.Run the application

python app.py
