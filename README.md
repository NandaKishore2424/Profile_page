# Profile Page
## Date: 07-07-2025
## Objective:

To design a simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes.

## Tasks:

#### 1. Set Up the HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the basic structure.

Add an appropriate <title> such as "My Profile".

#### 2. Add Page Headings:

Insert a main heading using ```<h1>``` for the user's name.

Include subheadings such as ```<h2>``` or ```<h3>``` for titles or roles (e.g., "Student", "Web Developer").

#### 3. Insert a Profile Image:

Use the ```<img>``` tag to display the user’s profile picture.

Add alt text and set basic attributes like width and height.

#### 4. Include a Short Bio Section:

Add a paragraph using <p> to provide a short introduction or biography.

The content may include education, interests, or a personal statement.

#### 5. Organize Content Using HTML Elements:

Use ```<section>```, ```<div>```, or ```<article>``` for logical grouping.

Add a horizontal line (```<hr>```) to separate sections.

#### 6. Keep the Design HTML-Only:

Do not use CSS or JavaScript.

Focus on semantic HTML and readability.
## HTML Code:

```
<!DOCTYPE html>
<html>
<head>
    <title>My Profile</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="profile-container">
        <section class="header-section">
            <h1>Nanda Kishore R</h1>
            <h2>Student</h2>
            <h3>Full Stack Developer</h3>
        </section>
        
        <hr>
        
        <section class="image-section">
            <img src="nanda.jpg" alt="Profile picture of Nanda Kishore R" width="200" height="200">
        </section>
        
        <hr>
        
        <section class="about-section">
            <h2>About Me</h2>
            <p>Passionate and results-driven Software Developer with strong problem-solving skills and a solid foundation in Data Structures, Algorithms, OOP, and System Design. Skilled in building scalable, high-performance full-stack web applications using Java, Spring Boot, React, and MongoDB. Writes clean code in agile teams.</p>
        </section>
        
        <hr>
        
        <section class="skills-section">
            <h2>Technical Skills</h2>
            <p><strong>Programming Languages:</strong> Java, JavaScript, Python</p>
            <p><strong>Frameworks:</strong> Spring Boot, React, Node.js</p>
            <p><strong>Databases:</strong> MongoDB, MySQL</p>
            <p><strong>Tools:</strong> Git, VS Code, IntelliJ IDEA</p>
        </section>
        
        <hr>
        
        <section class="education-section">
            <h2>Education</h2>
            <p>Currently pursuing Full Stack Development training with focus on modern web technologies and software engineering best practices.</p>
        </section>
        
        <hr>
        
        <section class="contact-section">
            <h2>Contact Information</h2>
            <p><strong>Email:</strong> r.nandakishore24@gmail.com</p>
            <p><strong>Location:</strong> India</p>
        </section>
    </div>
</body>
</html>
```

## Output:

![image](https://github.com/user-attachments/assets/e7dbdfa9-2fbd-4d0d-ba93-1411cfdf400d)

## CSS Code:

```
body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
}

.profile-container {
    max-width: 600px;
    margin: auto;
    background-color: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.header-section h1 {
    text-align: center;
    color: #2c3e50;
    font-size: 2.5em;
    margin-bottom: 10px;
}

.header-section h2 {
    text-align: center;
    color: #3498db;
    font-size: 1.5em;
    margin: 5px 0;
}

.header-section h3 {
    text-align: center;
    color: #27ae60;
    font-size: 1.2em;
    margin: 5px 0;
}

.image-section img {
    display: block;
    margin: auto;
    border-radius: 50%;
    border: 4px solid #3498db;
}

.about-section {
    background-color: #ecf0f1;
    padding: 20px;
    border-radius: 8px;
    margin: 20px 0;
    border-left: 4px solid #3498db;
}

.about-section h2 {
    color: #2c3e50;
    text-align: center;
    margin-bottom: 15px;
}

.about-section p {
    line-height: 1.6;
    text-align: justify;
    margin: 0;
}

.skills-section {
    background-color: #e8f5e8;
    padding: 20px;
    border-radius: 8px;
    margin: 20px 0;
    border-left: 4px solid #27ae60;
}

.skills-section h2 {
    color: #2c3e50;
    text-align: center;
    margin-bottom: 15px;
}

.skills-section p {
    line-height: 1.6;
    margin: 10px 0;
}

.education-section {
    background-color: #fef9e7;
    padding: 20px;
    border-radius: 8px;
    margin: 20px 0;
    border-left: 4px solid #f39c12;
}

.education-section h2 {
    color: #2c3e50;
    text-align: center;
    margin-bottom: 15px;
}

.education-section p {
    line-height: 1.6;
    text-align: justify;
    margin: 0;
}

.contact-section {
    background-color: #fdedec;
    padding: 20px;
    border-radius: 8px;
    margin: 20px 0;
    border-left: 4px solid #e74c3c;
}

.contact-section h2 {
    color: #2c3e50;
    text-align: center;
    margin-bottom: 15px;
}

.contact-section p {
    line-height: 1.6;
    margin: 8px 0;
}

hr {
    border: none;
    height: 2px;
    background-color: #bdc3c7;
    margin: 25px 0;
}

section {
    margin: 25px 0;
}

strong {
    color: #2c3e50;
}

```

## Output:

![image](https://github.com/user-attachments/assets/80a1225d-c6e6-4d38-9753-7c3f2b74ba7e)

![image](https://github.com/user-attachments/assets/ab423338-4456-4956-ad3a-ae9cd74c49d1)

![image](https://github.com/user-attachments/assets/c392ddcc-c3b2-4f04-9698-97284ae81d2e)




## Result:
A simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes is designed successfully.
