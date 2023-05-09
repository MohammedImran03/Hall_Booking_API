# Hall_Booking_API
Hall booking api with endpoints

To fetch room details
/rooms/ - to get all rooms
/rooms/:id - to get all rooms with id
/rooms/addrooms - to add new rooms
/rooms/editroom/:id - to edit rooms
/rooms/deleterooms/:id - to delete rooms

To fetch customer details
/customer/ - to get all customers
/customer/bookroom - to book room need these to post in body
    Customer_id,
    Room_id,
    Customer_Name,
    date,
    StartTime,
    EndTime
    
/customer/getallbookedrooms - to get booked rooms 
/customer/roomsstatus - to get rooms status
/customer/customersdata - to get customers with room booked status
