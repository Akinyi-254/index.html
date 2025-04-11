<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Week 2 Assignment</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="I">
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
            <li>Item 4</li>
            <li>Item 5</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Image from Pexels</h2>
        <img src="[https://www.pexels.com/photo/three-giraffe-under-gray-sky-34098/)" alt="Giraffe under gray sky" width="600">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
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
                    <td>John ope</td>
                    <td>18 Mbasa road</td>
                    <td>0707060504</td>
                    <td>johnope@yahoo.com</td>
                </tr>
                <tr>
                    <td>Janes mith</td>
                    <td>19 Angata road</td>
                    <td>0708070605</td>
                    <td>janesmith@yahoo.com</td>
                </tr>
                <tr>
                    <td>Samu Geen</td>
                    <td>20 Ika road</td>
                    <td>0709080706</td>
                    <td>samugeen@yahoo.com</td>
                </tr>
                <tr>
                    <td>Alice Browns</td>
                    <td>21 Iyaki road</td>
                    <td>0700010203</td>
                    <td>alicebrowns@yahoo.com</td>
                </tr>
                <tr>
                    <td>Michael Johns</td>
                    <td>22 ngemi road</td>
                    <td>0701020304</td>
                    <td>michaeljohns@yahoo.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <!-- Name Field -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Create a password" required><br><br>

            <!-- Date Field -->
            <label for="date">Date of Birth:</label>
            <input type="date" id="date" name="date" required><br><br>

            <!-- Dropdown Menu -->
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="Kenya">Kenya</option>
                <option value="Uganda">Uganda</option>
                <option value="Tanzania">Tanzania</option>
            </select><br><br>

            <!-- Radio Buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="Male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="Female">
            <label for="female">Female</label><br><br>

            <!-- Checkboxes -->
            <label for="newsletter">Subscribe to newsletter:</label>
            <input type="checkbox" id="newsletter" name="newsletter"><br><br>

            <button type="submit">Submit</button>
        </form>
    </section>

    <!-- Multimedia: Audio and Video -->
    <section>
        <h2>Multimedia Elements</h2>

        <!-- Audio Element -->
        <h3>Audio Example</h3>
        <audio controls>
            <source src="https://pixabay.com/music/beats-experimental-cinematic-hip-hop-315904/" type="audio/mp3">
        </audio>

        <!-- Video Element -->
        <h3>Video Example</h3>
        <video width="600" controls>
            <source src="https://www.pexels.com/video/dynamic-drone-sunset-over-praia-pequena-colares-sintra-27379086/" type="video/mp4">
        </video>
    </section>

</body>
<footer>
    <p>&copy; 2025 Marlene Akinyi Omondi. All rights reserved.</p>
</footer>

</html>


