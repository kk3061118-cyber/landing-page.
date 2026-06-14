# landing-page.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sunshine Summer Camp 2026</title>

//kk3061118@gmail.com
<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
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
    padding:90px 20px;
}

header h1{
    font-size:3.5rem;
    margin-bottom:15px;
}

header p{
    font-size:1.3rem;
    margin-bottom:25px;
}

.btn{
    display:inline-block;
    background:white;
    color:#ff5722;
    text-decoration:none;
    padding:14px 30px;
    border-radius:30px;
    font-weight:bold;
    margin-bottom:25px;
    transition:0.3s;
}

.btn:hover{
    transform:translateY(-3px);
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 10px;
    padding:10px 18px;
    border-radius:20px;
    transition:0.3s;
}

nav a:hover{
    background:white;
    color:#ff5722;
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

.hero-img{
    width:100%;
    max-width:800px;
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
    background:white;
    padding:15px;
    border-radius:15px;
    text-align:center;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card img{
    width:100%;
    height:160px;
    object-fit:cover;
    border-radius:10px;
    margin-bottom:10px;
}

.card h3{
    color:#ff5722;
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
    margin:8px 0 15px;
    border:1px solid #ccc;
    border-radius:8px;
}

input[type="submit"]{
    background:#ff5722;
    color:white;
    border:none;
    cursor:pointer;
}

input[type="submit"]:hover{
    background:#e64a19;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:25px;
    margin-top:30px;
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

    <a href="#register" class="btn">Register Now</a>

    <nav>
        <a href="#about">About</a>
        <a href="#activities">Activities</a>
        <a href="#gallery">Gallery</a>
        <a href="#schedule">Schedule</a>
        <a href="#register">Register</a>
    </nav>
</header>

<section id="about">
    <h2>About Our Camp</h2>

    <img class="hero-img"
    src="https://images.unsplash.com/photo-1502086223501-7ea6ecd79368?w=1200"
    alt="Summer Camp">

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
            <img src="https://images.unsplash.com/photo-1551632811-561732d1e306?w=500" alt="Hiking">
            <h3>🥾 Hiking</h3>
            <p>Explore nature trails and enjoy outdoor adventures.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1438029071396-1e831a7fa6d8?w=500" alt="Swimming">
            <h3>🏊 Swimming</h3>
            <p>Safe and exciting water activities for everyone.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1513364776144-60967b0f800f?w=500" alt="Arts">
            <h3>🎨 Arts & Crafts</h3>
            <p>Create amazing projects and express creativity.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1574629810360-7efbbe195018?w=500" alt="Sports">
            <h3>⚽ Sports</h3>
            <p>Participate in team games and friendly competitions.</p>
        </div>

    </div>
</section>

<section id="gallery">
    <h2>Camp Gallery</h2>

    <div class="activities">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1529156069898-49953e39b3ac?w=600" alt="Camp 1">
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1517486808906-6ca8b3f04846?w=600" alt="Camp 2">
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=600" alt="Camp 3">
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
    <h3>Sunshine Summer Camp 2026</h3>
    <p>Creating unforgettable summer memories.</p>
    <p>Email: info@sunshinecamp.com | Phone: +91 9876543210</p>
    <p>&copy; 2026 Sunshine Summer Camp. All Rights Reserved.</p>
</footer>

</body>
</html>