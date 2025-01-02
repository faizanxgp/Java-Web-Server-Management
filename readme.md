E-SPACE
Abstract

                        “E - Space” deals with the Web Server based Information and Maintenance of the Web Server. Web Service can identify the consumer whether the consumer is an individual, a business entity or another Web Service. The Physical location of the consumer is traceable by the Web Service. The Security and Privacy policies related to the consumer are known to a Web Service. Service level Agreements that exist between the consumer and the service provider are open to the web services. URL names and URL Authorities are identified and maintains the relationship between the consumers and Web Services.

                              Today in fast moving world of   E-Commerce, Companies realize to stay competitive in making their products available over the Internet. These services also need to talk to the partner applications to make the business to business communication work. Services may also be provided to the customer to get the interactivity in the website and get the customer closer to the organization.  The inherent complexities of automating such services are the interoperability between platforms. Web Services is emerging as the most promising solution to this need.
            The Project ”E - SPACE” deals with the Server maintenance for a company. Reports are generated as the output. The project consist of  
                   
•	Server Information
•	Customer Information                                              
•	URL Memory Allocation
•	URL Information
•	Payment Details
•	Sales Information
•	Product Delivery Information
•	URL Renewal Details
•	Reports

       Server Information:
              Select on the Server Information page, goes to the Dnr which consists of general information and evaluation. Selecting on the Server Information, the person has enter the details about scode,  sname,  stype,  ssize, samt .
                If the scode already exists then error message is displayed. If it does not exists then the values are inserted into the Dnr Table. After Insertion the values are displayed in the screen.

Customer Information:
            Choose on the Customer Information page, goes to the customer table which consists of general information and Evaluation. Select on the customer table, the person has enter the details about cno, cname, company, addr, phone, cmid, password. 
            If the cno already exists then error message is displayed. If it does not exists then the values are inserted into the customer table. After insertion the values are displayed in the screen.

Product Information:
            
           When Product information is selected a form requesting Product name, Product code, Price will be displayed. After giving the values when insert button is  selected  the above information will be inserted in a table Product.
         
Sales Entry:

            When sales entry is selected a form will be displayed having hyperlinks new customer. If he/she is new customer a form asking for his information such as name, company, address etc, will be asked for and the details collected will be maintained in    customer table. The customer will be provided with a username and password in the   previous form itself. Then, a signup page will be displayed asking for username and password. In the case of old customer he will directly reach this signup page. The  customer has to fill it up and when submit button is selected if the username and  Password given are ok, a list showing the item name is displayed along with its price and  hyperlink is given to each item, at that time itself the ordercode and customercode will generate for specification purpose. The customer can click the item he wants and when clicked next page asking for quantity required is obtained. The customer has to provide the quantity required. When insert button is selected, the ocode, ccode, pname, qtyorder, price, amt, dat will be inserted in sales table.  In the following screen whenbill is selected sales bill will be displayed. The information such as Customer, Invoice no, request, status will be maintained in bill table. 

 URL Memory Allocation

                     The URL Memory Allocation contains customer number, size of purchase, server code, duration, date, URL name, username, password, urltype. The amount for url memory allocation has got from Dnr database in accordance with given size and urltype.  Above Information are stored in the dnrform DataBase.
Payment Details:
                   Payment Details contains preparation of bill and payment entry. The Preparation of bill is done by getting customer number, Invoice number, Request and status from the customer and the bill is prepared from the information available in pdtrequest  Database. In the Payment Entry, the customer can make the payment for the 
url memory allocation  given to him and he can pay in terms of dd, cheque and cash. If the customer is made a part payment of the Total Purchase Amount, then balance amount is   calculated and stored in Transaction Database.   

 Product Delivery Information:
                      Selecting on the Product Delivery Information, goes to the cusorder database which consists of  Product order information. It will display the ordercode and product code and the person has enter the serial number  and it will display alone with the orderdate and delivery code in the screen.
Renewal Details:
                       Renewal Details is  given by calculating  the renewal date, renewal amount  for every customer using the customer number and url_name. And when the renewal amount is paid by the customer, the renewal receipt is given and the information is stored in the renewal  Database.
Reports:
                    When reports is choosed as sign in page will appear in order to verify the authentication of the Managing Director, as every one cannot view the reports. Only authorized persons  are allowed to do that. He has give his/her name and password as input and on selecting the  buttonsign in if the above given details are correct a page giving hyper link to the next   page will be obtained and if not again the sign in page will appear. As the Managing Directors are liable to retire by rotation for the convenience of the newly appointed Managing Director an option new md is given and when it is selected a  form for setting the name and password will appear.   On selecting the button sign in it will go to the page reports which has the following options

	Customer  Information  Reports
	Product   Information Reports


    CUSTOMER INFORMATION REPORTS

Single Customer:  When Customer Name is Entered Corresponding Customer Information is displayed.
Entire Customer: All the Customer Information Records are Displayed.


PRODUCT  INFORMATION REPORTS

	 Single Product:  When Product Name is Entered Corresponding Product Information is displayed.
	Entire Product: All the Product Information Records are Displayed.
        

