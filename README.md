# javaassignment5
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

    <form>
        <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <br><br>
        </div>
        <div class="mb-3">
            <label for="exampleInputPassword1" class="form-label">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
        </div>
        <br><br>


        <button type="submit" class="btn btn-primary">Submit</button>
    </form>
    <!-- <script>


        let a = window.location.search;
        console.log(a)
        let b = new URLSearchParams(a)
         let res = b.get('useremail');
        if (res === null) {
            loginbtn.innerHTML = "login"
        }
        else {


            loginbtn.innerHTML = res
        }


    </script> -->

</body>

</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>navbar</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonym">
</head>

<body>

    <div class="container">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Navbar</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class='nav-link' href='/movies.html' id='Moviesbtn'>movies</a>
                        </li>
                    </ul>
                    <ul class="navbar-nav mb-2 mb-lg-0">
                        <li class="nav-item">


                        <li class="nav-item">
                            <a class='nav-link' href='/login.html' id='loginbtn'>login</a>
                            <a class='nav-link' href='/sign up.html' id='signupbtn'>Signup</a>
                        </li>


                    </ul>
                </div>
            </div>
        </nav>
        <div class="body1">
            <div class="leftdiv">
                <h2>KlassyCafe</h2>
                <p>THE BEST EXPERIENCE</p>
                <P>Since 1990</P>


            </div>
            <div class="rightdiv">
                <img src="chair.jpg" alt="" class="img1">
            </div>
        </div>


    </div>


    <script>


        let a = window.location.search;
        console.log(a)
        let b = new URLSearchParams(a)
        let res = b.get('useremail');
        if (res === null) {
            loginbtn.innerHTML = "login"
        }
        else {


            loginbtn.innerHTML = login
        }


    </script>





















    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous">
        </script>
</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>movies</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonym">
    <link rel="style.css" href="style.css">
    <style>
        .cardscontainer {
            display: flex;
            align-items: center;
            grid-row: 20px;
            grid-column: auto;
            margin: 40px;
        }

        .leftdiv {
            display: flex;
            background-color: aqua;
            margin: 40px;
            column-gap: 20px;
            grid-row: auto;
        }
    </style>
</head>

<body>

    <div class="cardscontainer">
        <div class="div5">
            <div class="card" style="width: 18rem;">
                <img src="imeges/premium_photo-1677094766815-e0fe790e364a.avif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's
                        content.</p>
                    <a href="#" class="btn btn-primary">Go somewhere</a>
                </div>
            </div>

            <div class="card" style="width: 18rem;">
                <img src="imeges/premium_photo-1677094766815-e0fe790e364a.avif" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's
                        content.</p>
                    <a href="#" class="btn btn-primary">Go somewhere</a>
                </div>

                <div class="card" style="width: 18rem;">
                    <img src="imeges/premium_photo-1677094766815-e0fe790e364a.avif" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of
                            the
                            card's
                            content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
        </div>

        <div class="leftdiv">
            <div class="card" style="width: 18rem;">
                <img src="imeges/istockphoto-1297349747-612x612.webp" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the
                        bulk
                        of the
                        card's
                        content.</p>
                    <a href="#" class="btn btn-primary">Go somewhere</a>
                </div>

                <div class="card" style="width: 18rem;">
                    <img src="imeges/istockphoto-1297349747-612x612.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up
                            the
                            bulk of the
                            card's
                            content.</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>

                    <div class="card" style="width: 18rem;">
                        <img src="imeges/istockphoto-1297349747-612x612.webp" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make
                                up
                                the bulk of the
                                card's
                                content.</p>
                            <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>





        <script src="script.js"></script>

        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
            integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous">
            </script>

</body>

</html>
