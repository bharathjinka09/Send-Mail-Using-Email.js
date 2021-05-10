### Send mail using Email.js
 </br>

This project is all about seding mail using a library called [email.js](https://emailjs.com) without using any backend language.

#### Setup
<code>
 User ID => user_randomid
 Access Token youraccess token

(function () {
    emailjs.init(USERID);
})();
emailjs.send("SERVICE ID", "TEMPLATE NAME", {
    to_name: "USERNAME",
    from_name: "FROM NAME",
    message: "MESSAGE",
});
</code>