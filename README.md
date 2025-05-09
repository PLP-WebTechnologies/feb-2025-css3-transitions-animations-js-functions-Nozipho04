<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Living In The World Of AI</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #272840;
            font-family: Arial, sans-serif;
            display: flex;
            min-height: 100vh;
        }

        /* Sidebar navigation */
        .sidebar {
            width: 200px;
            background-color: #cbcdf7;
            padding: 40px 20px;
        }

        .sidebar ul {
            list-style: none;
        }

        .sidebar li {
            margin-bottom: 20px;
        }

        .sidebar a {
            text-decoration: none;
            color: #272840;
            font-weight: bold;
            font-size: 18px;
            transition: color 0.3s ease;
        }

        .sidebar a:hover {
            color: #555;
        }

        /* Main content */
        .content {
            flex: 1;
            padding: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .image-text {
            display: flex;
            align-items: center;
            gap: 40px;
            flex-wrap: wrap;
        }

        .image-text img {
            width: 300px;
            max-width: 100%;
            height: auto;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0% {
                transform: translateY(0px);
            }

            50% {
                transform: translateY(-15px);
            }

            100% {
                transform: translateY(0px);
            }
        }

        .image-text h1 {
            font-size: 48px;
            color: white;
            max-width: 400px;
        }
    </style>
</head>

<body>
    <!-- Sidebar navigation -->
    <nav class="sidebar">
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">TheGood</a></li>
            <li><a href="#">TheBad</a></li>
            <li><a href="#">CLOSING</a></li>
        </ul>
    </nav>

    <!-- Main content -->
    <div class="content">
        <div class="image-text">
            <img src="female-ai-android-face-shot-isolated-transparent-background_879541-1046-removebg-preview.png"
                alt="Futuristic female AI face">
            <h1>Living In The World Of AI</h1>
        </div>
    </div>
</body>

</html>
