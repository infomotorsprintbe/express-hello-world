




<!DOCTYPE html>
<!--[if lt IE 7]><html class="no-js lt-ie9 lt-ie8 lt-ie7" lang="en"><![endif]-->
<!--[if IE 7]><html class="no-js lt-ie9 lt-ie8" lang="en"><![endif]-->
<!--[if IE 8]><html class="no-js lt-ie9" lang="en"><![endif]-->
<!--[if gt IE 8]><!-->
<html class="no-js" lang="en"> <!--<![endif]-->




<head>
    
    <title>Telenet Webmail</title>

    

<title>Telenet: Meld je aan</title>
<meta content="IE=edge" http-equiv="X-UA-Compatible">
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
<meta name="description" content="">


    
    
        <script type="text/javascript" src="https://login.prd.telenet.be/openid/ruxitagentjs_ICA27NVfghjqrux_10283240117152214.js" data-dtconfig="app=bd04f5bd154f7157|ssc=1|cssm=n|featureHash=ICA27NVfghjqrux|vcv=2|rdnt=1|uxrgce=1|bp=3|cuc=wxbgggj9|mel=100000|md=mdcc1=a#login-form ^rb div.g-recaptcha,mdcc2=a#error|ssv=4|lastModification=1708171459084|tp=500,50,0,1|agentUri=/openid/ruxitagentjs_ICA27NVfghjqrux_10283240117152214.js|reportUrl=/openid/rb_58b59a93-831f-4aa5-913a-91bb5ca1f41c|rid=RID_-110783935|rpid=-1709908532|domain=telenet.be"></script><link rel="shortcut icon" href="https://static.telenet.be/assets/favicon/favicon.ico" type="image/x-icon"/>
    


<link rel="stylesheet" href="https://login.prd.telenet.be/openid/css/vendor/normalize.min.css">
<link rel="stylesheet" href="https://static.telenet.be/oauth2/css/main.css">
<link rel="stylesheet" href="https://login.prd.telenet.be/openid/css/login.css?v=2.1">
<link rel="stylesheet" href="https://login.prd.telenet.be/openid/css/login-sales-flow.css" type="text/css">
<link href="https://login.prd.telenet.be/openid/css/login-select-account.css" rel="stylesheet" type="text/css">

<!-- Adobe analytics -->
<script src="https://login.prd.telenet.be/openid/js/vendor/jquery-1.9.1.min.js"></script>
<script src="https://static.telenet.be/oauth2/js/vendor/jquery-ui-1.10.3.custom.min.js"></script>

<script type="text/javascript">
    function hideHtmlElement(id) {
        document.getElementById(id).style.display = "none";
    }

    function showHtmlElement(id) {
        document.getElementById(id).style.display = "block";
    }

    function showPanel(id) {
        hideHtmlElement("forgotLogin");
        hideHtmlElement("showLogin");
        showHtmlElement(id);
    }

    function getTelenetPasswordForgottenUrl(){
        return "https://www2.telenet.be/nl/profiel/wachtwoord-vergeten?"
            + "&login="
            + document.getElementById('j_username').value
            + "#/loginredirecturl="
            + "https%253A%252F%252Flogin.prd.telenet.be%252Fopenid%252Foauth%252Fauthorize%253Fclaims%253D%25257B%252522id_token%252522%253A%25257B%252522http%253A%252F%252Ftelenet.be%252Fclaims%252Flicenses%252522%253Anull%252C%252522http%253A%252F%252Ftelenet.be%252Fclaims%252Fmailbox%252522%253Anull%25257D%25257D%2526response_type%253Dcode%2526state%253Df2d776bc-cb4f-4cdc-a055-5c33f3c5fae8%2526nonce%253Df93ba735-9f38-4726-a308-b2b78e8bbbca%2526client_id%253Dwebmail";
    }

    function getLoginForgottenUrl(){
        return "https://www2.telenet.be"
            + '/nl/klantenservice/telenet-login-vergeten?intcmp=openid_login_forgotten_webmail';
    }

    function getBasePasswordForgottenUrl(){
        return "https://www.prd.base.be/nl/create-profile?flow=recoverpwd"
            + "&login="
            + document.getElementById('j_username_input').value;
    }

    function togglePassword() {
        var password = document.getElementById('j_password');
        if (password.type === 'text') {
            togglePasswordIcon('show-hide', 'hide-show');
            password.type = 'password';
        } else {
            togglePasswordIcon('hide-show', 'show-hide');
            password.type = 'text';
        }
    }

    function togglePasswordIcon(removeClass, addClass) {
        document.getElementById('passwordEye').classList.remove(removeClass);
        document.getElementById('passwordEye').classList.add(addClass);
    }

    function showEyeIcon() {
        var password = document.getElementById('j_password');
        if (password.value.trim() !== '') {
            showElement('passwordEye');
        } else {
            hideElement('passwordEye');
        }
    }

    function showElement(id) {
        document.getElementById(id).style.display = 'block';
    }

    function hideElement(id) {
        document.getElementById(id).style.display = 'none';
    }

    function toggleLanguage() {
        var languageMenu = document.getElementById('language-menu');
        if (languageMenu.classList.contains('open')) {
            document.getElementById('language-menu').classList.remove('open');
            document.getElementById('language-arrow').classList.remove('active');
        } else {
            document.getElementById('language-menu').classList.add('open');
            document.getElementById('language-arrow').classList.add('active');
        }
    }
