<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scottish Public School</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
            padding: 40px 20px;
            max-width: 900px;
            margin: auto;
        }

        h1 {
            text-align: center;
            font-size: 2.5rem;
            color: #2a4d69;
            margin-bottom: 20px;
        }

        h3 {
            font-size: 1.8rem;
            color: #4b3832;
            margin-top: 40px;
            margin-bottom: 15px;
            border-bottom: 2px solid #ccc;
            padding-bottom: 5px;
        }

        h1::after,
        h3::after {
            content: "";
            display: block;
            width: 100px;
            height: 4px;
            margin: 8px auto 0 auto;
            background: linear-gradient(to right, #0072ff, #ff0000);
            border-radius: 2px;
        }

        p {
            margin-bottom: 20px;
            text-align: justify;
            font-weight: bold;
        }

        .top-menu {
            text-align: center;
            margin-bottom: 20px;
        }

        .top-menu a {
            display: inline-block;
            margin: 10px 15px;
            padding: 12px 25px;
            font-size: 1.2rem;
            font-weight: bold;
            color: white;
            background: rgba(0, 114, 255, 0.8);
            border-radius: 25px;
            text-decoration: none;
            transition: background 0.3s, transform 0.3s;
        }

        .top-menu a:hover {
            background: rgba(255, 0, 0, 0.8);
            transform: scale(1.05);
        }

        .header-container {
            position: relative;
            width: 900px;
            height: 300px;
            margin: 0 auto 30px auto;
            border-radius: 10px;
            overflow: hidden;
        }

        .header-image {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
            border-radius: 10px;
        }

        .logo-image {
            position: absolute;
            bottom: 15px;
            right: 15px;
            width: 120px;
            height: 120px;
            object-fit: cover;
            border-radius: 10px;
            border: 3px solid white;
            background-color: white;
        }

        @media (max-width: 768px) {
            .header-container {
                width: 100%;
                height: auto;
            }

            .header-image {
                height: auto;
            }

            .logo-image {
                width: 90px;
                height: 90px;
                bottom: 10px;
                right: 10px;
            }
        }
    </style>
</head>

<body>
    <div class="top-menu">
        <a href="https://www.scottishpublicschoolkatihar.com/index.html" target="_blank">Home</a>
        <a href="http://127.0.0.1:3000/exp2.htm" target="_blank">About Us</a>
        <a href="https://www.scottishpublicschoolkatihar.com/Achievement.html" target="_blank">Top Performers</a>
        <a href="https://scottishktr.edvein.com/register" target="_blank">Admission</a>
    </div>

    <div class="header-container">
        <img src="https://www2.online-converting.com/upload/api_bf5ee64a82/result.jpg"
            alt="Scottish Public School Banner" class="header-image">
        <img src="https://www.scottishpublicschoolkatihar.com/Images/Logo1.jpg" alt="School Logo" class="logo-image">
    </div>

    <h1>Welcome to Scottish Public School</h1>
    <p>Scottish Public School established in 1991, functioned from a few tents pitched on the ground cleared from the
        onslaught of brambles. Today, spread over an area of about 3 acres of lush, green lawns, in the city of Katihar,
        Scottish Public School is a co-educational day-cum-boarding school. The foundation stone of the school building
        was laid in 1991 by Dr. Avinash. This school is under The Satyam Educational And Social Enhancement Trust.
        When technology changes, it impacts the kinds of things we want and need. Scottish Public School throughout has
        envisaged to keep the curriculum updated with the constantly changing technology in education. Consider a few of
        the key ideas incorporated in the school’s progressive education.</p>

    <h3>Our Vision</h3>
    <p>At Scottish Public School, we recognize the imperative of imparting an educational experience that is world-class
        in every respect and which prepares children for global citizenship. We are a school with an Indian mind, an
        Indian heart and an Indian soul; a school that celebrates the culture of excellence and is an embodiment of
        values. We believe that a curriculum of excellence with a global dimension is central to the education of
        children to face the challenges of the 21st century with confidence and strength of character.</p>

    <h3>Our Mission</h3>
    <p>The School's mission is to provide a learning environment that encourages children to bring out the best in
        themselves and enables their all-round development through the joy of learning, enduring values and the
        celebration of diversity.</p>
</body>

</html>
