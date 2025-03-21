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
    <title>HTML Example</title>
</head>
<body>

    <h1>HTML Elements Example</h1>

    <h2>Ordered List</h2>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
        <li>Item Four</li>
        <li>Item Five</li>
    </ol>

    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="Nature Image" width="500">

    <h2>Contact Table</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Michael Ngige</th>
                <th>210 kenlands ke</th>
                <th>0705160142</th>
                <th>ngigemike30@gmail.com</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Jane kimz</td>
                <td>542 langa ke</td>
                <td>004-123-453</td>
                <td>janekimz45@gmail.com</td>
            </tr>
            <tr>
                <td>sarah wanja</td>
                <td>657 pine ke</td>
                <td>+254 767 345 213</td>
                <td>sarahm34@gmail.com</td>
            </tr>
            <tr>
                <td>David  martin</td>
                <td>544 nakuru ke</td>
                <td>555-123-4567</td>
                <td>davd12@gmail.com.com</td>
            </tr>
            <tr>
                <td>ashyln totoz</td>
                <td>156 subukia ke</td>
                <td>111-222-3333</td>
                <td>ashtot3@gmail.com</td>
            </tr>
            <tr>
                <td>Michael murimi</td>
                <td>202 nanyuki ke</td>
                <td>444-555-6666</td>
                <td>michael004@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <h2>Registration Form</h2>
    <form action="#" method="post">
        <fieldset>
            <legend>User Registration</legend>

            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

            <label for="date">Date of Birth:</label><br>
            <input type="date" id="date" name="date" required><br><br>

            <label for="country">Country:</label><br>
            <select id="country" name="country">
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
                <option value="other">Other</option>
            </select><br><br>

            <p>Gender:</p>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>

            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label><br>

            <input type="radio" id="other_gender" name="gender" value="other">
            <label for="other_gender">Other</label><br><br>

            <p>Interests:</p>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br>

            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>

            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label><br><br>

            <input type="submit" value="Register">
        </fieldset>
    </form>

</body>
</html>
