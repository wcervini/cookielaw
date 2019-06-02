# CookieLaw 

NOTE: this package is a fork from @Wruczek/Bootstrap-Cookie-Alert, with some changes and extras features. Thanks Wruczek for share your code.

## GDPR 
In Europe is mandatory explain the visitors of your page what is a cookie and then the visitor than  accept cookies terms & conditions. 
## npm package
    No yet

## How to use
In the example I'm use Bootstrap4, but not mandatory to use. 

#### 1. In the `head` of your document, include `cookielaw.css` **after Bootstrap**.
```html
<link rel="stylesheet" href="%your root path%/cookielaw.css">
```

#### 2. Add the GDPR compliance for cookies:
in mi case the terms are in Spanish
```html

<div class="alert text-center cookielaw">
        <p><b>El sitio web que esta visitando utiliza cookies </b> &#x1F36A; propias y de terceros para recopilar
            información que ayuda a optimizar su visita a sus páginas web. No se utilizarán las cookies para recoger
            información de carácter personal. Usted puede permitir su uso o rechazarlo. Encontrará más información en
            nuestra <a href="/politicas_cookie.html" target='_blank'>Politica de Cookies</a></p>
        <button type="button" class="btn btn-primary btn-sm acceptcookies" aria-label="Close">
            Acepto
        </button>
        <button type="button" class="btn btn-danger btn-sm noacceptcookies" aria-label="Close">
            No Acepto
        </button>
    </div>


```

#### 3. Include the JavaScript after the html markup
```html
<script src="%path yous js folder%/cookiealert.js"></script>
```
#### 4. Function
try to use this library, if accept the terms & conditioms, the user can view the page but if reject the terms and conditions are redirect to google.
