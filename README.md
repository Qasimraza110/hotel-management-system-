Hotel Management System
Introduction   
Efficient management of hotel bookings, cancellations, and room statuses is critical to the success of the hospitality industry. This project, the *Hotel Management System*, aims to provide an automated, user-friendly solution for managing hotel operations. The system will use robust data structures and algorithms to handle room allocations, booking priorities, cancellations, and room availability displays.

Project Objectives
1. Automate room booking and cancellation processes.
2. Handle booking requests based on room types and floor preferences.
3. Provide priority-based booking for urgent requests.
4. Maintain a booking history for future reference.
5. Display room statuses using in-order traversal for efficient management.

Project Features
1. Room Management:
   - Store information about room ID, type, floor, and status (READY, BOOKED, OCCUPIED, UNAVAILABLE).
   - Use a doubly linked list for sequential access and a binary search tree (BST) for efficient in-order traversal.

2. Booking Requests:
   - Accept booking requests specifying room type, floor preference, customer details (name, phone number, CNIC), number of nights, and urgency.
   - Use a queue structure to separate priority and regular booking requests.

3.Booking Processing:
   - Assign rooms matching the customer’s request.
   - Update room status and store booking information in a stack for easy cancellation.

4. Booking Cancellation:
   - Cancel the most recent booking using a last-in, first-out (LIFO) structure.
   - Reset room status to READY and clear customer information.

5. Room Status Display:
   - Traverse the BST in-order to show all rooms, including type, floor, and current status.

Data Structures:
  Doubly Linked List: for room storage and traversal.
  Binary Search Tree: for efficient room searching and display.
  Queue: for booking requests (separate queues for priority and regular).
  Stack:  for booking history and cancellations.

Implementation
1. Classes and Objects:
   Room Class: Stores room details, including ID, type, floor, status, and customer information.
   BookingRequest Class: Holds booking request information.
   TreeNode Class: Nodes for the binary search tree.
   HotelManagement Class: Manages all core functionality, including adding rooms, processing requests, and managing booking history.
   
2. User Interface :
     - Add a booking request.
     - Process all pending requests.
     - Cancel the most recent booking.
     - Display booking history.
     - Display all room statuses.


Conclusion
The proposed Hotel Management System will streamline hotel operations, enhance customer service through efficient room management, and provide a scalable foundation for future enhancements. This project will demonstrate the effective use of advanced data structures and provide hands-on experience in managing real-world problems in software development.
