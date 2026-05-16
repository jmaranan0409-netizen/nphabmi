<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>My Personal Profile</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{

    margin:0;

    padding:0;

    box-sizing:border-box;

    font-family:'Poppins', sans-serif;

}

body{

    background:#fff0f5;

    color:#444;

    line-height:1.8;

}

/* HEADER */

header{

    background:linear-gradient(to right,#ff66b2,#ff99cc);

    color:white;

    text-align:center;

    padding:60px 20px;

}

header img{

    width:170px;

    height:170px;

    border-radius:50%;

    border:5px solid white;

    object-fit:cover;

    margin-top:20px;

    box-shadow:0 4px 10px rgba(0,0,0,0.2);

}

header h1{

    font-size:40px;

    margin-bottom:10px;

}

header p{

    font-size:18px;

}

/* NAVIGATION */

nav{

    background:#ff85c1;

    padding:15px;

    position:sticky;

    top:0;

    z-index:1000;

    box-shadow:0 2px 8px rgba(0,0,0,0.1);

}

nav ul{

    display:flex;

    justify-content:center;

    flex-wrap:wrap;

    list-style:none;

}

nav ul li{

    margin:10px;

}

nav ul li a{

    text-decoration:none;

    color:white;

    font-weight:600;

    transition:0.3s;

}

nav ul li a:hover{

    color:yellow;

}

/* SECTION DESIGN */

section{

    background:white;

    margin:25px;

    padding:35px;

    border-radius:20px;

    box-shadow:0 4px 12px rgba(0,0,0,0.08);

    transition:0.3s;

}

section:hover{

    transform:translateY(-5px);

}

h2{

    color:#ff4fa3;

    margin-bottom:20px;

    font-size:30px;

}

h3{

    color:#ff66b2;

    margin-top:20px;

    margin-bottom:10px;

}

/* GALLERY */

.gallery{

    display:grid;

    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));

    gap:20px;

    margin-top:20px;

}

.gallery div{

    background:#fff7fb;

    padding:15px;

    border-radius:15px;

    text-align:center;

    box-shadow:0 2px 10px rgba(0,0,0,0.08);

}

.gallery img{

    width:100%;

    border-radius:15px;

    transition:0.3s;

}

.gallery img:hover{

    transform:scale(1.05);

}

/* FOOTER */

footer{

    background:#ff66b2;

    color:white;

    text-align:center;

    padding:25px;

    margin-top:30px;

}

footer a{

    color:white;

    text-decoration:none;

    margin:0 10px;

    font-weight:600;

}

footer a:hover{

    color:yellow;

}

/* RESPONSIVE */

@media(max-width:768px){

    nav ul{

        flex-direction:column;

        align-items:center;

    }

    header h1{

        font-size:30px;

    }

    section{

        margin:15px;

        padding:25px;

    }

}

</style>

</head>

<body>

<header>

    <h1>My Personal Profile</h1>

    <p></p>

    <img src="E6897109-296F-4481-BF30-2429523462D0.jpeg" alt="Profile Picture">

</header>

<nav>

<ul>

    <li><a href="#personal">Personal</a></li>

    <li><a href="#education">Education</a></li>

    <li><a href="#family">Family</a></li>

    <li><a href="#collections">Collections</a></li>

    <li><a href="#friends">Friends</a></li>

    <li><a href="#achievements">Achievements</a></li>

    <li><a href="#gallery">Gallery</a></li>

    <li><a href="#advocacy">Advocacy</a></li>

</ul>

</nav>

<section id="personal">

    <h2>Personal Menu</h2>

    <p><strong>Full Name:</strong> Judy Ann B. Maranan</p>

    <p><strong>Age:</strong> 28 years old</p>

    <p><strong>Birthday:</strong> April 09, 1998</p>

    <p><strong>Favorite Color:</strong> Pink</p>

    <p><strong>Address:</strong> L5 B6 Carmona St. cor., Agueda Vista Verde Executive Village, Cainta, Rizal</p>

    <p><strong>Hobbies:</strong> Watching Basketball, Baking, Playing with my Dogs, and Coffee Hopping</p>

    <br>

    <p>

        Hi! I am Judy Ann Maranan. I am a college student who loves learning new things,

        spending time with family, friends, and especially with my dogs while exploring creative ideas.

        My dream is to become successful and inspire others through hard work and kindness.

    </p>

