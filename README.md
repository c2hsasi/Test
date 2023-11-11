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
