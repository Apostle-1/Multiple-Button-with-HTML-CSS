# Multiple-Button-with-HTML-CSS
CSS helps to style our HTML



<style>
    .request-button{
        background-color: black;
        color: white;
        height: 45px;
        width: 100px;
        border: none;
        cursor: pointer;
        transition: opacity 10s;
        
    }

    .request-button:hover{
        background-color:red;
    }

    .request-button:active{
       background-color:yellow;
    }

    .request-button{
        opacity: 0.8s;
    }

    .cart-button{
        background-color: yellow;
        height: 40px;
        width: 150px;
        border: none;
        border-radius: 20px;
        margin-left: 20px;
        cursor: pointer;
        font-weight: bold;
    }

    .sign-button{
        margin-left: 20px;
        height: 40px;
        width: 100;
        background-color: rgb(30, 193, 30);
        color: white;
        border: none;
        border-radius: 10px;
        font-size: 17px;
        box-shadow:10px 10px 10px rgb(255, 0, 255);
    }

    .get-button{
        background-color: rgb(97, 23, 166);
        color: white;
        height: 40px;
        width: 100px;
        border: none;
        border-radius: 5px;
        font-weight: bold;
    }

    .download-button{
        height: 40px;
        width: 100px;
        border: none;
        border-radius: 5px;
        background-color: rgb(196, 196, 174);
        color: white;
        margin-left: 5px;
        cursor: pointer;
    }
    
    .apply-button{
        background-color: rgb(85, 85, 247);
        color: white;
        height: 35px;
        width: 200px;
        border: none;
        border-radius: 20px;
        margin-left: 20px;
        font-weight: bold;
    }

    .save-button{
        background-color: white;
        color: blue;
        height: 35px;
        width: 55px;
        border-radius: 10px;
        border-color: blue;
        
    }
</style>



<a style="line-height:100px ; color: red;
"><h1>OLOTU MATTHEW</h1></a>
<button class="request-button">Request Now</button>
<button class="cart-button"> Add to Cart</button>
<button class="sign-button">Sign up</button>
<p><button class="get-button"> Get started</button>
<button class="download-button">Download</button>
<button class="apply-button">Apply on company website</button>
<button class="save-button">Save</button></p>

