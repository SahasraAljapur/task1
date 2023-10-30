# task1
# this is the main page of this website
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #460000;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }

        nav {
            background-color: #2b0101;
            text-align: center;
            padding: 0.5rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        .content {
            padding: 2rem;
            text-align: center;
        }

        footer {
            background-color: #460000;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        @media (max-width: 768px) {
            nav {
                display: flex;
                flex-direction: column;
                align-items: center;
            }

            nav a {
                margin: 10px 0;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Landing Page</h1>
    </header>
    <nav>
        <a href="about.html">About</a>
        <a href="services.html">Services</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="content">
        <h2>Welcome to our Simple Landing Page</h2>
        <p>This is a landing page created using HTML and CSS. It is responsive and works well on both desktop and mobile devices.</p>
    </div>
    <footer>
        <p>This page is created by Sahasra Aljapur to complete the task(1) given by Main Flow Services and Technologies.</p>
    </footer>
</body>

</html>
