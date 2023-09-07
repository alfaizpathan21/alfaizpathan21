<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alfaiz- Developer portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;

        }

        body {
            background-color: rgb(0, 0, 39);
            color: white;
            font-family: 'Poppins', sans-serif;

        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 62);
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            color: rgb(160, 144, 150);
            font-size: 1.03rem;
        }

        main hr {
            border: 0;
            background: #9c97f1;
            height: 1.2px;
            margin: 60px 84px;
        }

        .left {
            font-size: 1.5rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0;

        }

        .firstSection div {
            width: 30%;
        }

        .leftSection {
            font-size: 3rem;

        }

        .rightSection img {
            width: 80%;
        }

        .purple {
            color: rgb(170, 107, 228);
        }

        .text-grey {
            color: grey;
        }

        #element {
            color: rgb(170, 107, 228);
        }

        .secondSection {
            width: 80%;
            margin: auto;
            height: 80px;

        }

        .secondSection h1 {
            font-size: 1.9rem;
        }

        .secondSection .box {
            background: white;
            width: 77vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondSection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 120px;

        }

        .image-top {
            width: 30px;
            position: relative;
            top: -49px;
            left: -15px;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px;
            font-size: 14px;

        }

        .vertical-desc {
            position: relative;
            top: 86px;
            color: grey;
            width: 150px;
            font-size: 9px;

        }

        .footer1 {
            background-color: #0c0e1a;
            width: 100%;
        height: auto;
            
        }

        .footer1 {
            display: flex;
            margin: 423px 122px;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Alfaiz Portfolio </div>
            <div class="right">
                <ul>
                    <li><a href="/">home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contacts</a></li>

                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection"> Hi, my name is
                <span class="purple">Alfaiz </span>
                <div> &</div>
                <span id="element"></span>
            </div>
            <div class="rightSection"> <img src="batman.jpg" alt="">
            </div>
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-grey">when the time comes </span>
            <h1> The gotham city need's me </h1>



            <div class="box">
                <div class="vertical">
                    <img class=" image-top" src="superman.jpg" alt="">
                    <div class="vertical-title"> Superman the holp of life </div>
                    <div class="vertical-desc"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum officia
                        eaque
                        ducimus molestiae tempore. Magni distinctio at vero enim quod. Magnam quisquam amet totam
                        blanditiis, commodi ipsa odit quo nisi.
                    </div>
                </div>
                <div class="vertical">
                    <img class=" image-top" src="superman.jpg" alt="">
                    <div class="vertical-title"> Superman the holp of life </div>
                    <div class="vertical-desc"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum officia
                        eaque
                        ducimus molestiae tempore. Magni distinctio at vero enim quod. Magnam quisquam amet totam
                        blanditiis, commodi ipsa odit quo nisi.
                    </div>
                </div>
                <div class="vertical">
                    <img class=" image-top" src="superman.jpg" alt="">
                    <div class="vertical-title"> Superman the holp of life </div>
                    <div class="vertical-desc"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum officia
                        eaque
                        ducimus molestiae tempore. Magni distinctio at vero enim quod. Magnam quisquam amet totam
                        blanditiis, commodi ipsa odit quo nisi.
                    </div>
                </div>
                <div class="vertical">
                    <img class=" image-top" src="superman.jpg" alt="">
                    <div class="vertical-title"> Superman the holp of life </div>
                    <div class="vertical-desc"> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum officia
                        eaque
                        ducimus molestiae tempore. Magni distinctio at vero enim quod. Magnam quisquam amet totam
                        blanditiis, commodi ipsa odit quo nisi.
                    </div>
                </div>

            </div>
        </section>
    </main>
    <footer>
        
    </footer>


    <!-- <footer>
        <div class="footer1">
            <div class="footer-first">
                <h3> here i will write somthing about justice immortal </h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>hello</li>
                    <li>hello</li>
                    <li>hello</li>
                    <li>hello</li>

                </ul>
            </div>
            <div class="footer-third"></div>
            <div class="footer-fourth"></div>

        </div>
    </footer> -->

    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['I am batman .', ' I need vengeance'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
