Créer un formulaire contenant un champ nom, un champ mail et un champ age.

Si les champs ne correspondent pas à une regex, 
afficher un message d'erreur en rouge sous le champs dès que l'on entre une valeur.

Email  https://www.emailregex.com
-------------------------------------------------------------------------------------
> Just copy and paste the email regex below for the language of your choice. 
> Feeling hardcore (or crazy, you decide)? Read the official RFC 5322, or you can check out this Email Validation Summary. 
> Note there is no perfect email regex, hence the 99.99%.
> (?:[a-z0-9!#$%&'*+/=?^_`{|}~-]+(?:\.[a-z0-9!#$%&'*+/=?^_`{|}~-]+)*|"(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21\x23-\x5b\x5d-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])*")@(?:(?:[a-z0-9](?:[a-z0-9-]*[a-z0-9])?\.)+[a-z0-9](?:[a-z0-9-]*[a-z0-9])?|\[(?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?|[a-z0-9-]*[a-z0-9]:(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21-\x5a\x53-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])+)\])
>
> Python: 
>      r"(^[a-zA-Z0-9_.+-]+@[a-zA-Z0-9-]+\.[a-zA-Z0-9-.]+$)"
>
> JavaScript:
>     /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/
>
> HTML5:
>    <input type="email" placeholder="Enter your email" />
>
> or  https://www.keycdn.com/support/regex-cheatsheet:
>    /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,5})$/

> Swift, PHP, Perl, Java, C#...

Integer  https://stackoverflow.com/questions/9043551/regex-that-matches-integers-in-between-whitespace-or-start-end-of-string-only:
-----------------------------------------------------------------------------------------------------------------------------------
> positive/negative:   var regex = /^[-+]?\d+$/;

Phone number  https://www.keycdn.com/support/regex-cheatsheet:
--------------------------------------------------------------
> /^\b\d{3}[-.]?\d{3}[-.]?\d{4}\b$/
Therefore, with the above regex expression for finding phone numbers, it would identify a number in the format of 123-123-1234, 123.123.1234, or 1231231234

see: https://www.freecodecamp.org/news/javascript-string-replace-example-with-regex/

