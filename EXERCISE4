<?php
// Check if form is submitted
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // Handle POST request
    $name = htmlspecialchars($_POST['name']);
    $age = htmlspecialchars($_POST['age']);
    $post_result = "<p>Received via POST: Name = $name, Age = $age</p>";
} elseif (isset($_GET['name']) && isset($_GET['age'])) {
    // Handle GET request
    $name = htmlspecialchars($_GET['name']);
    $age = htmlspecialchars($_GET['age']);
    $get_result = "<p>Received via GET: Name = $name, Age = $age</p>";
}
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Team</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        .team-section {
            text-align: center;
            margin-bottom: 40px;
        }
        .team-section h1 {
            margin-bottom: 10px;
            font-size: 36px;
            color: #333;
        }
        .team-section p {
            color: #777;
            font-size: 18px;
        }
        .team-member {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }
        .team-member img {
            border-radius: 50%;
            margin-right: 20px;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .team-member div {
            text-align: left;
        }
        .team-member h2 {
            margin: 0 0 10px;
            font-size: 24px;
            color: #333;
        }
        .team-member h3 {
            margin: 0 0 15px;
            font-size: 18px;
            color: #666;
        }
        .team-member p {
            color: #555;
            line-height: 1.5;
        }
        .team-member a {
            color: #3b5998;
            text-decoration: none;
            font-size: 16px;
            margin-right: 10px;
        }
        .team-member a.instagram {
            color: #e4405f;
        }
        .java-code {
            margin-top: 40px;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }
        .java-code pre {
            background-color: #f4f4f4;
            padding: 20px;
            border-radius: 8px;
            overflow-x: auto;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="team-section">
            <h1>Meet Our Team</h1>
            <p>We are a team of dedicated students who are developing our skills and pursuing success.</p>
        </div>

        <!-- Team Members -->
        <div class="team-member">
            <img src="https://assets.onecompiler.app/42ptcg8wy/42ptc3e48/Joseph.jpg" alt="Joseph Manuel">
            <div>
                <h2>Joseph Manuel</h2>
                <h3>Leader</h3>
                <p>Hi, I'm Joseph, 21 years old, a 3rd-year student at PLMUN currently pursuing a Bachelor of Science in Information Technology.</p>
                <a href="https://www.facebook.com/joseph.manuel.5437923" target="_blank">Facebook</a>
                <a href="https://www.instagram.com/bio_joseph0?igsh=ODY1MHpzNG8zcnAz" target="_blank" class="instagram">Instagram</a>
            </div>
        </div>

        <!-- Additional team members (as needed) -->
         <!-- Team Member 2 -->
        <div class="team-member">
            <img src="https://assets.onecompiler.app/42ptcg8wy/42ptc3e48/Alfred.jpg" alt="Alfred Divinagracia">
            <div>
                <h2>Alfred Divinagracia</h2>
                <h3>Member</h3>
                <p>Hello, I'm Alfred, a 21-year-old third-year Bachelor of Science in Information Technology student.</p>
                <a href="https://www.facebook.com/alfred.vergara.7737?mibextid=ZbWKwL" target="_blank">Facebook</a>
                <a href="https://www.instagram.com/afrdvrgra?igsh=bjQwcHM4dnlyY3A5" target="_blank" class="instagram">Instagram</a>
            </div>
        </div>

        <!-- Team Member 3 -->
        <div class="team-member">
            <img src="https://assets.onecompiler.app/42ptcg8wy/42ptc3e48/Thaniell.jpg" alt="Thaniell Maravilla">
            <div>
                <h2>Thaniell Maravilla</h2>
                <h3>Member</h3>
                <p>Hello! I'm Thaniell, and I love solving problems and making things easier.</p>
                <a href="https://www.facebook.com/Thaniell.parafina?mibextid=ZbWKwL" target="_blank">Facebook</a>
                <a href="https://www.instagram.com/whosthaniell__?igsh=MWZqMWI3a2lobmpoMg==" target="_blank" class="instagram">Instagram</a>
            </div>
        </div>

        <!-- Team Member 4 -->
        <div class="team-member">
            <img src="https://assets.onecompiler.app/42ptcg8wy/42ptc3e48/LUIS%20M.jpg" alt="Luis Montillano">
            <div>
                <h2>Luis Montillano</h2>
                <h3>Member</h3>
                <p>Hi, I'm Luis, a 20-year-old student currently pursuing a Bachelor of Science in Information Technology.</p>
                <a href="https://www.facebook.com/luisqt0419?mibextid=ZbWKwL" target="_blank">Facebook</a>
                <a href="https://www.instagram.com/luwiisssz?igsh=MTBheGd3dnRwN25tNw==" target="_blank" class="instagram">Instagram</a>
            </div>
        </div>


        <!-- GET and POST Form Section -->
        <div>
            <h2>Submit Your Info (GET)</h2>
            <form method="GET" action="">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" required><br><br>
                <input type="submit" value="Submit via GET">
            </form>

            <h2>Submit Your Info (POST)</h2>
            <form method="POST" action="">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" required><br><br>
                <input type="submit" value="Submit via POST">
            </form>

            <!-- Display Results -->
            <?php
            if (isset($post_result)) {
                echo $post_result;
            }
            if (isset($get_result)) {
                echo $get_result;
            }
            ?>
        </div>

        <!-- Java Code Section -->
        <div class="java-code">
            <h2>Sample Java Code:</h2>
            <pre>
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
            </pre>
        </div>
    </div>
</body>
</html>
