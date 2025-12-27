# 📘 Assignment: Enhancing HTML5 Content & Mastering Forms

## Overview

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Enhanced HTML5 Content and Forms Assignment">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enhanced HTML5 Content & Forms</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            line-height: 1.6;
        }

        header, section, footer {
            margin-bottom: 30px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        table, th, td {
            border: 1px solid #333;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        fieldset {
            margin-bottom: 20px;
            padding: 15px;
        }

        legend {
            font-weight: bold;
        }

        label {
            display: block;
            margin-top: 10px;
        }

        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
        }
    </style>
</head>

<body>

<header>
    <h1>Enhancing HTML5 Content & Mastering Forms</h1>
    <p>This page demonstrates advanced HTML5 content elements and a fully validated HTML5 form.</p>
</header>

<!-- SECTION: LISTS -->
<section>
    <h2>Popular Web Technologies</h2>

    <h3>Frontend Technologies</h3>
    <ul>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
    </ul>

    <h3>Backend Technologies</h3>
    <ol>
        <li>Node.js</li>
        <li>Python</li>
        <li>PHP</li>
    </ol>
</section>

<!-- SECTION: TABLE -->
<section>
    <h2>Course Schedule</h2>

    <table>
        <thead>
            <tr>
                <th>Day</th>
                <th>Topic</th>
                <th>Duration</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Monday</td>
                <td>HTML5 Basics</td>
                <td>2 Hours</td>
            </tr>
            <tr>
                <td>Wednesday</td>
                <td>Forms & Validation</td>
                <td>3 Hours</td>
            </tr>
            <tr>
                <td>Friday</td>
                <td>Media & Tables</td>
                <td>2 Hours</td>
            </tr>
        </tbody>
    </table>
</section>

<!-- SECTION: MEDIA -->
<section>
    <h2>Embedded Media</h2>

    <figure>
        <img src="https://via.placeholder.com/600x300" alt="Sample placeholder image">
        <figcaption>Sample Image Embedded Using HTML5</figcaption>
    </figure>

    <h3>Sample Audio</h3>
    <audio controls>
        <source src="sample-audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <h3>Sample Video</h3>
    <video controls width="400">
        <source src="sample-video.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>
</section>

<!-- SECTION: FORM -->
<section>
    <h2>User Registration Form</h2>

    <form action="#" method="post" autocomplete="on">

        <fieldset>
            <legend>Personal Information</legend>

            <label for="fullname">Full Name</label>
            <input type="text" id="fullname" name="fullname"
                   placeholder="Enter your full name"
                   required minlength="3">

            <label for="email">Email Address</label>
            <input type="email" id="email" name="email"
                   placeholder="example@email.com"
                   required>

            <label for="phone">Phone Number</label>
            <input type="tel" id="phone" name="phone"
                   placeholder="0712345678"
                   pattern="[0-9]{10}"
                   required>
        </fieldset>

        <fieldset>
            <legend>Account Details</legend>

            <label for="username">Username</label>
            <input type="text" id="username" name="username"
                   required minlength="5">

            <label for="password">Password</label>
            <input type="password" id="password" name="password"
                   required minlength="8">

            <label for="accountType">Account Type</label>
            <select id="accountType" name="accountType" required>
                <option value="">-- Select --</option>
                <option value="student">Student</option>
                <option value="professional">Professional</option>
                <option value="admin">Administrator</option>
            </select>
        </fieldset>

        <fieldset>
            <legend>Additional Information</legend>

            <label for="dob">Date of Birth</label>
            <input type="date" id="dob" name="dob" required>

            <label for="bio">Short Bio</label>
            <textarea id="bio" name="bio"
                      placeholder="Tell us about yourself"
                      minlength="10"></textarea>

            <label>
                <input type="checkbox" name="terms" required>
                I agree to the terms and conditions
            </label>
        </fieldset>

        <button type="submit">Submit Form</button>

    </form>
</section>

<footer>
    <p>&copy; 2025 HTML5 Assignment. All rights reserved.</p>
</footer>

</body>
</html>
