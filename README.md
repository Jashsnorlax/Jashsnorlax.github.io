<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Jash Bacucang</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        h1, h2 {
            color: #333;
            text-align: center;
            margin-top: 20px;
        }

        p {
            text-align: center;
            max-width: 600px;
            margin: 20px auto;
            font-size: 1.1em;
        }

        img {
            display: block;
            margin: 20px auto;
            border-radius: 50%;
            border: 3px solid #333;
        }

        ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
        }

        ul li {
            display: inline-block;
            margin: 10px;
            padding: 10px 15px;
            background-color: #008cba;
            color: white;
            border-radius: 5px;
            font-weight: bold;
        }

        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            background-color: #fff;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 12px;
            text-align: center;
            font-size: 1em;
        }

        th {
            background-color: #333;
            color: #fff;
        }

        tr:nth-child(even) {
            background-color: #f4f4f9;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <header>
        <h1>Portfolio</h1>
    </header>

    <main>
        <img src="JASH.jpg" alt="Profile Picture" width="200">

        <section>
            <p>
                Hello! My name is Joseph Jash Bacucang, and I'm passionate about web development and design.
                I love exploring new technologies and bonding with my friends and family. I also love to cook, travel,
                play sports, play games, and work out.
            </p>
        </section>

        <section>
            <h2>My Hobbies</h2>
            <ul>
                <li>Cooking</li>
                <li>Traveling</li>
                <li>Photography</li>
                <li>Playing sports</li>
                <li>Going to the gym</li>
                <li>Playing online games</li>
                <li>Drawing</li>
            </ul>
        </section>

        <section>
            <h2>My Family</h2>
            <table>
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Relation</th>
                        <th>Age</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Joseph Jash Bacucang</td>
                        <td>Student</td>
                        <td>18</td>
                    </tr>
                    <tr>
                        <td>Grace Galon</td>
                        <td>Mother</td>
                        <td>41</td>
                    </tr>
                    <tr>
                        <td>Eugene Bacucang</td>
                        <td>Father</td>
                        <td>39</td>
                    </tr>
                    <tr>
                        <td>Kristoff Bacucang</td>
                        <td>Little Brother</td>
                        <td>14</td>
                    </tr>
                    <tr>
                        <td>Eugene Bacucang Jr.</td>
                        <td>Little Brother</td>
                        <td>11</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>

    <footer>
        &copy; 2024 Joseph Jash Bacucang. All rights reserved.
    </footer>

    <!-- Add this to the end of the code -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            alert('Welcome to my portfolio!');
        });
    </script>
</body>

</html>
