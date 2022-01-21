# In the name of Allah❤️
# Console_Web
information is displayed for you on the console!
# OPSHENS :
keylogger, IP Addres And Vershen browser And Online Or Ofline ...![Screenshot 2022-01-22 030413](https://user-images.githubusercontent.com/86854694/150613400-196c2f89-55f9-416b-96b3-1c25f6d5b8a5.png)
# Programming ?
Html, Jvascript
# Code :
    <!DOCTYPE html>
     <html lang="en" itemtype="http://schema.org/WebPage">
     <head>
    <!-- In the name of Allah❤️ -->
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Console Terminal</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    </head>
    <body style="font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">
        <div style="background-color: #f6f7fa;
        box-shadow: 5px 5px 7px rgb(98, 113, 114); 
        border-radius: 10px;
        width: 700px;
        height: 400px;">

             <!-- style web -->
             <h1 style="font-size: 40px; margin: 15px;" id="welcom">Plese Go To Console .</h1>
             <script>
                 document.getElementById("welcom").addEventListener("mouseover", function (){
                     document.getElementById("welcom").innerHTML = "Thankful !"
                 })
             </script>

             <br>

             <a href="https://github.com/mrExploitwriter" style="font-size: 20px;
             margin: 15px;">My Github!</a>
             <hr>

                 <script>

                // welcom!
                alert("❤️ In the name of Allah ❤️")
                var input = prompt("Hi, Plese You r Name ?")
                alert("Ok Successful. Thankful ("+input+") The information is displayed for you on the console!")
                alert("Steps to exit the Console: << ...Right-click inspect and select Console in the menu... >>")
                alert("!! Lets Go !!")

                // Oneline or Ofline Pc
                var online = navigator.onLine
                console.log("Internet # (",online,")")
                console.log("+=+=+=+=+=-=-=-=-=-=-=-=-=-=-=-=-=-=+=+=+=+")
                // Vershen bowroser
                var vershen = navigator.appVersion
                console.log("APP vershen! {{",vershen,"}}")
                console.log("+=+=+=+=+=-=-=-=-=-=-=-=-=-=-=-=-=-=+=+=+=+") 
                // IP
                $.get("https://api.ipify.org", function(ip){
                    console.log("IP: [",ip,"]")
                    console.log("+=+=+=+=+=-=-=-=-=-=-=-=-=-=-=-=-=-=+=+=+=+")
                    console.log("Kilogger | run ;")
                    console.log("-[+]- -[+]- -[+]- -[+]- -[+]- -[+]- -[+]- -[+]-")
                })
                // Keloggers .
                document.addEventListener("keypress", function(data){
                    var key = (data.key)
                    console.log("Key == ",key)
                    console.log("+=+=+=+=+=-=-=-=-=-=-=-=-=-=-=-=-=-=+=+=+=+")
                })
                // ..............
             </script>
    </div>
    </body>
    </html>

