# Burp_Suite_lab_projects
The class-leading vulnerability scanning, penetration testing, and web app security platform. Learn with Practical

# What is Burpsuite 
Burp Suit is a Java application that can be used to secure or penetrate web applications. The Suite consists of different tools, such as a proxy server, a web spider, an intruder and a repeater.

urp suite is a Web Penetration Testing framework. It has become an industry standard suite of tools used by information security professionals. Burp Suite helps you identify vulnerabilities and verify attack vectors that are affecting web applications. Because of its popularity and breadth as well as depth of features, we have created this useful page as a collection of Burp Suite knowledge and information.
In its simplest form, Burp Suite can be classified as an Interception Proxy. While browsing their target application, a penetration tester can configure their internet browser to route traffic through the Burp Suite proxy server. Burp Suite then acts as a (sort of) Man In The Middle by capturing and analyzing each request to and from the target web application so that they can be analyzed. Penetration testers can pause, manipulate and replay individual HTTP requests in order to analyze potential parameters or injection points. Injection points can be specified for manual as well as automated fuzzing attacks to discover potentially unintended application behaviors, crashes and error messages


# Burpsuite Alternatives: 
1. Acunetix
2. OWASP ZAP
3. Netsparker
4. W3af

# How to install Burp suite in windows 

offical website: [https://portswigger.net/burp], after signup 
There are Three options :-
1. Burp Suite Enterprise Edition
2. Burp Suite Professional
2. Burp Suite Community Edition

For Free go with community edition and download in your local system.
 
# Installation

First we need to install 
1. Java [https://www.oracle.com/uk/java/technologies/downloads/]
2. ![Alt text](/Images/image.png)

we need to install the burpsuite community edition
Link [https://portswigger.net/burp/documentation/desktop/getting-started/download-and-install]
![Alt text](/Images/image2.png)

# HTTP & how it works
1. HTTP stands for hypertext transfer protocol and is used to transfer data across the Web.
2. The default port is 80
3. The first version HTTP was HTTP/0.9, which was introduced in 1991. The latest version of HTTP is HTTP/3
4. The HTTP protocol is also a stateless protocol meaning that the server isn't required to store session information, and each request is independent of the other.
5. A request consists of: A command or request + optional headers + opntional body content
6. A response consists of: A status code + optional optinal body content.

# HTTP request methods:
__GET:__ The GET method requests a representation of the specified resource. Requests using GET should only retrieve data.
__HEAD:__ The HEAD method asks for a response indentical to a GET request, but without the response body.
__POST:__ The POST method submits an entity to the specified resource, often casing a change in state or side effects on the server.
__PUT:__ The PUT method replaces all current representation of the target resource with the request payload.
__DELETE:__ The DELETE method deletes the specified resource
__CONNECT:__ The connect method establishes a tunnel to the server indentified by the target resources.
__OPTIONS:__ The OPTIONS method describe the communication options for the target resources resources.
__TRACE__ The Trace method performs a message loop-back test along the path to the target resources.

# HTTP Response status code:
1. 1xx: informational: It means the request was received and process is continuing.
2. 2xx: Success: It means the action was successful received, understood and accepted
3. 3xx: Redirection: It means futher action must be taken in order to complete the request.
4.  4xx: Client Error: It means the request contains incorrect syntax or cannot be fullfilled.
5.  5xx: Server Error: It means the server failed to fulfill the valid request.

# Setup Free Web app Penetesting Lab on Cloud

How to setup Free Web app Penetesting Lab on Cloud

Please visit this website for installation: [https://owasp.org/www-project-juice-shop/]
![Alt text](/Images/image4.png)

The below the OWASP documentation github repository
![Alt text](/Images/image5.png)

Check in README.md file for Deploy the app in Heruko.
![Alt text](/Images/image6.png)

Check my deployed Website through Heroku: [https://ows-9b48a3aa05fe.herokuapp.com/#/]
![Alt text](/Images/image3.png)


# Burpsuite Repeater 

1. The repeater tool in Burp Suite allows you to manually send and modify individual HTTP requests repeatedly.
2. It's typically used for more focused and repetitive testing of specific endpoints, parameters, or payloads 
   that you've already identified as interesting or potentially vulnerable.
3. Use the repeater when you want to fine-tune and iterate on specific requests to observe how the application 
   responds to different inputs or payloads.
4. It's helpful for in-depth testing, debugging, and verifying the behavior of the application.


Take some website for pen testing example: [http://www.testphp.vulweb.com/login-php]
![Alt text](/Images/website.png)

Interception is on to check the website
![Alt text](/Images/interception_on.png)

Right click and click to repeater 
![Alt text](/Images/interception_to_repeater.png)

![Alt text](/Images/raw.png)

![Alt text](/Images/repeater_raw_view.png)

![Alt text](/Images/Repeater_render.png)

![Alt text](/Images/wrong_password_302_status_code.png)

I have done the SQL injection Attack, check the status code 200
![Alt text](/Images/SQL_injection_attacj_200_Status_code.png)

We can do the SQL injection attack here not to check the website
![Alt text](/Images/SQL_Injection_attacj_render_part.png)






