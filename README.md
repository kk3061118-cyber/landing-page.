# landing-page.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

   //kk3061118@gmail.com

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunshine Summer Camp 2026</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }

        body{
            font-family:Arial, sans-serif;
            background:#f4f7fb;
            color:#333;
            line-height:1.6;
        }

        header{
            background:linear-gradient(135deg,#ff9800,#ff5722);
            color:white;
            text-align:center;
            padding:70px 20px;
        }

        header h1{
            font-size:3rem;
            margin-bottom:10px;
        }

        header p{
            font-size:1.2rem;
            margin-bottom:20px;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:0 12px;
            font-weight:bold;
        }

        nav a:hover{
            text-decoration:underline;
        }

        section{
            width:90%;
            max-width:1100px;
            margin:30px auto;
            background:white;
            padding:30px;
            border-radius:15px;
            box-shadow:0 5px 15px rgba(0,0,0,0.1);
        }

        h2{
            text-align:center;
            color:#ff5722;
            margin-bottom:20px;
        }

        img{
            width:100%;
            max-width:700px;
            display:block;
            margin:20px auto;
            border-radius:15px;
        }

        .activities{
            display:flex;
            flex-wrap:wrap;
            gap:20px;
            justify-content:center;
        }

        .card{
            width:230px;
            background:#fff7f2;
            padding:20px;
            border-radius:12px;
            text-align:center;
            box-shadow:0 3px 10px rgba(0,0,0,0.1);
        }

        .card h3{
            color:#ff5722;
            margin-bottom:10px;
        }

        table{
            width:100%;
            border-collapse:collapse;
        }

        th{
            background:#ff5722;
            color:white;
        }

        th,td{
            border:1px solid #ddd;
            padding:12px;
            text-align:center;
        }

        form{
            max-width:500px;
            margin:auto;
        }

        input{
            width:100%;
            padding:12px;
            margin-top:5px;
            margin-bottom:15px;
            border:1px solid #ccc;
            border-radius:8px;
        }

        input[type="submit"]{
            background:#ff5722;
            color:white;
            border:none;
            cursor:pointer;
        }

        footer{
            background:#222;
            color:white;
            text-align:center;
            padding:25px;
            margin-top:30px;
        }

        footer a{
            color:#ff9800;
        }

        @media(max-width:768px){
            header h1{
                font-size:2rem;
            }

            .activities{
                flex-direction:column;
                align-items:center;
            }

            .card{
                width:100%;
                max-width:350px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>☀ Sunshine Summer Camp 2026</h1>
    <p>Learn • Explore • Make New Friends • Create Memories</p>

    <nav>
        <a href="#about">About</a>
        <a href="#activities">Activities</a>
        <a href="#schedule">Schedule</a>
        <a href="#register">Register</a>
    </nav>
</header>

<section id="about">
    <h2>About Our Camp</h2>

    <img src="assets/image.jpg" alt="Summer Camp">

    <p>
        Welcome to <strong>Sunshine Summer Camp</strong>! Our camp offers
        exciting outdoor adventures, creative workshops, sports activities,
        and opportunities to build leadership skills.
    </p>

    <br>

    <p>
        <em>Limited Seats Available – Register Early!</em>
    </p>
</section>

<section id="activities">
    <h2>Camp Activities</h2>

    <div class="activities">

        <div class="card">
            <h3>🥾 Hiking</h3>
            <p>Explore nature and beautiful trails.</p>
        </div>

        <div class="card">
            <h3>🏊 Swimming</h3>
            <p>Fun water activities with supervision.</p>
        </div>

        <div class="card">
            <h3>🎨 Arts & Crafts</h3>
            <p>Creative projects and learning experiences.</p>
        </div>

        <div class="card">
            <h3>⚽ Sports</h3>
            <p>Team games and friendly competitions.</p>
        </div>

    </div>
</section>

<section id="schedule">
    <h2>Weekly Schedule</h2>

    <table>
        <tr>
            <th>Day</th>
            <th>Activity</th>
        </tr>

        <tr>
            <td>Monday</td>
            <td>Welcome & Team Building</td>
        </tr>

        <tr>
            <td>Tuesday</td>
            <td>Outdoor Adventure</td>
        </tr>

        <tr>
            <td>Wednesday</td>
            <td>Arts & Crafts Workshop</td>
        </tr>

        <tr>
            <td>Thursday</td>
            <td>Sports Tournament</td>
        </tr>

        <tr>
            <td>Friday</td>
            <td>Camp Celebration</td>
        </tr>
    </table>
</section>

<section id="register">
    <h2>Register Now</h2>

    <form>
        <label>Name</label>
        <input type="text" placeholder="Enter your name">

        <label>Email</label>
        <input type="email" placeholder="Enter your email">

        <label>Age</label>
        <input type="number" placeholder="Enter your age">

        <input type="submit" value="Register">
    </form>
</section>

<footer>
    <p>&copy; 2026 Sunshine Summer Camp</p>
    <p>
        Contact:
        <a href="mailto:camp@example.com">camp@example.com</a>
    </p>
</footer>

</body>
</html>