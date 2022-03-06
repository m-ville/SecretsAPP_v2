# SecretsAPP
> Express-based web application where you can post your secrets anonymously.


## Register/login 
`Node.js` authentication done using `Passportjs` with,
1. `passport-local-mongoose` : hashing and salting passwords and saving it to  `monoDB Atlas`.
2. `passport-google-oauth20` : Google authentication using *Google Strategy* and saving it to `mongoDB Atlas`.
3. `passport-facebook`       : facebook authentication using *facebook Strategy* and saving it to `mongoDB Atlas`.
4. `express-session`         : for *Cookies & Sessions*.


## DBMS 
> **mongoDB Atlas** for saving the entered data and retrieving it.
