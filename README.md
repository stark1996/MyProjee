<h2># MyProjee</h2>
<p>     This is a class project i created in 2017 as a final year project. The project aim was to build an e-commerce project using Spring MVC and DevOps. The languages included are HTML, CSS, JavaScript, JAVA, Hibernate, SQL. Framework used are Bootstrap & Spring. Database used is H2 database.</p>
<p>     The Project is divided into two separate folder : Frontend (i.e. this repository) & Backend (i.e. stark1996/projeeBackend). 
     Spring Web MVC is the original web framework built on the Servlet API and has been included in the Spring Framework from the very beginning. The abbreivation 'MVC' stands for Model-View-Controller.</p>
<img src="https://www.google.co.in/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwj78tmfy4rfAhUBU30KHVOfCxsQjRx6BAgBEAU&url=https%3A%2F%2Fwww.javainterviewpoint.com%2Fspring-mvc-flow-diagram%2F&psig=AOvVaw2NqzOBX3D0wTw9azzZDdeU&ust=1544164517936698" alt="Spring MVC data flow">
<p>     The Frontend part includes the View and Controllers where the controllers duty is to fetch request from the user and take action accordingly. Here the controller interacts with the backend for retrieving/processing data. The Request is then forwarded to view(HTML pages). </p>
<p>     The Backend part includes all the backend logic such as Data processing, Data Storing, Data Manipulation, Security control, Database authorization. It includes models for manipulating data from the database.</p>
<p>     The Project also has spring security inbuild in it for security reason(user's authorization to pages,etc.)</p>

Things Required to begin installing the project?
Needs installing...
<ul>
<li>Jdk 1.8</li>
<li>Glassfish Server(4.1.1)</li>
<li>H2 Database (latest)</li>
<li>apache-maven-3.5.4</li>
<li>rest of the jar files will be downloaded automatically</li>
</ul>

How to Setup the project?
<ul>
<li>First, fork both the projects (i.e. stark1996/projee and stark1996/projeeBackend) to your repo.</li>
<li>Next open Netbeans and clone the projects to your platform</li>
<li>After done, download and install netbeans and use Embedded Server, setup your own setup by making changes in projeeBackend project in src/com/hiberConfig/HiberConfig.java and set the same in h2 database config. once connected, switch back to the project. </li>
<li>Right-click both projects and do build with dependencies</li>
<li>And finally run the projee project by <b>Right-Click -> run</b></li>
<li>Once running, the project will redirect yuh to a login page. The table will generate automatically once compiled. For login details, add by adding a new row in users table in h2 database.</li>
</ul>

<p>Any help required, please email at stevenfernz96@gmail.com</p>
    