/**
 * SeAT login page layout
 */
@media all {
    html, body {
        height: auto;
    }

    .login-page, .register.body {
        color: rgb(255,255,255);
        background-image: url(https://web.ccpgamescdn.com/aws/eveonline/sso/background.jpg);
        background-position: center center;
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
    }

    .login-box, .register-box {
        width: 360px;
        margin: 0;
        position: absolute;
        top: 50%;
        left: 50%;
        background: rgba(48,48,48,.8);
        transform: translate(-50%, -50%);
        border: 5px solid #ecf0f1;
        border-radius: 40px;
        box-shadow: 0 1px 1px rgba(0,0,0,0.05);
    }

    .login-logo, .register-logo {
        font-size: 35px;
        text-align: center;
        margin-bottom: 25px;
        font-weight: 300;
        margin-top: 50px;
    }

    .login-logo::before, .register-logo::before {
        content: " ";
        display: block;
        width: 128px;
        height:128px;
        margin: 0 auto;
        background-image: url(https://images.evetech.net/corporations/98482334/logo?size=128);
        border-radius: 50%;
        margin-bottom: 50px;
    }

    .login-box-body, .register-box-body {
        background: transparent;
        padding: 20px;
        border-top: 0;
        color: inherit;
    }
}
