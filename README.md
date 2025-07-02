<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .profile-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 800px;
            margin: auto;
        }
        .profile-header {
            text-align: center;
            margin-bottom: 20px;
        }
        .profile-header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #ddd;
        }
        .profile-header h1 {
            margin-top: 10px;
            color: #0056b3;
        }
        .profile-section {
            margin-bottom: 20px;
            border-bottom: 1px solid #eee;
            padding-bottom: 15px;
        }
        .profile-section:last-child {
            border-bottom: none;
            padding-bottom: 0;
        }
        .profile-section h2 {
            color: #0056b3;
            border-bottom: 2px solid #eee;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }
        .profile-info {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 10px;
            margin-bottom: 10px;
        }
        .profile-info strong {
            color: #555;
        }
        .skills-list, .courses-list {
            list-style-type: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }
        .skills-list li, .courses-list li {
            background-color: #e2f0ff;
            padding: 5px 10px;
            border-radius: 4px;
            color: #0056b3;
        }
        .grades-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        .grades-table th, .grades-table td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        .grades-table th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <div class="profile-container">
        <div class="profile-header">
            <img src="https://via.placeholder.com/150" alt="Student Photo">
            <h1>John Doe</h1>
            <p>Student ID: S123456789</p>
            <p>Major: Computer Science</p>
        </div>

        <div class="profile-section">
            <h2>Personal Information</h2>
            <div class="profile-info">
                <strong>Date of Birth:</strong> <span>January 15, 2003</span>
            </div>
            <div class="profile-info">
                <strong>Email:</strong> <span>john.doe@example.com</span>
            </div>
            <div class="profile-info">
                <strong>Phone:</strong> <span>+1 (555) 123-4567</span>
            </div>
            <div class="profile-info">
                <strong>Address:</strong> <span>123 University Ave, City, State, 12345</span>
            </div>
        </div>

        <div class="profile-section">
            <h2>Academic Information</h2>
            <div class="profile-info">
                <strong>University:</strong> <span>University of XYZ</span>
            </div>
            <div class="profile-info">
                <strong>Program:</strong> <span>Bachelor of Science</span>
            </div>
            <div class="profile-info">
                <strong>Year:</strong> <span>3rd Year</span>
            </div>
            <div class="profile-info">
                <strong>GPA:</strong> <span>3.8 / 4.0</span>
            </div>
        </div>

        <div class="profile-section">
            <h2>Courses Enrolled</h2>
            <ul class="courses-list">
                <li>Data Structures and Algorithms</li>
                <li>Database Management Systems</li>
                <li>Operating Systems</li>
                <li>Web Development</li>
                <li>Artificial Intelligence</li>
            </ul>
        </div>

        <div class="profile-section">
            <h2>Grades</h2>
            <table class="grades-table">
                <thead>
                    <tr>
                        <th>Course Code</th>
                        <th>Course Name</th>
                        <th>Grade</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>CS101</td>
                        <td>Introduction to Programming</td>
                        <td>A</td>
                    </tr>
                    <tr>
                        <td>MA201</td>
                        <td>Calculus I</td>
                        <td>B+</td>
                    </tr>
                    <tr>
                        <td>PH101</td>
                        <td>Physics for Engineers</td>
                        <td>A-</td>
                    </tr>
                    <tr>
                        <td>CS205</td>
                        <td>Data Structures</td>
                        <td>A</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <div class="profile-section">
            <h2>Skills</h2>
            <ul class="skills-list">
                <li>Python</li>
                <li>Java</li>
                <li>JavaScript</li>
                <li>HTML</li>
                <li>CSS</li>
                <li>SQL</li>
                <li>Git</li>
                <li>Problem Solving</li>
            </ul>
        </div>

        <div class="profile-section">
            <h2>Projects / Experience</h2>
            <ul>
                <li><strong>E-commerce Website (Project):</strong> Developed a full-stack e-commerce platform using MERN stack.</li>
                <li><strong>Internship at Tech Innovators Inc. (Summer 2024):</strong> Worked on developing backend APIs for a new mobile application.</li>
            </ul>
        </div>

        <div class="profile-section">
            <h2>Contact Information</h2>
            <p>Feel free to reach out for collaborations or opportunities.</p>
        </div>
    </div>
</body>
</html>
