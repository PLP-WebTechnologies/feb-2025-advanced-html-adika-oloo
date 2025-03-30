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
    <title>HTML Assignment</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Roman Numeral Ordered List</h2>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
        <li>Item Four</li>
        <li>Item Five</li>
    </ol>
    
    <!-- External Image from Pexels -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Beautiful Scenery" width="500">
    
    <!-- Contacts Table -->
    <h2>Contacts</h2>
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
                <td>Calvince Adika </td>
                <td>28570-0000, Nairobi Kenya </td>
                <td>+254735269425</td>
                <td>caadika@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak St, City</td>
                <td>+987654321</td>
                <td>jane@gmail.com</td>
            </tr>
            <tr>
                <td>Emily Brown</td>
                <td>789 Pine St, City</td>
                <td>+1122334455</td>
                <td>emily@gmail.com</td>
            </tr>
            <tr>
                <td>Michael Johnson</td>
                <td>101 Maple St, City</td>
                <td>+5566778899</td>
                <td>michael@gmail.com</td>
            </tr>
            <tr>
                <td>Sarah Wilson</td>
                <td>202 Birch St, City</td>
                <td>+6677889900</td>
                <td>sarah@gmail.com</td>
            </tr>
        </tbody>
    </table>
    
    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="POST">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter password" required minlength="6">
        <br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <!-- Dropdown -->
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
        <br><br>

        <!-- Radio Buttons -->
        <p>Choose your Subscription Plan:</p>
        <input type="radio" id="basic" name="subscription" value="basic" required>
        <label for="basic">Basic</label>
        <input type="radio" id="premium" name="subscription" value="premium">
        <label for="premium">Premium</label>
        <br><br>

        <!-- Checkboxes -->
        <p>Select Interests:</p>
        <input type="checkbox" id="tech" name="interests" value="technology">
        <label for="tech">Technology</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <br><br>

        <button type="submit">Register</button>
    </form>
</body>
</html>

