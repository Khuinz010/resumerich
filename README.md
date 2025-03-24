<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rich Al Mae C. Manzano - Web Developer Resume</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="resume-container">
        <header>
            <div class="profile">
                <img src="muah.jpg" alt="Resume" class="profile-image">
                <div class="name-details">
                    <h1>Resume</h1>
                    <p class="personal-details">Name: Rich Al Mae C. Manzano</p>
                    <p class="personal-details">Birthday: March 8, 2005</p>
                    <p class="personal-details">Age: 25 years old</p>
                    <p class="personal-details">Contact: 09369392861</p>
                    <p class="personal-detail">Email: manzano@gmail.com</p>
                    <p class="address">Address: Iligan City</p>
                </div>
            </div>
        </header>

        <section class="about">
            <h2>About Me</h2>
            <p>I am a results-driven Web Developer with a strong background in HTML, CSS, JavaScript, and modern frameworks such as React. With a focus on delivering high-quality, responsive, and user-centric web solutions, I am committed to continuously enhancing performance, functionality, and user experience to meet the needs of both clients and end-users.</p>
        </section>

        <section class="education">
            <h2>Educational Background</h2>
            <ul>
                <li><strong>Elementary education</strong> Tambo Central School - Iligan City (2010 - 2016)</li>
                <li><strong>Secondary education</strong> St. Michael's College Basic education Department - Iligan City (2016 - 2022)</li>
                <li><strong>College </strong> Bachellor of Science in Computer Science</strong> - Mindanao State University- Maigo School of Arts and Trades (2022-2027)</li>
    
            </ul>
        </section>

        <section class="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML/CSS</li>
                <li>Responsive Design</li>
                <li>Database and Cache</li>
                <li>Testing and Debugging</li>
            </ul>
        </section>

        <section class="experience">
            <h2>Professional Experience</h2>
            <h3>Junior Web Developer</h3>
            <p><strong>Tech Solutions, Cagayan de Oro City</strong> (2029 - Present)</p>
            <ul>
                <li>Developed and maintained responsive websites using HTML, CSS, JavaScript, and React.</li>
                <li>Collaborated with cross-functional teams to implement user-friendly designs.</li>
            </ul>

            <h3>Frontend Developer Intern</h3>
            <p><strong>Web Innovations, Iligan City</strong> (2027 - 2028)</p>
            <ul>
                <li>Assisted in creating and optimizing web pages with HTML5, CSS, and JavaScript.</li>
                <li>Worked with the development team to enhance website performance and user interface.</li>
            </ul>
        </section>

        <section class="languages">
            <h2>Languages</h2>
            <ul>
                <li>Tagalog</li>
                <li>English</li>
                <li>Bisaya</li>
            </ul>
        </section>
    </div>
</body>
</html>
<style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'georgia', sans-serif;
    background-color: #f5f5f5;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.resume-container {
    width: 500px;
    background-color: #fff;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

header {
    display: flex;
    align-items: center;
    margin-bottom: 30px;
}

.profile {
    display: flex;
    align-items: center;
}

.profile-image {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-right: 15px;
    border: 3px solid #edeef3;
}

.name-details h1 {
    font-size: 1.5rem;
    color: hsl(0, 0%, 0%);
}

.name-details p {
    font-size: 0.9rem;
    color: #010003;
}

section h2 {
    font-size: 1.2rem;
    color: #971e32;
    margin-top: 20px;
    margin-bottom: 10px;
    text-transform: uppercase;
    border-bottom: 2px solid #007bff;
    padding-bottom: 5px;
}

section ul {
    list-style: none;
    padding-left: 20px;
}

section ul li {
    font-size: 0.9rem;
    margin-bottom: 8px;
    color: #555;
}

section p {
    font-size: 0.9rem;
    color: #555;
    margin-bottom: 10px;
}

@media (max-width: 500px) {
    .resume-container {
        width: 90%;
        padding: 15px;
    }

    .profile-image {
        width: 100px;
        height: 80px;
    }

    .name-details h1 {
        font-size: 1.3rem;
    }
}

</style>
