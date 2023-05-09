# Hall_Booking_API
Hall booking api with endpoints

To fetch room details
http://localhost:6000/rooms/ - to get all rooms
http://localhost:6000/rooms/:id - to get all rooms with id
http://localhost:6000/rooms/addrooms - to add new rooms
http://localhost:6000/rooms/editroom/:id - to edit rooms
http://localhost:6000/rooms/deleterooms/:id - to delete rooms

To fetch customer details
http://localhost:6000/customer/ - to get all customers
http://localhost:6000/customer/bookroom - to book room need these to post in body
    Customer_id,
    Room_id,
    Customer_Name,
    date,
    StartTime,
    EndTime
    
http://localhost:6000/customer/getallbookedrooms - to get booked rooms 
http://localhost:6000/customer/roomsstatus - to get rooms status
http://localhost:6000/customer/customersdata - to get customers with room booked status
