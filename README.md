# Ex.05 Book Front Cover Page Design
## Date:24-05-2026

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Game Development Book Cover</title>

<style>

@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;700&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:linear-gradient(135deg,#dbeafe,#fbcfe8);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:30px;
    font-family:'Montserrat',sans-serif;
}

/* BOOK COVER */

.book-cover{
    width:560px;
    background:white;
    border-radius:30px;
    overflow:hidden;
    box-shadow:0 15px 40px rgba(0,0,0,0.15);
}

/* HEADER */

.top-section{
    background:linear-gradient(135deg,#38bdf8,#ec4899);
    padding:45px 35px;
    color:white;
    position:relative;
}

.top-section::after{
    content:'';
    position:absolute;
    bottom:-40px;
    right:-40px;
    width:160px;
    height:160px;
    background:rgba(255,255,255,0.15);
    border-radius:50%;
}

.top-section h1{
    font-size:34px;
    font-weight:700;
    margin-bottom:10px;
    letter-spacing:1px;
}

.top-section p{
    font-size:15px;
    opacity:0.95;
}

/* CONTENT */

.content{
    padding:40px 35px;
}

.subject-tag{
    display:inline-block;
    background:#fce7f3;
    color:#db2777;
    padding:10px 18px;
    border-radius:30px;
    font-size:14px;
    font-weight:600;
    margin-bottom:25px;
}

.description{
    color:#374151;
    line-height:1.9;
    font-size:15px;
    text-align:justify;
    margin-bottom:30px;
}

/* QUOTE */

.quote-box{
    background:#eff6ff;
    border-left:6px solid #38bdf8;
    padding:22px;
    border-radius:18px;
    margin-bottom:35px;
}

.quote-box p{
    text-align:center;
    font-style:italic;
    color:#0f172a;
    line-height:1.8;
    font-size:15px;
}

/* AUTHOR */

.author-card{
    display:flex;
    gap:20px;
    align-items:center;
    background:#f9fafb;
    border-radius:22px;
    padding:20px;
    border:1px solid #e5e7eb;
    margin-bottom:35px;
}

.author-img{
    width:100px;
    height:120px;
    object-fit:cover;
    border-radius:18px;
    border:4px solid #ec4899;
}

.author-info h2{
    color:#0284c7;
    margin-bottom:10px;
    font-size:24px;
}

.author-info p{
    color:#4b5563;
    line-height:1.8;
    font-size:14px;
    text-align:justify;
}

/* FOOTER */

.footer{
    background:linear-gradient(135deg,#38bdf8,#ec4899);
    padding:20px 35px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    color:white;
}

.publisher h3{
    font-size:20px;
    margin-bottom:5px;
}

.publisher p{
    font-size:13px;
    opacity:0.9;
}

.price{
    background:white;
    color:#ec4899;
    padding:10px 22px;
    border-radius:40px;
    font-size:20px;
    font-weight:700;
}

</style>
</head>

<body>

<div class="book-cover">

    <!-- HEADER -->

    <div class="top-section">

        <h1>ABOUT THE BOOK</h1>


    </div>

    <!-- CONTENT -->

    <div class="content">

        <div class="subject-tag">

            Modern Game Design & Development

        </div>

        <p class="description">

            This book introduces readers to the creative field of
            Game Development, where programming, storytelling,
            animation, graphics, and innovation come together to
            build immersive gaming experiences. Learn about game
            engines, character creation, level design, sound effects,
            interactive gameplay, and modern development tools used
            in today’s gaming industry.

        </p>

        <!-- QUOTE -->

        <div class="quote-box">

            <p>

                “Games are not just played —
                they are experiences designed with imagination.”

            </p>

        </div>

        <!-- AUTHOR -->

        <div class="author-card">

            <img src="author.jpeg" class="author-img" alt="Author">

            <div class="author-info">

                <h2>KOUSHIK</h2>

                <p>

                    Koushik is a passionate developer and creative
                    designer interested in game technology, digital
                    experiences, and innovative software solutions.
                    He enjoys inspiring young creators to explore
                    the future of interactive entertainment.

                </p>

            </div>

        </div>

    </div>

    <!-- FOOTER -->

    <div class="footer">

        <div class="publisher">

            <h3>SEC Publishers</h3>

            <p>Gaming Edition • 2026</p>

        </div>

        <div class="price">

            ₹264

        </div>

    </div>

</div>

</body>
</html>
```


## OUTPUT:
<img width="801" height="911" alt="{D5399A2C-9C51-4A8F-B5C2-5B8E2E3EF00A}" src="https://github.com/user-attachments/assets/375407fd-b8fd-47bf-bba6-2f10dcc256a4" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
