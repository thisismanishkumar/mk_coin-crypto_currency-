# crypto_currency
Here are three servers for your conviennce. Differ only by account holder name and their port number.
With the help of __POSTMAN__ certain kind of.
__GET__ request are:-
+ mine_block
  * This should be executed first to create __Genesis Block__ .It creates a block having transactions. 
+ get_chain
  * This displays list of all blocks present in a block chain.
+ is_valid
  * Verify whether blocks are valid or not through proof of work.
+ replace_chain
  * This requests replaces current chain with the longest chain in the connect nodes.

 __POST__ request are:-
- add_transaction
  * In this requests post __JSON__ format r given in [transactions.json](/transactions.json) format.
- connect_node
  * It used to connect list of nodes. Post requests in __JSON__ format given in [nodes.json](/nodes.json) format.  

## As we are using __Flask__ framework to connect Web application, So default address is:-
### http://127.0.0.1: __Port Number__ / __Request__

## To be installed:
+ Flask==0.12.2: pip install Flask==0.12.2
+ Postman HTTP Client: https://www.getpostman.com/
+ (requests library) pip install requests==2.18.4
