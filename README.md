Given below are the API/Batch Feed short description and endpoint details for Commerce Orchestration to consume and get the response:
TOURS:
1.1 Tour catalog feed from Supplier to Commerce Orchestration:

Description:

    This batch feed will be triggered from Supplier system to Commerce Orchestration (CO)periodically (once or twice or thrice in a day which will be configurable value) and CO will use the catalog feed for further processing.
Endpoint : 

    The dummy endpoint created by mocking supplier response to CO.
    https://d92b82eb-137a-46d1-babf-a62cfa969f82.mock.pstmn.io/productFeed/tours
1.2 Tour Price and availability status for 30 days from Commerce Orchestration to Suppliers:

Description:

    This API will be triggered from CO to retrieve the Price and Availability of tour products for 30 days window.
Endpoint :

    The dummy endpoint created by mocking supplier response to CO.
    https://d92b82eb-137a-46d1-babf-a62cfa969f82.mock.pstmn.io/availability/tours
1.3 Tour Price and availability (real-time check) for the selected tour, date and time from Commerce Orchestration to Suppliers:

Description:

    This API will be triggered from CO to retrieve the real-time Price and Availability of tour products for the selected tour, selected date and time.
 Endpoint : 

    The dummy endpoint created by mocking supplier response to CO.
    https://d92b82eb-137a-46d1-babf-a62cfa969f82.mock.pstmn.io/availability/tours?date=2024-03-01&time=12:00:00
PARKING
2.1 Parking catalog feed from Supplier to Commerce Orchestration:

Description:

    This batch feed will be triggered from Supplier system to Commerce Orchestration (CO)periodically (once or twice or thrice in a day which will be configurable value) and CO will use the parking catalog feed for further processing.
Endpoint : 

    The dummy endpoint created by mocking supplier response to CO.
    https://d92b82eb-137a-46d1-babf-a62cfa969f82.mock.pstmn.io/productfeed/parking
2.2 Parking Price and availability status for 30 days from Commerce Orchestration to Suppliers:

Description:

    This API will be triggered from CO to retrieve the Parking price and Availability of parking products for 30 days window.
Endpoint :

    The dummy endpoint created by mocking supplier response to CO.
   https://d92b82eb-137a-46d1-babf-a62cfa969f82.mock.pstmn.io/availability/parking
2.3 Parking Price and availability (real-time check) for the selected parking product, date and time from Commerce Orchestration to Suppliers:

Description:

    This API will be triggered from CO to retrieve the real-time Price and Availability of Parking products for the selected parking, selected date and time.
 Endpoint : 

    The dummy endpoint created by mocking supplier response to CO.
    https://d92b82eb-137a-46d1-babf-a62cfa969f82.mock.pstmn.io/availability/parking?Date=2024-03-01&Time=12:00:00
