API LIST

TO create a room(POST) - http://localhost:6000/api/hall/createroom

          * Send room details in body as json
              
              BODY :
                       {
                              "number of seats availabe": "200",
                             
                              "Price for 1 Hour": "Just only RS 1000" 
                            }
To get all the booked room data(GET) - http://localhost:6000/api/hall/bookedrooms


To Book a room(POST) - http://localhost:4000/api/hall/book

          * Send details in body as json

             BODY EXAMPLE:
                  {
                  "CustomerName":"anu",
                                    "StartTime":"6PM",
                  "EndTime":"10PM",
                  "RoomName":"BBB"
                  }

1*   Check readme    



## To get all the booked room data(GET)


{"_id":{"$oid":"654f9544a6d7ea739de68489"},"username":"anu","emailid":"anu@gmail.com","password":"$2b$10$QmlUk/LG7Hk5vYtScaGDiO1TEidldTOK0CzhqWKVieG3dlWliJrb2","__v":{"$numberInt":"0"},"resetPasswordToken":null,"resetPasswordTokenExpiery":null}


![image](https://github.com/c2hsasi/Test/assets/129680190/d94bf3ac-53e8-48eb-a600-7f5daac06447)
