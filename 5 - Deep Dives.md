# Redis caching
  * products must be cached for quickly access for all types of users 
# Database  Scaling
  * indexing , make The most searching elements in app , to be retrieved faster 
  * Replication for data , because when a specific servar fall , other servers still be able to run stie smoothly and without data loss 
# Consistency and availability
  * Product Booking , so when two users click at the same time it will taken just once
  * showing off each element whether it is avaliable in warehouses or not 
# Idempotency for payments , orders or bookings
# Rate Limiting 
  - making sure that site do not fall into DDOS Attack
# Pagination for products
  - for making request lighter , page are divided into chunks and not getting retrieved once 
# Notifications 
