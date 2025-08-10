# Level1-Task1-OIBSIP-landing-page
Level1-Task1-A Responsive HTML &amp; CSS landing page for a fictional Alinno Hackathon 2025, featuring event details, theme, and prizes.

//landpage.html

<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="page.css">
        <title>Task1-Landing page</title>
    </head>
    <body>
        <header>
            <h1>AIinno Hackathon 2025</h1>
            <p>Innovate.Build.Impact<p>
            <p>Date : 23-August-2025 to 4-October-2025 </p>
            <div class="reg">
            <a href="">Register Now</a>
            </div>
            <hr>
        </header>
        <main>
            <h2>Description</h2>
            <p>A high-energy hackathon where innovators,developers,and creators come together to solve real-world problem</p>
            <br>
            <h2>Theme</h2>
            <p>AI,FinTech,Sustainability,Social Impact.</p>
            <br>
            <h2>Prizes</h2>
               <p>First Prize:$2,400</p>
               <p>Second Prize:$1,200</p>
                <p>Third Prize:$600</p>
            <footer>
                <hr>
                <p>Registeration closes by:15-August-2025</p>
                 <p>✉<strong>Email:</strong><a href="httpsounts.google.com/SignOutOptions?hl=en-GB&continue=https://mail.google.com/mail/&service=mail&ec=GBRAFwom">hackathon@AIinno.com</a></p>
                 &copy;2025Copyright AIinno.com<br>
            </footer>
        </main>
    </body>
</html>

//page.css

header{
    background-color: rgb(0, 217, 255);
    margin: 0px;
}
footer{
    background-color: rgb(0, 217, 255);
    margin:0px
}
.reg{
    text-align: center;
}
a{
    font-family:Georgia, 'Times New Roman', Times, serif ;
    color:rgb(0, 47, 255);
    padding: 8px 15px;
    display:inline-block;
}
a.active{
    background-color: rgb(255, 255, 255);
    font-weight: bold;
    border-radius: 5px;
}
a:hover{
    background-color: rgb(0, 170, 255);
    border-radius: 5px;
}
h1{
    text-align: center;
}
h2{
    color:rgb(0, 179, 255);
    text-align: center;
}
p{
    text-align: center;
}
footer{
    text-align: center;
}


