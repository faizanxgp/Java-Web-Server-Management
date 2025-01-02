# E-SPACE Web Server Manager

“E - Space” deals with the Web Server based Information and Maintenance of the Web Server. Web Services can identify the consumer, whether the consumer is an individual, a business entity, or another Web Service. The Physical location of the consumer is traceable by the Web Service. The Security and Privacy policies related to the consumer are known to a Web Service. Service Level Agreements that exist between the consumer and the service provider are open to web services. URL names and authorities are identified, and the relationship between consumers and Web Services is maintained.

Today, in the fast-moving world of e-commerce, companies must stay competitive by making their products available online. These services must also talk to the partner applications to make the business-to-business communication work. Services may also be provided to the customer to facilitate interactivity on the website and get the customer closer to the organization.  The inherent complexity of automating such services is the interoperability between platforms. Web Services is emerging as the most promising solution to this need.

##### The Project ” E-SPACE” deals with Server maintenance for a company. Reports are generated as the output. 

### **The project consists of:**                     
•	Server Information
•	Customer Information                                              
•	URL Memory Allocation
•	URL Information
•	Payment Details
•	Sales Information
•	Product Delivery Information
•	URL Renewal Details
•	Reports

**Server Information:**
Select the Server Information page and go to the Dnr, which contains general information and evaluation. When selecting the server information, the person has to enter the details about the code, name, style, size, and salt.
If the code already exists, then an error message is displayed. The values are inserted into the Dnr Table if they do not exist. After Insertion, the values are displayed on the screen.

**Customer Information:**
Choose the Customer Information page and go to the customer table, which consists of general information and Evaluation. Select on the customer table, the person has enter the details about cno, cname, company, addr, phone, cmid, password. 
If the cno already exists, then an error message is displayed. The values are inserted into the customer table if they do not exist. After insertion, the values are displayed on the screen.

**Product Information:**
When Product information is selected, a form requesting Product name, Product code, and Price will be displayed. After giving the values when the insert button is selected, the above information will be inserted in a table Product.
         
**Sales Entry:**
When a sales entry is selected, a form will be displayed with hyperlinks to new customers. If he/she is a new customer, a form asking for his information, such as name, company, address, etc, will be asked for, and the details collected will be maintained in the customer table. The customer will be provided with a username and password in the   previous form. Then, a signup page will be displayed, asking for a username and password. In the case of an old customer, he will directly reach this signup page. The customer has to fill it up, and the when to submit button is selected; if the username and Password given are ok, a list showing the item name is displayed along with its price, and a hyperlink is given to each item; at that time itself, the order code and customer code will generate for specification purpose. The customer can click the item he wants, and when clicking the next page, asking for the quantity required is obtained. The customer has to provide the quantity required. When the insert button is selected, the code, code, name, qty order, price, amt, and dat will be inserted in the sales table.  When it is selected, the sales bill will be displayed in the following screen. The bill table will maintain information such as customer, invoice number, request, and status. 

 **URL Memory Allocation:**
The URL Memory Allocation contains the customer number, purchase size, server code, duration, date, URL name, username, password, and type. The amount for URL memory allocation has been obtained from the DNR database per the given size and type.  The above information is stored in the uniform DataBase.

**Payment Details:**
Payment Details contain the preparation of bills and payment entries. The bill is prepared by getting the customer number, invoice number, request, and status from the customer, and the bill is prepared using the information available in the put request Database. In the Payment Entry, the customer can make the payment for the 
URL memory allocation is given to him, and he can pay in terms of dd, cheque, and cash. If the customer has partially paid the Total Purchase Amount, the balance amount is calculated and stored in the Transaction Database.   

**Product Delivery Information:**
 Selecting the Product Delivery Information goes to the customer database, which consists of Product order information. It will display the order code and product code. The person has entered the serial number, which will display along with the order date and delivery code on the screen.
 
**Renewal Details:**
Renewal Details are given by calculating every customer's renewal date and renewal amount using the customer number and url_name. When the customer pays the renewal amount, the renewal receipt is given, and the information is stored in the renewal Database.

**Reports:**

When reports are chosen, a sign-in page will appear to verify the authentication of the Managing Director, as everyone cannot view the reports. Only authorized persons  are allowed to do that. He has given his/her name and password as input, and on selecting the button sign-in, if the above-given details are correct, a page giving a hyperlink to the next page will be obtained, and if not again, the sign-in page will appear. As the Managing Directors are liable to retire by rotation for the convenience of the newly appointed Managing Director, an option for a new MD is given. When it is selected, a  form for setting the name and password will appear.   When choosing the button sign-in, it will go to the page reports, which has the following options.

### INFORMATION REPORTS