</script>

<!--[if lt IE 9]>
<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->








    <link href="https://login.prd.telenet.be/openid/css/common/icons.css" rel="stylesheet" type="text/css">
    <link href="https://login.prd.telenet.be/openid/css/telenet/telenet.css" rel="stylesheet" type="text/css">
</head>

<body>

<section id="LoginForm">
    <span id="showBackgroundForStatic" style="display: none">true</span>
    <div class="openid-login-page m--n justify-content-center background__image--full-size">
        <div class="openid-login-page__container align-items-center">
            <div class="m--n openid-login-page__container--inner">
                
                <div class="p--n mb--l openid-login-page__container--header">
                    <div class="m--n openid-login-page__container--header-logo">
                        <div class="p--n cmp cmp-logo">
                            <span class="logo ">
                                <img class="" src="https://login.prd.telenet.be/openid/img/telenet/logo-telenet.svg" alt="Telenet">
                            </span>
                            <span class="openid-login-page__header-site-name fit-content">
                                Telenet Webmail
                            </span>
                            <span id="languageForStatic" style="display: none">nl</span>
                        </div>
                        
                            <div class="language-selector clearfix" onclick="toggleLanguage()" onmouseover="toggleLanguage()" onmouseleave="toggleLanguage()">
    <div class="language-selector__selected">
        <div class="lang-selected">
            <span>nl</span>
            <span id="language-arrow" class="arrow"></span>
        </div>
    </div>
    <div id="language-menu" class="language-menu" onmouseover="toggleLanguage()">
        <ul>
            <span id="languageForStatic" style="display: none">nl</span>
            <!-- IT-4522 The design team uses languageForStatic to display text dynamically-->
            
            
            <span>
                
                    
                        <li class="active"><a class="cur-default" href="javascript:void(0)" tabindex="-1">NL</a></li>
                        <li><a href="?lang=fr&error=" tabindex="-1">FR</a></li>
                        <li><a href="?lang=en&error=" tabindex="-1">EN</a></li>
                    
                    
                    
                
            </span>
        </ul>
    </div>
</div>

                        
                    </div>
                </div>

                <!-- message handling -->
                <div class="contentContainer" id="loginSection">

                    <div id="error">
                        

    
    
    
    
    
    





                    </div>
                    
                    
                        <div class="display-flex openid-login-page__container-details">
                            <div class="openid-login-page__container--form-login-section p--n width-260">
                                <form id="login-form" name="loginForm" action="/openid/login.do" method="post" class="p--n m--n login-form">
                                    <div class="form-group mb--m position--relative">
                                        <label for="j_username">
                                            
                                                
                                                
                                                    Je e-mailadres
                                                
                                            
                                        </label>
                                        
                                            <a href="#" onclick="window.open(getLoginForgottenUrl());  return false;" target="_blank" tabindex="-1" class="ml--xs link link--unstyled" tabindex="-1">
                                                Vergeten?
                                            </a>
                                        
                                        <div data-cs-mask class="form__input-container ">
                                            <input type="text" class="form__input "
                                                       name="j_username"
                                                       id="j_username"
                                                       autcomplete="off"
                                                       tabindex="1"
                                                       autofocus
                                            
                                                   placeholder="e-mail@telenet.be"
                                            
                                            >
                                        </div>
                                    </div>
                                    <div class="form-group mb--m position--relative">
                                        <label for="j_password">
                                            Wachtwoord
                                        </label>
                                        <a onclick="window.open(getTelenetPasswordForgottenUrl()); return false;" href="#" target="_blank"
                                           class="ml--xs link link--unstyled" tabindex="-1">
                                            Vergeten?
                                        </a>
                                        <div data-cs-mask class="form__input-container display-flex">
                                            <input class="form__input "
                                                       type="password" name="j_password"
                                                       id="j_password" onkeyup="showEyeIcon();"
                                                       autocomplete="off"
                                                       tabindex="2"
                                                       placeholder="Hoofdlettergevoelig">
                                            <div class="hide-show" style="display: none;" id="passwordEye"
                                                 onclick="togglePassword();"></div>
                                        </div>
                                    </div>
                                    
                                    <div class="p--n">
                                        
                                            
                                                <div>
                                                    <div class="form__checkbox">
                                                        <input type="checkbox" class="form__checkbox__input" name="rememberme"
                                                               id="rememberme"
                                                               value="true"
                                                                tabindex="3">
                                                        <label class="form__checkbox__label" for="rememberme">&nbsp;</label>
                                                    </div>
                                                    <label class="label" for="rememberme">Aangemeld blijven</label>
                                                </div>
                                            
                                            
                                        
                                    </div>

                                    <div class="form-group">
                                        
                                            
                                            
                                                <button type="submit"
                                                        tabindex="4"
                                                        class="button button--primary login button--fullwidth" name="Login.Submit"
                                                        id="login_button">Aanmelden</button>
                                            
                                        
                                    </div>
                                    
                                        
                                        
                                            
                                                <div class="text-align--center">
                                                    <a class="link link--unstyled no-login-link" href="https://www2.telenet.be/residential/nl/create-profile/?flow=selfRegistration#/loginredirecturl=https%253A%252F%252Flogin.prd.telenet.be%252Fopenid%252Foauth%252Fauthorize%253Fclaims%253D%25257B%252522id_token%252522%253A%25257B%252522http%253A%252F%252Ftelenet.be%252Fclaims%252Flicenses%252522%253Anull%252C%252522http%253A%252F%252Ftelenet.be%252Fclaims%252Fmailbox%252522%253Anull%25257D%25257D%2526response_type%253Dcode%2526state%253Df2d776bc-cb4f-4cdc-a055-5c33f3c5fae8%2526nonce%253Df93ba735-9f38-4726-a308-b2b78e8bbbca%2526client_id%253Dwebmail" target="_blank"
                                                       tabindex="-1">Nog geen login? Maak er één aan.</a>
                                                </div>
                                            
                                        
                                    
                                </form>
                            </div>

                            
                        </div>
                    
                </div>
                
            </div>
        </div>
    </div>

