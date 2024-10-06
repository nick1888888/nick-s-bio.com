<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nick's Bio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: url('andrzej-kryszpiniuk-zUqFqeG03-k-unsplash.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #ffffff;
            position: relative;
            overflow: hidden;
        }

        header {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            z-index: 1;
            border-bottom: 2px solid #f8e71c;
        }

        h1 {
            font-size: 2.5em;
            margin: 0;
            color: #000080; /* Dark blue */
        }

        p {
            color: #ffd700; /* Gold */
        }

        .container {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
            position: relative;
            z-index: 1;
            animation: colorShift 8s infinite alternate; /* Box animation */
        }

        @keyframes colorShift {
            0% { background-color: rgba(255, 255, 255, 0.2); }
            50% { background-color: rgba(255, 255, 0, 0.5); }
            100% { background-color: rgba(255, 0, 0, 0.5); }
        }

        .bio img.profile-img {
            width: 150px;
            height: auto;
            border-radius: 50%;
            margin-top: 10px;
            border: 3px solid #f8e71c;
        }

        h2 {
            color: #4B0082; /* Dark purple */
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin: 5px 0;
            color: #ffffff;
        }

        .banner {
            width: 100%;
            height: 50px; /* Adjusted banner size */
            background: linear-gradient(90deg, magenta, darkorange, teal, darkred, cyan);
            background-size: 300% 300%;
            animation: colorBannerShift 8s infinite alternate;
            position: fixed;
            bottom: 0;
            left: 0;
            z-index: 10;
        }

        @keyframes colorBannerShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #ddd;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 2em;
            }

            .container {
                padding: 10px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Nick</h1>
        <p>Pronouns: he/him | Gender: Male | Sexuality: Straight</p>
    </header>

    <div class="container">
        <section id="about" class="bio">
            <h2>About Me</h2>
            <p>My name is Nick, and I like chess, astronomy, and nature.</p>
            <img src="WhatsApp Image 2024-05-19 at 18.33.06_3c2a80c4.jpg" alt="Nick" class="profile-img"> <!-- Placeholder image -->
        </section>

        <section id="hobbies" class="hobbies">
            <h2>Hobbies</h2>
            <ul>
                <li>Chess</li>
                <li>Long Walks</li>
                <li>Watching Movies/Series</li>
                <li>Listening 24/7 to Spotify</li>
                <li>Writing Poems</li>
            </ul>
        </section>

        <section id="extra" class="extra">
            <h2>Extra</h2>
            <ul>
                <li>MBTI: INFJ</li>
                <li>Favorite Anime: The Garden of Sinners</li>
                <li><a href="https://www.wattpad.com/user/17nickk" target="_blank">Read my poems on Wattpad</a></li>
            </ul>
        </section>

        <footer>
            <p>© 2024 Nick. All rights reserved.</p>
        </footer>
    </div>

    <div class="banner"></div> <!-- Smaller animated banner with rare colors -->

    <script>
        console.log("Welcome to my bio page!");
    </script>
</body>
</html>
