# SpringCloudConfigServer

What is exchange rate of one currency in another?
  
http://localhost:8000/currency-exchange/from/USD/to/INR

{
"id":1001,
"from":"USD",
"to":"INR",
"conversionMultiple":66.00,
"environment": "8000 instance-id" 

}


Convert 10 USD into INR

http:localhost:8100/currency-conversion/from/USD/to/INR/quantity/10

{
  "id":1,
  "from":"USD",
  "to":"INR",
  "conversionMultiple":65.00,
  "quantity":10,
  "totalCalculatedAmount:650,
  "environment":8000
}


API's

currency exchange:
http://localhost:8001/currency-exchange/from/USD/to/INR

currency conversion:
http://localhost:8100/currency-conversion-feign/from/USD/to/INR/quantity/6

Eureka:
http://localhost:8761/

API GATEWAY:
http://localhost:8765/CURRENCY-EXCHANGE/currency-exchange/from/USD/to/INR



















