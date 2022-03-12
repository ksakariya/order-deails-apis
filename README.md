# Order-detais api 

Details : We have created model for order details page in model.py. in which i have created order,order_details,item,delayed_order model 

## Installation 

1. Clone the project.
2. Create virtual environment. 
3. Activate virtual environment.
4. Got to root folder "pip install -r requirements.txt" by using this command whichever i have used packages it will get install packages in your system

## Start server 

1. To start server use command : "python3 manage.py runserver".

## API
    - Check List of order details , Here is only one end-point for GET,PUT,PATCH,DELETE Request
    
        - GET all records : /orders/v1/
        - GET perticlut record by id : /orders/v1/<:id>
        - PATCH : /orders/v1/<:id>
        - DELETE : /orders/v1/<:id>
        
    - Get List of delayed order details then go to : 
    
        - Get all records : /orders/v1/delayed/get/
        
## Run Scheduler 
    
1. For scheduling task go to the root project.
2. Write command "python/python3 schedule.py" then command fire every 1 minutes