</section>

<section id="education">

    <h2>Educational Menu</h2>

    <h3>Grade School</h3>

    <p>

        I studied at Urdaneta Elementary School where I learned the importance of education,

        discipline, and friendship. My grade school years were filled with fun memories,

        school activities, and experiences that helped shape who I am today.

    </p>

    <h3>High School</h3>

    <p>

        I studied at Bendita National High School where I discovered my strengths,

        built my confidence, and met friends who became part of my journey.

        During these years, I joined different school activities that helped me grow personally and socially.

    </p>

    <h3>College</h3>

    <p>

        I studied BS Accountancy at AMA University Quezon City which helped me gain knowledge and experience.

    </p>

    <p>

        I am currently studying at LPU Manila taking up Customs Administration.

        As a college student, I continue to challenge myself, learn new things,

        and work hard to achieve my dreams and build a successful future.

    </p>

</section>

<section id="family">

    <h2>Family Menu</h2>

    <h3>Father</h3>

    <p>

        My father is hardworking, responsible, and always willing to sacrifice for our family.

        He inspires me to stay strong and never give up in life.

    </p>

    <h3>Mother</h3>

    <p>

        My mother is loving, caring, and supportive in everything I do.

        She motivates me to become a better person and always reminds me to believe in myself.

    </p>

    <h3>Siblings</h3>

    <p>

        My siblings are not only part of my family but also my best friends.

        I enjoy spending time with them, sharing laughter, and creating happy memories together.

    </p>

</section>

<section id="collections">

    <h2>Collections / Interests Menu</h2>

    <p>

        I love collecting Snoopy items because they make me happy and remind me of childhood memories.

    </p>

</section>

<section id="friends">

    <h2>Friends Menu</h2>

    <h3>School Friends</h3>

    <p>

        My school friends make my college life more enjoyable and meaningful.

        They support me during stressful times, motivate me to do better,

        and create unforgettable memories with me.

    </p>

    <p><em>"Friends are the family we choose."</em></p>

</section>

<section id="achievements">

    <h2>Achievements Menu</h2>

    <ul>

        <li>Graduated Elementary and High School with Special Award</li>

        <li>Passed the NCIII Bookkeeping Assessment in 2018</li>

        <li>Passed the IC3 Assessment</li>

    </ul>

</section>

<section id="gallery">

    <h2>Gallery Menu</h2>

    <div class="gallery">

        <div>

            <img src="photo1.jpg" alt="Gallery Photo">

            <p>“A moment worth remembering.”</p>

        </div>

        <div>

            <img src="photo2.jpg" alt="Gallery Photo">

            <p>“Small memories, big happiness.”</p>

        </div>

        <div>

            <img src="photo3.jpg" alt="Gallery Photo">

            <p>“Growth through every season.”</p>

        </div>

    </div>

</section>

<section id="advocacy">

    <h2>Advocacy / Awareness for Social Change</h2>

    <h3>Mental Health Awareness</h3>

    <p>

        Mental health awareness is important because many people silently struggle with stress,

        anxiety, and emotional challenges. By spreading awareness, showing kindness,

        and encouraging open communication, we can help create a more supportive and understanding community.

    </p>

</section>

<footer>

    <p>Thank you for visiting my website!</p>

    <br>

    <a href="https://www.facebook.com/share/1KPvi4ufrd/?mibextid=wwXIfr" target="_blank">

        💙 Facebook

    </a>

    |

    <a href="https://www.instagram.com/nphabmi_09?igsh=MWZhdHU3bGNrNzAxMQ%3D%3D&utm_source=qr" target="_blank">

        💖 Instagram

    </a>

    |

    <a href="mailto:jmaranan0409@yahoo.com">

        📧 Email Me

    </a>

    <br><br>

    <p>© 2026 Judy Ann Maranan | All Rights Reserved</p>

</footer>

<script>

alert("Welcome to My Personal Journey Website!");

</script>

</body>

</html>


