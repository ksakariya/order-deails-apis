Order-detais api 

Details : We have created model for order details page in model.py. in which i have created order,order_details,item,delayed_order model 

Step to install django project :

1. Clone the project 

2. Got to root folder "pip install -r requirements.txt" by using this command whichever i have used packages it will get install packages in your     system

3. Run project by command "python manage.py runserver"
    - Check List of order details , Here is only one end-point for GET,PUT,PATCH,DELETE Request
        - GET all records : /orders/v1/
        - GET perticlut record by id : /orders/v1/<:id>
        - PATCH : /orders/v1/<:id>
        - DELETE : /orders/v1/<:id>
    - Get List of delayed order details then go to : 
        - Get all records : /orders/v1/delayed/get/
    
4. For scheduling task go to the project and write "python/python3 schedule.py" then command fire every 1 minutes
