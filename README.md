# security-awareness

**Security Fundementals**

* Application Security Concepts

     * **LeastPrivileges :** When previleges are loosely assigned .I.e; when users or processes are provided more accesses than they required to complete the action. 
     
	 * **Rule:** User ,application and system functions should run with the least amount of privileges possible to complete their role.
	             "DENY BY DEFAULT" , Access only case by case
     
	 * **Example:** A web application which only makes read operations are assigned with write access so an attacker can levarage this to drop tables by a potential existing weakness through sql injection
	 
	 * **Summary:** Implementing least privileges will not stop exploiting security weaknesses but just makes it harder for an attacker to exploit the weakness
     
