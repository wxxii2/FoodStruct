# project-t15-H1gogogo

1. [URL for live website]

2. Descriptions of working requests:
    
3. Database Access:</br>
    CONNECTION_STRING = "mongodb+srv://toricas:wang796005@cluster0.o9rvr.mongodb.net/customer?retryWrites=true&w=majority"</br>
    MONGO_USERNAME=toricas</br>
    MONGO_PASSWORD=wang796005</br>

4. Login Details:</br>
    - Costomer login:</br>
        username: asd</br>
        password: asd123456</br>

        username: 111</br>
        password: qwer123456</br>

    - Vendor login:</br>
        Vendorid: DylanBob</br>
        password: 123</br>

        Vendorid: six seeds</br>
        password: 123</br>

        Vendorid: Tasty Trailer</br>
        password: 123</br>

        Vendorid: Sushi</br>
        password: 123</br>

        Vendorid: Cafe Ark</br>
        password: 123</br>

5. other notes
    - food collection
        there are 8 snacks with their "_id", "name", "picture", "price"
    - order collection
        orders contains customer infomation of who submit the order "customer", vendor who receive the order "vendor", 
        snack array that contain foodname, quantity, price "snack", status of the order "status", 
        rating of the order "ratings", comment of the order "comment", total price of the order "total", 
        and whether is is discounted "discount", and the id of the order ""
    - vendor collection
        Vendor is displayed with "_id", vendor name "name", "location" which is a arry contain coordinates according to 
        [latitude, longtitude], "password", textaddress, "parked" as a status of parking. If the vendor unpark their
        car, the location will be set to a empty array.

    - register
        one can easily register by enter new email and password and press register button, the family name and given name
        will be set to default first, one can then change it in the profile.
        
    - wrong user name/password
        if customers input nonexistent username/wrong password, a message will be shown to notify them. 


