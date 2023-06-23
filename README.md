# rekey-with-function
https://developer.confluent.io/tutorials/rekey-with-function/ksql.html

Consider a stream of customer information events keyed by ID. Each event contains a few attributes, including the customer's phone number. In this tutorial, we'll write a program that rekeys the topic by the area code of the phone number. Customers with the same area code will be placed into the same partition in the new topic.
