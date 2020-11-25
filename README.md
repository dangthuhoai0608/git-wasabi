# git-wasabi

nhận xét

            margin: 0;
            padding: 0;
            outline: none;
            font-family: 'Roboto', sans-serif;
            list-style: none;
            text-decoration: none;
        }
        
        .logo img {
            width: 100%;
            height: 200px;
        }
        /* Menu */
        
        .menu {
            margin-top: 30px;
            margin-bottom: 20px;
            text-align: center;
            height: 40px;
            width: 100%;
        }
        
        .menu ul li {
            display: inline-block;
            padding: 20px 100px;
            text-transform: uppercase;
            text-align: center;
            color: black;
        }
        /*slice*/
        
        .slice {
            width: 100%;
            margin-top: 30px;
            position: relative;
        }
        
        .slice .left {
            width: 50%;
            height: 300px;
            float: left;
        }
        
        .slice .right {
            width: 50%;
            height: 300px;
            float: left;
        }
        
        .slice .left img {
            width: 100%;
            height: 300px;
        }
        
        .slice .right img {
            width: 100%;
            height: 300px;
        }
        /*slice_below*/
        
        .slice_below {
            width: 100%;
            height: 300px;
        }
        
        .slice_below img {
            width: 100%;
            height: 300px;
            float: left;
        }
        
        .slice h1 i big {
            position: absolute;
            top: 90px;
            left: 20px;
            text-align: center;
            color: white;
            width: 100%;
        }
        
        .box-title h2 {
            text-align: center;
            margin: 3em 0;
            color: #2c2e53;
            text-transform: uppercase;
            font-weight: 900;
            position: relative;
        }
        
        .box-title h2:after {
            content: "";
            position: absolute;
            top: 102%;
            left: 50%;
            width: 5em;
            height: 4px;
            background: #bd945f;
            transform: translateX(-50%);
        }
        
        .product {
            padding: 2em 1em;
            margin-top: -5em;
            height: 1000px;
            width: 400px;
        }
        
        .product img {
            height: 400px;
            width: 400px;
            float: left;
        }
        
        .product-left {
            height: 100px;
            width: 400px;
            float: left;
            background: rgb(243, 241, 241);
        }
        
        .product p {
            margin-top: .3em;
        }
        
        .product .name {
            color: #2c2e53;
            font-weight: 800;
        }
        
        .product .price {
            font-weight: 600;
        }
        
        .product .desc {
            color: #999;
        }
        
        .product i {
            color: #eed70c;
        }
        
        .list-product {
            background: rgb(145, 209, 238);
            padding: 9em;
            display: flex;
            height: 400px;
            width: 1240px;
        }
        /*buttom*/
        
        .buttom {
            background: rgb(145, 209, 238);
            padding: 9em;
            display: flex;
            height: 400px;
            width: 1240px;
        }
        
        .menu-2 {
            background: rgb(145, 209, 238);
            margin-bottom: 20px;
            text-align: center;
            height: 250px;
            width: 100%;
        }
        
        .menu-2 ul li {
            margin-top: 20px;
            width: 200px;
            background: rgb(145, 209, 238);
            display: inline-block;
            padding: 20px 100px;
            text-transform: uppercase;
            text-align: center;
            color: black;
            margin-left: 15px;
            margin-bottom: 5px;
        }
        
        .menu-2 p {
            margin-top: 2px;
        }
        
        .item {
            width: 1270px;
            height: 200px;
            background: white;
            display: flex;
            margin-left: 160px;
        }
        
        .menu-3 {
            background: rgb(145, 209, 238);
            margin-bottom: 20px;
            text-align: center;
            height: 150px;
            width: 100%;
        }
        
        .menu-3 button {
            margin-top: 30px;
            padding: 1em 2em;
            border: none;
            background: #bd945f;
            color: #fff;
            margin-bottom: 5px;
        }
        
        .trending {
            background: rgb(145, 209, 238);
            height: 70px;
        }
        
        .banner-top {
            width: 1240px;
            height: 200px;
        }
        
        
        
        
        
        
        
        
        
        
        <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>du an</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css" integrity="sha512-+4zCK9k+qNFUR5X+cKL9EIR+ZOhtIloNl9GIKS57V1MyNsYpYcUrUeQc9vNfzsWfV28IaLL3i96P9sdNyeRssA==" crossorigin="anonymous" />
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="logo">
        <img src="./images/anh2.png" alt="">
    </div>


    <div class="menu">
        <ul>
            <li><b><a href="#">ホームページ</a></b></li>
            <li><b><a href="#">アドバイザリー</a></b></li>
            <li><b><a href="#">ニュース</a></b></li>
            <li><b><a href="#">ホットスポット</a></b></li>
        </ul>
    </div>


    <div class="slice">
        <div class="right">
            <img src="./images/banner1.png" alt="">
        </div>
        <div>
            <h1><i><big>信頼はクロスブランディングを生み出す
					<p>ユーザーをモットーに、ぜひお越しください</p>
				</big></i></h1>
        </div>
        <div class="left">
            <img src="./images/banner2.png" alt="">
        </div>
    </div>


    <div class="slice_below">
        <img src="./images/anh3.png" alt="">
    </div>


    <div class="trending">
        <div class="box-title">
            <h2> 信頼はクロスブランディングを生み出す
                <p>ユーザーをモットーに、ぜひお越しください</p>
            </h2>
        </div>
    </div>

    <div class="buttom">

        <div class="product">
            <div class="img">
                <img src="./images/anh4.png" alt="">
            </div>
            <div class="product-left">
                <p class="name text-uppercase">20/02/2002</p>
                <p>信頼はクロスブラン</p>
                <p>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </p>
            </div>
        </div>

        <div class="product">
            <div class="img">
                <img src="./images/anh4.png" alt="">
            </div>
            <div class="product-left">
                <p class="name text-uppercase"> 20/02/2002 </p>
                <p>信頼はクロスブラン</p>
                <p>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </p>
            </div>
        </div>

        <div class="product">
            <div class="img">
                <img src="./images/anh4.png" alt="">
            </div>

            <div class="product-left">
                <p class="name text-uppercase">20/02/2020</p>
                <p>信頼はクロスブラン</p>
                <p>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </p>
            </div>
        </div>
    </div>


    <div class="list-product d-flex">

        <div class="product">
            <div class="img">
                <img src="./images/anh4.png" alt="">
            </div>
            <div class="product-left">
                <p class="name text-uppercase">20/02/2002</p>
                <p>信頼はクロスブラン</p>
                <p>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </p>
            </div>
        </div>

        <div class="product">
            <div class="img">
                <img src="./images/anh4.png" alt="">
            </div>
            <div class="product-left">
                <p class="name text-uppercase"> 20/02/2002 </p>
                <p>信頼はクロスブラン</p>
                <p>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </p>
            </div>
        </div>

        <div class="product">
            <div class="img">
                <img src="./images/anh4.png" alt="">
            </div>

            <div class="product-left">
                <p class="name text-uppercase">20/02/2020</p>
                <p>信頼はクロスブラン</p>
                <p>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </p>
            </div>
        </div>
    </div>

    <div class="menu-2">
        <div class="item">
            <ul>
                <li><b><a href="#">ホームページ</a></b></li>
                <li><b><a href="#">アドバイザリー</a></b></li>
                <li><b><a href="#">ニュース</a></b></li>
                <p>
                    <li><b><a href="#">ニュース</a></b></li>
                    <li><b><a href="#">ホットスポット</a></b></li>
                    <li><b><a href="#">アドバイザリー</a></b></li>
                </p>
            </ul>
        </div>

        <div class="menu-3">
            <button class="btn text-uppercase">MORE</button>
        </div>
    </div>

    <div class="banner">
        <div class="banner-top">
            <img src="./images/banner4.plg.jpg" alt="">
        </div>
        <div class="banner-2"></div>
    </div>

</body>

</html>
