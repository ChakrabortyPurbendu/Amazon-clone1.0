# Amazon-clone1.0
Amazon clone 
.... Html code 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
     <div class="navbar">
           <div class="nav-logo border">
           <div class="logo">

              </div>
        </div>
            <div class="nav-address border">
                <p class="add-first">Deliver to</p>
                <div class="add-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-sec">India</p>
                </div>

              
           
           </div>
           <div class="nav-search">
            <select name="" class="search-select">
                <option value="">All</option>
                
            </select>
            <input type="text" placeholder="Search Amazon" class="search-input">
             <div class="search-icon">
            <i class="fa-solid fa-magnifying-glass" style="color: white;"></i>
             </div>
        </div>

        <div class="nav-signin border">
            <p><span>Hello Signin</span></p>
            <p class="nav-second">Accounts & lists</p>
        </div>

        <div class="nav-return border">
            <p><span>Returns</span></p>
            <p class="nav-second"> &Orders</p>
        </div>

        <div class="nav-cart border">
            <i class="fa-solid fa-cart-shopping"></i>
            cart
        </div>

    </div>
    <div class="panel">
        <div class="panel-all">
            <i class="fa-solid fa-bars"></i>
            All
        </div>
        <div class="panel-ops">
            <p>Today's deals</p>
            <p>Customer Service</p>
            <p>Registery</p>
            <p>Gift Cards</p>
            <p>Sell</p>
        </div>
        <div class="panel-deals">
            Shop deals in Electronics
        </div>
    </div>
    <div class="hero-section">
        <div class="hero-msg">
            You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery.    <a href="#">Click here to go to amazon.in</a>
        </div>
    </div>

    <div class="shop-section">
         <div class="box1 box">
            <div class="box-content">
                <h2>Clothes</h2>
                <div class="box-img1">

                </div>
                <p>See More</p>
            </div>
         </div>
         <div class="box2 box">
            <div class="box-content">
                <h2>Health & Personal care</h2>
                <div class="box-img2">

                </div>
                <p>See More</p>
            </div>
         </div>
         <div class="box3 box">

            <div class="box-content">
                <h2>Furniture</h2>
                <div class="box-img3">

                </div>
                <p>See More</p>
            </div>
         </div>
         <div class="box4 box">

            <div class="box-content">
                <h2>Electronics</h2>
                <div class="box-img4">

                </div>
                <p>See More</p>
            </div>
         </div>
         <div class="box4 box">

            <div class="box-content">
                <h2>Beauty Pics</h2>
                <div class="box-img5">

                </div>
                <p>See More</p>
            </div>
         </div>
         <div class="box4 box">

            <div class="box-content">
                <h2>Pet Care</h2>
                <div class="box-img6">

                </div>
                <p>See More</p>
            </div>
         </div>
         <div class="box4 box">

            <div class="box-content">
                <h2>New Arrival in Toys</h2>
                <div class="box-img7">

                </div>
                <p>See More</p>
            </div>
         </div>
         <div class="box4 box">

            <div class="box-content">
                <h2>Discover Fashion Trends</h2>
                <div class="box-img8">

                </div>
                <p>See More</p>
            </div>
         </div>
    </div>
    <footer>
        <div class="foot-pannel1">
            Back to top
        </div>
        <div class="foot-pannel2">
            <div class="foot-pannel2-ops">
                <p>Get to know us</p>
                <ul>
                    <li>Careers</li>
                    <li>Blog</li>
                    <li>About Amazon</li>
                    <li>Investor Relations</li>
                    <li>Amazon Devices</li>
                    <li>Amazon Science</li>
                </ul>
            </div>
            <div class="foot-pannel2-ops">
                <p>Make Money with Us</p>
                <ul>
                    <li>Sell products on Amazon</li>
                    <li> Sell on Amazon Business</li>
                    <li>Sell apps on Amazon</li>
                    <li>Become an affiliate</li>
                    <li>Advertise your products</li>
                    <li>Self-Publish with us</li>
                    <li>
                        host an Amazon Hub
                    </li>
                    <li>See more make more money with us</li>
                </ul>
            </div>
            <div class="foot-pannel2-ops">
                <p>Amazon Payment Products</p>
                <ul>
                    <li>Amazon Business Card</li>
                    <li>Shop with points</li>
                    <li>Reload your balance</li>
                    <li>Amazon Currency convertor</li>
                </ul>
            </div>
            <div class="foot-pannel2-ops">
                <p>Let us help you</p>
                <ul>
                    <li>Amazon and COVID-19</li>
                    <li>Your Account</li>
                    <li>Your Orders</li>
                    <li>Shipping rates and policies</li>
                    <li>Returns and replacements</li>
                    <li>Manage your content and devices</li>
                     <li>Amazon Assistant </li>
                     <li>Help</li>
                
                </ul>
            </div>
        </div>
        <div class="foot-pannel3">
            
        </div>
    </footer>
