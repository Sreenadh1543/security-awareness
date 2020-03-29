# Web-application-security-awareness

* **Application Security Concepts**

* **LeastPrivileges :** When previleges are loosely assigned .I.e; when users or processes are provided more accesses than they required to complete the action. 
     
	 * **Rule:** User ,application and system functions should run with the least amount of privileges possible to complete their role.
	             "DENY BY DEFAULT" , Access only case by case
     
	 * **Example:** A web application which only makes read operations are assigned with write access so an attacker can levarage this to drop tables by a potential existing weakness through sql injection
	 
	 * **Summary:** Implementing least privileges will not stop exploiting security weaknesses but just makes it harder for an attacker to exploit the weakness.
	 

* **Secure by Default :** Default settings available with in the application should be most secured .

     * **Example :** An application enforces an vauge password restriction for user onboarding and a simple bruteforce attack can break the system; in such cases if client side validations are bi passed and if at server side this data
     
     * Design applications securely from the start and components should use Least Privileges .
     * "Defence in Depth" layered defence mechanisms both application and infrastructure.
     

* **Defense in Depth :** Every layer in the architecture should be secured on it's own so a breach on one layer can still be prevented to have an impact on the whole system
	
	**Example :** Consider if a frontend application is vulnerable to SQL injection attack but the database is implemented with  least previleges so the attacker can not drop tables.
	* Presence of firewalls and segregating the application serves presence to zones will be a part of this idea.
	
	
	
	
	
     
