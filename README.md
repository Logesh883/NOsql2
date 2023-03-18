Customer order database in cassandra 

To use this database, you will need to have Apache Cassandra installed and running on your system. You can download Cassandra from the official website: https://cassandra.apache.org/.

Cassandra is a free and open-source, distributed, wide-column store, NoSQL database management system designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure. Cassandra offers support for clusters spanning multiple datacenters, with asynchronous masterless replication allowing low latency operations for all clients. Cassandra was designed to implement a combination of Amazon's Dynamo distributed storage and replication techniques combined with Google's Bigtable data and storage engine model.

This is a sample customer order database created using Apache Cassandra. 
The database consists of three tables: 'customers','orders', and 'order_items'.

customers
The customers table contains information about each 'customer', including their 
                first name, 
                last name, 
                email, 
                phone number,
                address.
                
orders
The orders table contains information about each 'order', including the 
                customer who placed the order, 
                the order date, 
                total amount.
            
order_items
The order_items table contains information about each item in an order, including the 
                order it belongs to,  
                the product it represents,  
                the quantity,
                price.