</section>
<div class="bgContainer"></div>

<div class="overlayer" id="cookie-dialog-itsme">
    <div class="overlayer-mask opacity--mini-transparency"></div>
    <div class="overlay__section">
        <div class="overlay__section__content p--s">
            <div class="overlay__section__content__description ">
                
            </div>
            <div class="overlay__section__content__action justify-content-center mb--s">
                <button onclick='closeInformCookieDialog("itsme"); return false;' class="button button--secondary">Nee</button>
                <button onclick='confirmInformCookieDialog("itsme"); return false;' class="button button--primary">Ja</button>
            </div>
        </div>
    </div>
</div>
<div class="overlayer" id="cookie-dialog-facebook">
    <div class="overlayer-mask opacity--mini-transparency"></div>
    <div class="overlay__section">
        <div class="overlay__section__content p--s">
            <div class="overlay__section__content__description ">
                
            </div>
            <div class="overlay__section__content__action justify-content-center mb--s">
                <button onclick='closeInformCookieDialog("facebook"); return false;' class="button button--secondary">Nee</button>
                <button onclick='confirmInformCookieDialog("facebook"); return false;' class="button button--primary">Ja</button>
            </div>
        </div>
    </div>
</div>

<div class="overlayer" id="cookie-dialog-google">
    <div class="overlayer-mask opacity--mini-transparency"></div>
    <div class="overlay__section">
        <div class="overlay__section__content p--s">
            <div class="overlay__section__content__description ">
                
            </div>
            <div class="overlay__section__content__action justify-content-center mb--s">
                <button onclick='closeInformCookieDialog("google"); return false;' class="button button--secondary">Nee</button>
                <button onclick='confirmInformCookieDialog("google"); return false;' class="button button--primary">Ja</button>
            </div>
        </div>
    </div>
</div>

<script src="https://login.prd.telenet.be/openid/js/social/social.js"></script>
<input type="hidden" id="oauth2-brand" value="TELENET"/>
<script src="https://login.prd.telenet.be/openid/js/vendor/modernizr-2.6.2-respond-1.1.0.min.js"></script>

<!--[if lt IE 9]>!
<script type="text/javascript" src="/openid/js/vendor/jquery.backgroundSize.js"></script>
<![endif]-->

<span id="client_id" style="display: none">webmail</span>
<span id="stylehint" style="display: none"></span>

<script src="https://static.telenet.be/oauth2/js/main.js"></script>



    
        <script src="https://static.telenet.be/oauth2/js/items_centered_webmail.js"></script>
        <script>if(typeof(window.data) === 'undefined') { document.write('<script src="https://static.telenet.be/oauth2/js/items_centered.js">\x3C/script>');}</script>
    
    


<script type="text/javascript">
    $('form').submit(function () {
        if('webmail' !== 'ocapi_base') {
            $('input:submit').attr("disabled", true);
            $(this).find('button:submit').attr("disabled", true);
        }
    });
</script>



    
        
        
        
            <script src="https://login.prd.telenet.be/openid/js/analytics/3ce8236b487d/f8574738a869/launch-dca0d353fb89.min.js"></script>
        
    

    <script src="https://login.prd.telenet.be/openid/js/analytics/udl.min.js"></script>
    <script src="https://login.prd.telenet.be/openid/js/analytics/analytics.js"></script>


<!-- <sessionid>29d44cda-6233-4954-bdd9-092f0d516e04</sessionid> -->
<!-- errorCode: , errorMessage:  -->
</body>
</html>
