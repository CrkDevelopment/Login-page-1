
>Live Preview



>Html code

```html

<div class="login-container">
        <div class="section-1">
            <img src="/images/bg-img.jpg" alt="">
        </div>
        <div class="section-2">
            <div class="btn-2">
                <span>Already have an Account?</span>
                <button type="button"><a href="/login">SIGN IN</a></button>
            </div>

            <div class="login-form">
                <h1 class="title">Welcome to CrkDevelopment</h1>
                <h3 class="sub-title">Register your account</h3>
                <form action="/signup" method="post">
                    <label for="fname">Name</label>
                    <input type="text" name="fname" id="fname">

                    <label for="email">Email</label>
                    <input type="email" name="email" id="email">

                    <label for="password">Password</label>
                    <input type="password" name="password" id="password">

                    <label for="conform-password">Conform Password</label>
                    <input type="password" name="conform-password" id="conform-password">

                    <div class="btn">
                        <button type="submit">Login</button>

                        <div class="social-icons">
                            <div class="social-icon-title">Create Account with</div>
                            <div class="social-icon-link">
                                <a href="#"><img src="/images/social-icons/icons8-google-100.png" alt="google-icon"></a>
                                <a href="#"><img src="/images/social-icons/icons8-facebook-100.png" alt="facebook-icon"></a>
                                <a href="#"><img src="/images/social-icons/icons8-github-squared-100.png" alt="github-icon"></a>
                                <a href="#"><img src="/images/social-icons/icons8-linkedin-100.png" alt="linkedin-icon"></a>
                            </div>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </div>

```
>Css

```css
        body{
    margin: 0;
}

.login-container{
    margin: 0;
    width: 100%;
    height: 100vh;
    display: flex;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    cursor: default;
}

.section-1{
    width: 60%;
    height: 100%;
    background-color: cyan;
}

.section-1 img{
    width: 100%;
    height: 100%;
}

.section-2{
    position: relative;
    background: #fff;
    width: 40%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.section-2 .title{
    font-size: 20px;
}

.section-2 .sub-title{
    font-size: 14px;
    color: #979090;
}

.login-form{
    background: #fff;
    padding: 30px 20px;
    border-radius: 4px;
}

.login-form label,input{
    display: flex;
    flex-direction: column;
    padding: 6px;
}

label{
    font-size: 17px;
    font-weight: bold;
}

input{
    width: 250px;
    font-size: 13px;
    font-weight: 600;
    border: none;
    outline: none;
    border-radius: 3px;
    border: 2px solid #0679d6;
    padding: 10px;
}

.login-container .btn button{
    cursor: pointer;
    padding: 15px 50px;
    border: none;
    background: #0679d6;
    font-weight: bold;
    color: #fff;
    margin-top: 10px;
    border-radius: 10px;
}

.login-container .btn .social-icons{
    color: #979090;
    font-size: 14px;
    margin-top: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.btn .social-icons img{
    width: 28px;
    border: 3px solid #6c98bd;
    padding: 1px;
    margin-left: 8px;
    border-radius: 10px;
}

.btn .social-icons img:hover{
    border: 3px solid #0679d6;
    transform: scale(1.1);
}

.section-2 .btn-2{
    position: absolute;
    top: 20px;
    right: 20px;
}

.section-2 .btn-2 span,a{
    text-decoration: none;
    color: #979090;
    font-size: 14px;
}

.section-2 .btn-2 button{
    cursor: pointer;
    border: none;
    background: white;
    padding: 12px 30px;
    border: 1px solid #0679d6;
    border-radius: 10px;
    margin: 7px;
}

@media (max-width:792px) {
    .login-container{
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .section-1{
        display: none;
    }
    
    .section-2{
        box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px, rgba(0, 0, 0, 0.23) 0px 3px 6px;
        width: 60%;
        height: 650px;
        border-radius: 10px;
    }
}

@media (max-width:602px) {
    .section-1{
        display: none;
    }
    .section-2{
        width: 100%;
    }
}

````

<details><summary>Credits</summary>
<p>

#### </ᴄʀᴋ>
    
    MuhammedHabeeb

</p>
</details>