# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            background-color: #f0f8f8;
            margin: 0;
            padding: 20px;
            align-items: center;
        }
        .resume-container {
            max-width: 700px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
           text-align: center;
        }
        .header {
            display: flex;
          align- items: center;
            background: #a8d5d5;
            padding: 20px;
            border-radius: 10px;
        }
       
        #profile-pic {
             width: 200px;
            height: 150px;
            border-radius: 50%;
            margin-right: 10px;  
        }
        ul {
            padding-left: 20px;
        }
        .header h1 {
           
            text-align:center;
        }
        .section {
            margin-bottom: 20px;
            text-align: left;
        }
        .section h2 {
            border-bottom: 2px solid #a8d5d5;
            padding-bottom: 5px;
        }
        .contact,.education, .skills, .languages, .certifications {
            background: #e0f2f1;
            padding: 10px;
            border-radius: 5px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
    <div class="header">
        <input type="file" id="imageUpload" accept="image/*">
        <img id="profile-pic" src="" alt="Profile Picture" style="display:none;">
 
        <div>
                <h1>SAKTHI SREE</h1>
                <p>🎓 BACHELOR OF SCIENCE IN COMPUTER SCIENCE </p>
        </div>
       </div>
     

        <div class="section contact">
            <h2>Contact Information</h2>
            <p>📞 +91 9940986081</p>
            <p>📍 1/161 Rangampalayam, Coimbatore 638009</p>
            <p>✉️ sakthisree1712@gmail.com</p>
        </div>
        <div class="section">
            <h2>Personal Profile</h2>
            <p>I'm an experienced, hardworking and responsible individual with a keen eye for detail. I work well both individually and as a team, and can be relied upon to be punctual, cheerful and driven. I'm always looking for ways to improve myself and to support those around me, and work consistently well under pressure.</p>
        </div>
       
        <div class="section education">
            <h2>Education</h2>
            <h3>🏫Bachelor of Science in Computer Science - Bharathiyar University</h3>
            <p>2023 - 2026, Coimbatore</p>
            <h3>🏫High School - Government Higher Secondary School</h3>
            <p>2021 - 2023, Pethikuttai, Coimbatore</p>
            <h3>🏫Matric School - Government Higher Secondary School</h3>
            <p>2019 - 2021, Chinniyampalayam, Coimbatore</p>
        </div>
    </div>

<div class="section professionalskills">
            <h2>Professional Skills</h2>
            <ul>
                <li>Strong team player with excellent communication skills</li>
                <li>Able to meet deadlines</li>
                <li>Profound ability to follow and understand trends</li>
                <li>Participated in code reviews.</li>
              </ul>
        </div>

        <div class="section skills">
            <h2>Skills</h2>
            <ul>
                <li>Java</li>
                <li>Database</li>
                <li>JavaScript</li>
                <li>HTML & CSS</li>
                <li>C Programming</li>
                <li>Strong Communication</li>
            </ul>
        </div>
       
        <div class="section hobbies">
            <h2>Hobbies</h2>
            <ul>
                <li>Painting</li>
                <li>Photography</li>
                <li>Reading</li>
                <li>Sports</li>
            </ul>
        </div>    
         
        <div class="section languages">
            <h2>Languages</h2>
            <ul>
                <li>Tamil</li>
                <li>English</li>
                <li>Kannada (Speaking Only)</li>
            </ul>
        </div>

        <div class="section experience">
            <h2>Certifications</h2>
            <ul>
                <li>TNSDC-FEWD & Cloud</li>
            </ul>
        </div>
 
       
    <script>
        document.getElementById('imageUpload').addEventListener('change', function(event) {
            const file = event.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    const img = document.getElementById('profile-pic');
                    img.src = e.target.result;
                    img.style.display = 'block';
                }
                reader.readAsDataURL(file);
            }
        });
    </script>
</body>
</html>
