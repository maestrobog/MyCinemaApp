## General info
I have created this "Cinema app" project to demonstrate my expertise Spring MVC, Spring Security, Spring Data, Hibernate, Servlet API, H2, JSTL
This project was created for online booking of tickets for cinema performances. Users can view the session schedule, stage selection and ticket reservations. Administrators can manage sessions, movie performances, etc.

## Technologies
In project these technologies have been used:
```
* Java 11
* MySQL
* Spring
* Hibernate
* Tomcat 9.0.50 (to run app locally)

```

## Credentials
<table width="100%" cellspacing="0" cellpadding="5">
   <tr> 
        <td valign="top" align="center"><b>&nbsp;</b></td>
        <td valign="top" align="center"><b>Guest</b></td>
        <td valign="top" align="center"><b>Registered user</b></td>
        <td valign="top" align="center"><b>Admin</b></td>
   </tr>
    <tr> 
        <td valign="top" align="center"><b>Registration</b></td>
        <td valign="top" align="center"><b>+</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>-</b></td>
   </tr>
    <tr> 
        <td valign="top" align="center"><b>View available sessions</b></td>
        <td valign="top" align="center"><b>+</b></td>
        <td valign="top" align="center"><b>+</b></td>
        <td valign="top" align="center"><b>+</b></td>
   </tr>
    <tr> 
        <td valign="top" align="center"><b>Process the order</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>+</b></td>
        <td valign="top" align="center"><b>+</b></td>
   </tr>
    <tr> 
        <td valign="top" align="center"><b>View orders history</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>+</b></td>
        <td valign="top" align="center"><b>+</b></td>
   </tr>
    <tr> 
        <td valign="top" align="center"><b>View registered users</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>+</b></td>
   </tr>
    <tr> 
        <td valign="top" align="center"><b>Delete users</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>+</b></td>
   </tr>
    <tr> 
        <td valign="top" align="center"><b>View all orders</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>-</b></td>
        <td valign="top" align="center"><b>+</b></td>
   </tr>
  </table>

The structure of the database can be seen below:

![image](https://user-images.githubusercontent.com/106582552/210845955-4bbfe202-96a7-4d42-aae8-bf1fd1c870e5.png)


## To start a project by your own you have to:

1️⃣ Clone this project into your local directory and open the project in an IDE.

2️⃣ To configure the MySQL DBMS, provide the database URL and password, and username
in the project directory.

3️⃣ Configure Apache Tomcat (I recomend you to use Tomcat 9.0.54)

4️⃣  Run Tomcat 🚀

5️⃣ To register send request with body {"email":"testmail@gmail.com", "password":"correctPassword4u", "repeatPassword":"correctPassword4u"} to /register of yours host   