</body>
</html>

... CSS code ....

*{
    margin: 0px;
    padding: 0px;
    font-family: Arial, Helvetica, sans-serif;
    border: border-box;
}
.navbar
{
    height: 60px;
    background-color: #0f1111;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-evenly;



}
.nav-logo
{
    height: 50px;
    width: 100px;
}
.logo
{
    background-image: url('amazon_logo.png');
    height: 50px;
    width: 100%;
    background-size: cover;


}
.border
{
    border: 2px solid transparent;

}
.border:hover
{
    border: 1.5px solid white;
}
.add-first
{
    color: #cccccc;
    font-size: 0.85rem;
    margin-left: 15px;
}
.add-sec
{
    color: #cccccc;
    margin-left: 3px;
}
.icon
{
    
    background-color: white;
    border: 2px solid white;
}
.add-icon
{
    display: flex;
    align-items: center;
}
.nav-search
{
    display: flex;
    justify-content: space-evenly;
    /* background-color: pink; */
    width: 620px;
    height: 40px;
    border-radius: 4px;

}
.search-select
{
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px ;
    border-top-right-radius: 4px;
    border: none;

}
.search-input
{
    width: 500px;
    font-size: 1rem;
    border: none;

}
.search-icon
{
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: rgb(224, 178, 27);
    border-top-right-radius: 4px ;
    border-bottom-right-radius: 4px;

}
.nav-search:hover
{
    border: 2px solid orange;
}
span
{
    font-size: 0.7rem;
    color: #cccccc;
}
.nav-second
{
    font-size: 0.85rem;
    font-weight: 700;
    color: #cccccc;
}
.nav-return
{
    font-size: 0.85rem;
    font-weight: 700;
    color: #cccccc;
}
.nav-cart i
{
   font-size: 35px;
   height: 30px;
   color: #cccccc;

}
.nav-cart
{
    font-size: 0.85rem;
    font-weight: 700;
    color: #cccccc;
}
.panel
{
    height: 40px;
    background-color: #0f1111;
    display: flex;
    color: #f3f3f3;
    justify-content: space-evenly;


}
.panel-ops
{
    width: 70%;
    font-size: 0.85rem;
}
.panel-ops p
{
    display: inline;
    color: #f3f3f3;
    margin-left: 15px;

}
.panel-deals
{
    font-size: 0.9rem;
    font-weight: 700;
}
.hero-section
{
   background-image: url('hero_image .jpg');
   height: 380px;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: flex-end;
  
    
}
.hero-msg
{
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.85rem;
    position: relative;
    width: 90%;
    margin-bottom: 25px ;
}
.hero-msg a
{
    color: #007185;

}
.shop-section
{
    display: flex;
    justify-content: space-evenly;
    background-color: grey;
    flex-wrap: wrap;

}
.box
{
    /* border: 2px solid black; */
    height: 400px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 15px;


}
.box-img1
{
    height: 300px;
    background-image: url('box1_image.jpg');
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-img2
{
    height: 300px;
    background-image: url('box2_image.jpg');
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-img3
{
    height: 300px;
    background-image: url('box3_image.jpg');
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-img4
{
    height: 300px;
    background-image: url('box4_image.jpg');
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-img5
{
    height: 300px;
    background-image: url('box5_image.jpg');
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-img6
{
    height: 300px;
    background-image: url('box6_image.jpg');
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-img7
{
    height: 300px;
    background-image: url('box7_image.jpg');
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-img8
{
    height: 300px;
    background-image: url('box8_image.jpg');
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}
.box-content
{
    margin-left: 1rem;
    margin-right: 1rem;
}
.box-content p
{
    color: #007185;
}
footer
{
    margin-top: 15px;
}
.foot-pannel1
{
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
    
}
.foot-pannel2
{
    background-color: #222f3d;
    color: white;
    height: 400px;
    display: flex;
    justify-content: space-evenly;
}
 ul li
{
    margin: 15px;
    list-style: none;
}
.foot-pannel2-ops
{
    margin: 15px;
}