Single Customer:  The corresponding customer information is displayed when the customer name is entered.
Entire Customer: All the Customer Information Records are Displayed.
    
**Date Wise Report:**
A form requesting the product name and date will appear when selecting the date-wise report. The text field requesting the name(order info, sales, payment) is designed as a list-down box, and with the help of which, we can select the name we want. We should give the date for which we'd like to the report. When choosing the button ok, the corresponding date will be checked with the date in the product table, and a report will be generated as output.

 **Month Wise Report:**
When selecting the Month Wise Report, a form requesting the name and date will appear.  The text field requesting the name (order info, sales, payment) is designed as a list-down box, and with the help of which, we can select the name we want. The month and the year should be given as input. Selecting the button will check the corresponding month with the month in the transaction table, and a report will be generated as output. Here, we are also giving the year as input along with month as each year we have the same months, so we should know for which corresponding year month-wise report we want.

**Year Wise Report:**
On clicking the Year Wise Report, a form requesting the name and Year will appear. The text field requesting the name (order info, sales, payment) is designed as a list-down box, and with the help of which, we can select the name that we want. 
The year for which we want the report should be given. Selecting the button will check the corresponding year with the year in the Transaction table, and a report will be generated as output.

**Payment Details Report:**
•	Payment Details Report: When a customer code is given, the corresponding Purchase date, Purchase Amount, Amount paid, and Balance are displayed.
•	Single Customer Balance Payable Report: When the customer code is given, the corresponding customer’s balance amount to be paid is displayed for all purchases.
•	Entire Customer Balance Payable Report: The entire customer’s balance amount to be paid and the total balance amount are displayed.                          

**Product Detail Reports:**
•	Month Wise Product Delivery Report: When month and year are entered, the entire Product delivery Information, along with the delivery code and product code, is displayed for the respective month and year.

** Net Profit Information Reports:**
•	Month Wise Net Profit Information Report When month and year are entered, the company's entire sales, Total Collections, and Total Outstanding Balance are displayed for the respective month and year.
•	Year Wise Net Profit Information Report: When the year is entered, the entire sales, Total Collections, and Total Outstanding Balance of the company are displayed for the respective year.

**In this way, “E-SPACE” is processing effectively in utilizing, servicing, and maintaining the memory allocation of the company server.**


### Database Design

**Table name:** LOGIN
Field Name	Data Type 	Description
Ccode	Varchar	Client code
Pwd	Varchar	Password

**Table Name:** SEVER
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

**Table Name:** CUSTOMER
Field Name	Data Type	Description
Cno	Number	Client no
Cname	Varchar	Client name
Company	Varchar	Company name
Addr	Varchar	Address
Phoneno	Number	Phoneno
Pwd	Varchar	Password
Cid	Varchar	Client id

**Table Name:** URL BOOK
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
Design	Varchar	Design of URL

**Table Name:** URL INFO
Field Name	Data Type	Description
Ccode	Number	Client code
Urlname	Varchar	Urlname
Dname	Varchar	Domainname
Mname	Varchar	Maintenance name

**Table Name:** ORDER PLACE
Field Name	Data Type	Description
Cno	Number	Client no
Prcode	Varchar	Product code
Prname	Varchar	Product name
Qty	Number	Quantity
Amt	Number	Amount
Ono	Number	Order no
Sdate	Varchar	Sales date
Price	Number	Price

**Table Name:** CPAYMENT
Field Name	Data Type	Description
Ccode	Number	Client code
Payamt	Number	Payment amount
Date	Varchar	Paydate
Paytype	Varchar	Payment type
Cheddno	Number	Cheque/dd no
Bankinfo	Varchar	Bank address
Ono	Number	Order no


**Table Name:** SPAYMENT
Field Name	Data Type	Description
Ccode	Number	Client code
Scode	Number	Server code
Size	Number	Required size
Amt	Number	Amount
Ono	Number	Order no

**Table Name:** PRODUCT PAY
Field Name	Data Type	Description
Prcode	Varchar	Product code
Paydate	Varchar	Payment date
Ccode	Number	Client code
Amt	Number	Amount
Paytype	Varchar	Payment type
Ddcheno	Number	dd/cheque no
Ono	Number	Order no

**Table Name:** RENEWALS
Field Name	Data Type	Description
Custcode	Number	Customer code
Sercode	Number	Server code
Urlname	Varchar	Urlname
Date	Varchar	Renewal date
Amt	Number	Amount

**Table Name:** SALES
Field Name	Data Type	Description
Prcode	Varchar	Product code
Prname	Varchar	Product name
Price	Number	Price
Qty	Number	Quantity
Amt	Number	Amount
Sdate	Varchar	Sales date

