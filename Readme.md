# Buba'le MakeUp

Buba'le is an android app that allows a user to create orders and pay for products in a virtual e-commerce shop. The app utilizes Back4app for the back-end operations.

Time spent: close to 20 hours spent in total

## User Stories

The following functionality is implemented om the first release of the app:

  - [x] User can create a new user account
  - [x] User can retrieve an existing account password using the registered e-mail address.
  - [x] User can make new orders.
  - [x] A basic seacrch engine is implemented to search for products that contains a string in its name (case sensitive)  
  - [x] User can modify orders in the interactive cart before checking out
  - [x] User can pay dor the generated order using PayPal system (due security concerns credit cards will only be added in future releases)
  - [x] The App will check if the user defined a shippement address in the profile (if not, the app won't allow payments)
  - [x] User can fill a contact form and send comments to "Buba'le" (the selling shop) using the home section in the App
  - [x] User can update profile information (e-mail can not be modified, this is for the App to keep track of account activity)
  - [x] User can see previous orders: the status (PAID, SHIPPED, COMPLEATED) and the order number for future inqueries.   


The following features will be implemented in the next release:

- [ ] Migration to a dedicated MySql server.
- [ ] Improved search engine. 
- [ ] HTML e-mails to replace the basic text based emails.
- [ ] Forum section for product reviews.
- [ ] Improved profile functionalities.
- [ ] Fidelity program and dicounts sytems based on points and vouchers. (code already existing, to be implemented on the new server)
- [ ] Live chat.
- [ ] Persistent shopping cart with "save for later" option.
- [ ] use of credit cards (using Paypal platform for improved security).
- [ ] General UI and efficiency improvements.
- [ ] Data encryption and password hashing to improve security.


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/HIPERION2021/BubaleApp3/blob/master/Bubale.gif' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Please note, the App currently points to my PayPal Bussiness SandBox Account. The app can be set to "Live" (real transactions) although not recommended at this stage.
The for e-mails the App uses a dedicated e-mail account bubadevelopment@gmail.com -  the emails go from and to that same account 
After any purchase the user will recieve an email in his/her registered e-mail address letting him know the order has been paid (regardless of the app using SandBox accounts). 

## Open-source libraries used

- [PayPal] PayPal intelligent button integration (rendering option)
- [JavaMail] https://javaee.github.io/javamail/#Download_JavaMail_Release
- [Parse] com.github.parse-community:Parse-SDK-Android:1.18.5
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Esteban Luques]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.