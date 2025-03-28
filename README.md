# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨






<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Demo Page</title>
    <!-- Basic CSS for styling -->
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; }
        table { border-collapse: collapse; width: 100%; }
        th, td { border: 1px solid #ddd; padding: 8px; text-align: left; }
        th { background-color: #f2f2f2; }
        form { max-width: 400px; margin-top: 20px; }
        label { display: block; margin-bottom: 5px; }
        input, select { width: 100%; padding: 8px; margin-bottom: 10px; }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My HTML5 Demo Page</h1>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Ordered List with Roman Numerals -->
        <section>
            <h2>My Favorite Activities</h2>
            <ol type="I">
                <li>Reading Books</li>
                <li>Playing Guitar</li>
                <li>Coding Projects</li>
                <li>Hiking</li>
                <li>Watching Movies</li>
            </ol>
        </section>

        <!-- External Image from Pexels -->
        <section>
            <h2>A Beautiful Image</h2>
            <img src="https://images.pexels.com/photos/417074/pexels-photo-417074.jpeg" 
                 alt="Mountain Landscape" 
                 width="500" 
                 height="300">
        </section>

        <!-- Table of 5 Contacts -->
        <section>
            <h2>Contact List</h2>
            <table>
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile</th>
                        <th>Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>John Doe</td>
                        <td>123 Elm St, NY</td>
                        <td>555-1234</td>
                        <td>john.doe@example.com</td>
                    </tr>
                    <tr>
                        <td>Jane Smith</td>
                        <td>456 Oak Rd, CA</td>
                        <td>555-5678</td>
                        <td>jane.smith@example.com</td>
                    </tr>
                    <tr>
                        <td>Bob Jared</td>
                        <td>789 Pine Ave, TX</td>
                        <td>555-9012</td>
                        <td>bob.j@example.com</td>
                    </tr>
                    <tr>
                        <td>Alice Betty</td>
                        <td>321 Maple Dr, FL</td>
                        <td>555-3456</td>
                        <td>alice.b@example.com</td>
                    </tr>
                    <tr>
                        <td>Tom Wilson</td>
                        <td>654 Cedar Ln, WA</td>
                        <td>555-7890</td>
                        <td>tom.wilson@example.com</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Registration Form -->
        <section>
            <h2>Registration Form</h2>
            <form action="#" method="post">
                <!-- Name Field -->
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>

                <!-- Email Field -->
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>

                <!-- Password Field -->
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" 
                       placeholder="Enter your password" 
                       minlength="8" required>

                <!-- Date of Birth Field -->
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required>

                <!-- Dropdown for Country -->
                <label for="country">Country:</label>
                <select id="country" name="country" required>
                    <option value="">Select your country</option>
                    <option value="usa">USA</option>
                    <option value="uk">UK</option>
                    <option value="india">India</option>
                    <option value="canada">Canada</option>
                </select>

                <!-- Radio Buttons for Gender -->
                <label>Gender:</label>
                <input type="radio" id="male" name="gender" value="male" required>
                <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Female</label>
                <input type="radio" id="other" name="gender" value="other">
                <label for="other">Other</label>

                <!-- Checkboxes for Interests -->
                <label>Interests:</label>
                <input type="checkbox" id="coding" name="interests" value="coding">
                <label for="coding">Coding</label>
                <input type="checkbox" id="music" name="interests" value="music">
                <label for="music">Music</label>
                <input type="checkbox" id="sports" name="interests" value="sports">
                <label for="sports">Sports</label>

                <!-- Submit Button -->
                <input type="submit" value="Register">
            </form>
        </section>

        <!-- Multimedia Elements -->
        <section>
            <h2>Multimedia Demo</h2>
            <!-- Audio Element -->
            <audio controls>
                <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
                Your browser does not support the audio element.
            </audio>

            <!-- Video Element -->
            <video width="500" height="300" controls>
                <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
                Your browser does not support the video element.
            </video>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 HTML5 Demo Page. All rights reserved.</p>
    </footer>
</body>
</html> 