Date Wise Report

                  On selecting the date wise report, a form requesting the productname and  date will appear. The text field requesting the name(orderinfo,sales,payment) is  designed as listdown box and with the help of which we can select the name,  which we  want. The date for which we want the report should be given. On selecting the button ok  the corresponding date will be checked with the date in the product table  and a report  will be generated as output.

 Month Wise Report:

                     On selecting the Month Wise Report a form requesting the name and date will appear.  The text field requesting the name (orderinfo,sales,payment) is designed as list down box and with the help of which we can select the name, which we want. The month and the year should be given as input. On selecting the button the corresponding month will be checked with the month in the transaction table and a report will be generated as output. Here we are giving the year also as input along with month as in each year we are having the same months and so we should know that for which corresponding years  month wise report we want.

  Year Wise Report:
            On clicking the Year Wise Report a form requesting the name and Year will   
 appear. The text field requesting the name (orderinfo,sales,payment) is designed as list 
down box and with the help of which we can select the name, which we want. The year 
for which we want the report should be given. On selecting the button the   corresponding year will be checked with the year in the Transaction table and a report 
will be generated as output.

Payment Details Report:    

•	Payment Details Report: When a customer code is given, the corresponding Purchase date, Purchase Amount, Amount paid and Balance is displayed.

•	Single Customer Balance Payable Report: when customer code is given, the corresponding customer’s balance amount to be paid is displayed for entire purchases.
•	Entire Customer Balance Payable Report: Entire customer’s balance amount to be paid is displayed along with total balance amount.                          
Product Detail Reports:
	
•	Month Wise Product Delivery Report:  When month and year is entered, the entire Product delivery Information along with the delivery code and product code is displayed for the respective month and year.

 Net Profit Information Reports:

•	Month Wise Net Profit Information Report When month and year is entered, the entire TotalSales, Total Collections, Total Outstanding Balance of the company  is displayed for the respective month and year.
•	Year Wise Net Profit Information Report: When  year is entered, the entire TotalSales, Total Collections, Total Outstanding Balance of the company  is displayed for the respective  year.

In this way  “ E - SPACE ” is processing in an effective manner in utilizing, servicing and maintaining the memory allocation of company server.








System Specification

Hardware Specification

Processor                    :celeron
Speed                          : 667 MHz
Hard Disk                   : 4 GB
RAM                           : 64 MB
Display Card              : Super Video Adapter(SVGA)
Keyboard                    : Standard 102 Enhanced Keyboard
Mouse                      : Logitech Serial Mouse







Software Specification

Operating  System                  :Windows 98/2000/XP
Web  Server                             : Apache Tomcat 4.1.7
Web Browser                           : Internet Explorer
Front End Tool                        : HTML
Back End Tool                         : SQL Server 2000
Client side Script
  Languages                           : JavaScript
Server side  Technology          : Java Server Page(JSP)
 








Database Design
          
Table name  : LOGIN

Field Name	Data Type 	Description
Ccode	Varchar	Client code
Pwd	Varchar	Password


Table Name  : SEVER

Field Name	Data Type	Description
Scode	Number	Server code
Sname	Varchar	Server name
Stype	Varchar	Server type
Ssize	Number	Server size
Sloca	Varchar	Server location
Company	Varchar	Company name
Authority	Varchar	Authority
Addr	Varchar	Address
Eid	Varchar	Email id
Phoneno	Number	Phone no

Table Name  : CUSTOMER

Field Name	Data Type	Description
Cno	Number	Client no
Cname	Varchar	Client name
Company	Varchar	Company name
Addr	Varchar	Address
Phoneno	Number	Phoneno
Pwd	Varchar	Password
Cid	Varchar	Client id





Table Name  :URL BOOK

Field name	Data Type	Description
Cno	Number	Client no
Size	Number	Required size
Scode	Number	Server code
Dur	Number	Duration
Dat	Varchar	Date of booking
Urlname	Varchar	Urlname
Domname	Varchar	Domain name
Pword	Varchar	Password
Utype	Varchar	Urltype
Ono	Number	Order no
Design	Varchar	Design of url

Table Name : URL INFO

Field Name	Data Type	Description
Ccode	Number	Client code
Urlname	Varchar	Urlname
Dname	Varchar	Domainname
Mname	Varchar	Maintenance name

Table Name  : ORDER PLACE

Field Name	Data Type	Description
Cno	Number	Client no
Prcode	Varchar	Product code
Prname	Varchar	Product name
Qty	Number	Quantity
Amt	Number	Amount
Ono	Number	Order no
Sdate	Varchar	Sales date
Price	Number	Price

Table Name  : CPAYMENT

Field Name	Data Type	Description
Ccode	Number	Client code
Payamt	Number	Payment amount
Date	Varchar	Paydate
Paytype	Varchar	Payment type
Cheddno	Number	Cheque/dd no
Bankinfo	Varchar	Bank address
Ono	Number	Order no


Table Name : SPAYMENT

Field Name	Data Type	Description
Ccode	Number	Client code
Scode	Number	Server code
Size	Number	Required size
Amt	Number	Amount
Ono	Number	Order no

Table Name : PRODUCT PAY

Field Name	Data Type	Description
Prcode	Varchar	Product code
Paydate	Varchar	Payment date
Ccode	Number	Client code
Amt	Number	Amount
Paytype	Varchar	Payment type
Ddcheno	Number	dd/cheque no
Ono	Number	Order no

Table Name : RENEWALS

Field Name	Data Type	Description
Custcode	Number	Customer code
Sercode	Number	Server code
Urlname	Varchar	Urlname
Date	Varchar	Renewal date
Amt	Number	Amount

Table Name : SALES

Field Name	Data Type	Description
Prcode	Varchar	Product code
Prname	Varchar	Product name
Price	Number	Price
Qty	Number	Quantity
Amt	Number	Amount
Sdate	Varchar	Sales date

