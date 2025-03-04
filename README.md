<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore The World</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #667eea, #764ba2);
            text-align: center;
            color: white;
        }
        .hero {
            background: url('https://source.unsplash.com/1600x900/?travel') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            position: relative;
        }
        .hero-content {
            background: rgba(0, 0, 0, 0.6);
            padding: 30px;
            border-radius: 15px;
            max-width: 500px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
        }
        .cta {
            background: linear-gradient(45deg, #ff6600, #ff3300);
            padding: 15px 35px;
            color: white;
            text-decoration: none;
            font-size: 22px;
            border-radius: 50px;
            margin-top: 20px;
            display: inline-block;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0px 5px 15px rgba(255, 102, 0, 0.6);
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .cta:hover {
            background: linear-gradient(45deg, #ff3300, #cc0000);
            transform: scale(1.1);
            box-shadow: 0px 8px 20px rgba(255, 51, 0, 0.8);
        }
        .hero img {
            width: 80px;
            height: 80px;
            margin-bottom: 20px;
            border-radius: 50%;
            box-shadow: 0px 4px 10px rgba(255, 255, 255, 0.5);
        }
        .extra-img {
            width: 120px;
            height: auto;
            margin-top: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(255, 255, 255, 0.5);
        }
    </style>
</head>
<body>
    <div class="hero">
        <img src="C:\Users\Karthik\Pictures\n.jpg" alt="Travel Logo">
        <div class="hero-content">
            <h1>Discover Your Next Adventure</h1>
            <p>Travel the world with us and explore stunning destinations.</p>
            <a href="#" class="cta">Book Now</a>
        </div>
        <img src="C:\Users\Karthik\Pictures\7886229d-0746-4349-8f43-d0b67e36fa46.jpg"alt="Extra Image" class="extra-img">
    </div>
</body>
</html>
