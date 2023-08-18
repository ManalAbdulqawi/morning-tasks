# Designing for failure

​
Identify the kinds of failure readiness described below, giving your reasoning;
​

- A system that switches to a new server when one fails

Failover: to ensure the availability of the system when the failure happening or handling bugs.
​

- Adding replica databases with a master database:

Redundancy:to avoid Single points of failure if the app depends on one database
​

- Having a 2-3 colleagues who have access to the master password

Redundancy: to ensure the system is working, monitring and maintaining if one staff is absent
​

- Performing health checks on a server

Monitoring: to detect the failurs before they happen or handling them before they impact the system or end-users.
​

- Spreading out user requests over multiple machines rather than just one
  powerful one

Load balancing: to avoid overload requests in one server which may make it slow or not working.
