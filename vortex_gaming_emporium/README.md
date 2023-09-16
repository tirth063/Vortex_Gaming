# vortex_gaming_emporium

A simple app to provide online booking fesility og gamezone store

## Getting Started

**PROJECT REPORT ON** 

**Vortex Gaming Emporium**

**SUBMITTED BY:**

**Jay R. Gayakwad**

**Vansh K. Gandhi** 

**Fenil N. Trivedi** 

**Tirth R. Patel**  


**INDEX** 



||**Chapter**|**Page No.**|
| :- | - | - |
||||
|**1.** |<p>**Introduction**</p><p>1\.1  **Project description**</p>|**3 – 5** |
||1\.2  **Project Profile**||
||||
|**2.** |**Objectives** |**6**|
||||
|**3.** |**System Flow Diagram** |**7 – 8** |
||||
|**4.** |**UML Diagram** |**9**|
||||
|**5.** |**ER Diagram** |**10**|
||||
|**6.** |**Database Design** |**11 – 12**|
||||
|**7.** |**System Design** |**13 – 16**|
||||
|**8.** |` `**References**|**17** |

1. **Introduction !
1. **Project Description** 
- Vortex Gaming Emporium is an application designed primarily for Gaming People who can book the PCs from their home. 
- The Vortex Gaming Emporium application is made in Android Studio with Flutter Framework and also the Dart Language is used. 
- The Firebase Database is used for Login and Registration of users which is managed by firebase Auth or Authentication. 
- This application is mobile friendly and have a good-looking user interface. 
- Vortex Gaming Emporium contained three tabs: 
- Home tab 
- Booking tab 
- History tab 
- **Home Tab:** 
- It is mandatory to login or register for using the application. 
- If the User has forgotten his password, they can reset their password with their email-id.
- The resetting the password works like you first need to send email to the user and for that we use sendPasswordResetEmail method after that if user going to click on the email, it will be redirected to a default page provided by firebase from there user can reset their password. 
- If the login is successful, first thing the user will see the welcome message. 
- After that user can see when the shop is opened and closed at the current time. 
- Last the user will see the container of images and prices of the zones and if the user clicks on the image container, they will directly go to the booking tab. 
- The Zone contains:
1. Common Zone 
1. Private Zone 
1. Gaming Zone 
- **Booking Tab:** 
- In booking tab, the first thing user will see the hover images of different games like Call of Duty, GTA 5, Valorant, Fall Guys which are available in all PCs. 
- After that user can select any zone as per their preferences or needs. 
- In Common zone the first thing user has to select the time slot which is between 9:00 am to 7:00 pm for the current days’ time. The user can also 

select multiple time slots as per the requirements.

- After booking the time slots the user had to book the computers number between 1 to 20. The user can also select multiple computers as per their 

requirements, but only if that particular computer number are not selected by other users. •  After that user had to click on book button and the alert dialog box will popup which asks for confirmation and it also contains the details of the selected 

zone, computer number, time slot and total cost. If user click on book button in alert dialog box the user will then go to the payment page and they have to fulfil the payment process, after that the confirmed booked page is shown to users in which they can see their details of booking process also if they want to save their details, they can save it with save button and screenshot will be saved in their device gallery.

- The same process for the Private Zone and Gaming Zone.
- **History Tab:** 
- In History tab the user can see their booked details. 
- The booked detail contains which zone the user had booked, which time slot and the booked computer number for that particular day. 
2. **Project Profile**  



|Project title: |Vortex Gaming Emporium |
| - | - |
|Frontend: |` `Flutter, Dart |
|Backend: |FIREBASE |
|Target Audience: |<p>` `Any age of people above 18 can Discover, book, and enjoy gaming sessions at their favorite </p><p>zones effortlessly                  </p>|
|Platform: |Android Studio |
|Documentation tool: |MicroSoft Word |
|Internal Guide: |Priyanka Ma’am|
|Submitted to: |Priyanka Ma’am|

2. **Objectives!**

 **Start to End Process:**

1. To create an online gaming shop application that provides a platform for users to book computer services. 
1. To provide a user-friendly interface for booking computer services.  
1. To provide a secure payment gateway for users to make payments. 
1. To maintain a record of booked services in a Firebase database. 
1. Custom Functions & Validations. 
1. Making responsive design.  
1. Debugging and code optimization. 
3. **System Flow Diagram![ref2] ![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.019.png)![ref4]![ref5]![ref6]![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.023.png)![ref7]**
- **Login and Registration Process Flow Diagram:** 

![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.025.png)

- **Booking Tab Flow Diagram:**

![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.026.png)

4. **UML Diagram ![ref2] ![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.027.png)![ref4]![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.028.png)![ref5]![ref6]![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.029.png)![ref7]**
5. **ER Diagram![ref2] ![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.030.png)![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.031.png)![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.032.png)![ref5]![ref6]![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.033.png)![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.034.png)![ref7]**

8. **References ![ref8]![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.062.png)![ref5]![ref1]![](Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.063.png)![ref2]![ref2]![ref7]**
- [Flutter - Build apps for any screen ](https://flutter.dev/)
- [dart - How to make a payment by credit card Visa and Mastercard on flutter? - Stack Overflow ](https://stackoverflow.com/questions/60976045/how-to-make-a-payment-by-credit-card-visa-and-mastercard-on-flutter)
- [Flutter Tutorial - GeeksforGeeks ](https://www.geeksforgeeks.org/flutter-tutorial/)
- [Flutter UI - Beautiful UI components for Flutter ](https://flutterui.design/)
17 

[ref1]: Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.005.png
[ref2]: Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.007.png
[ref3]: Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.011.png
[ref4]: Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.020.png
[ref5]: Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.021.png
[ref6]: Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.022.png
[ref7]: Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.024.png
[ref8]: Aspose.Words.f0911d1f-9fbd-4b4b-920b-a9348b851b84.042.png
