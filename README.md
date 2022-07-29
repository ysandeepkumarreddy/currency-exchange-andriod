# CurrencyExchange
This is an android app that exchanges currency of different countries.



## Introduction

* Android is a mobile operating system (OS) currently developed by Google, based on the Linux kernel, and designed primarily for touchscreen mobile devices such as smart phones and tablets. Android's user interface is mainly based on direct manipulation, using touch gestures that loosely correspond to real-world actions, such as swiping, tapping, and pinching, to manipulate on-screen objects, along with a virtual keyboard for text input. In addition to touchscreen devices, Google has further developed Android TV for televisions, Android Auto for cars, and Android Wear for wrist watches, each with a specialized user interface. Variants of Android are also used on notebooks, game consoles, digital cameras, and other electronics. Initially developed by Android, Inc., which Google bought in 2005, Android was unveiled in 2007, along with the founding of the Open Handset Alliance – a consortium of hardware, software, and telecommunication companies devoted to advancing open standards for mobile devices. As of July 2013, the Google Play store has had over one million Android applications ("apps") published, and over 50 billion applications downloaded. An April–May 2013 survey of mobile application developers found that 71% of developers create applications for Android, and a 2015 survey found that 40% of fulltime professional developers see Android as their priority target platform. 

* Currency is a primary medium of exchange within the times, having way back replaced bartering as away of trading goods and services. Due to Globalization, there is a tremendous growth of businesses nationally as well as internationally. So, with different nations, they have their different currency values. So, to deal with these fluctuating currency rates, having a mobile application with the latest exchange rates also with a converter which can be accessed anytime anywhere is very helpful. Currency deals with the development of an android-based application for the conversion of different currencies along with getting the latest exchange rates. The main aim of this proposed application is to provide all the features in a single place, accessible anytime anywhere. The application consists of the following modules, namely:(i) Converter (ii)Chart (iii)News(iv)Payment Gateway. The data is fetched through API and the Chart is displayed using the MPAndroidChart library. This application can be used by international tourists, forex traders, and analysts.

## System Requirements

* The most common set of requirements defined by any operating system or software application is the physical computer resources, also known as hardware. 
* CPU	                     :	           x86_64 CPU architecture; 2nd generation Intel Core or newer
* Cores                        :           5th generation Intel core                      
* RAM                        :            8 GB RAM or more
* Graphics                   :            Intel Integrated Graphics or AMD Equivalent
* Secondary Storage   :           8 GB minimum (IDE + Android SDK   + Android Emulator)
* Display Resolution  :            1280 x 800 minimum screen resolution

## Project Desgin

The project titled “Currency Exchange” aims at developing an android based application for the user to see exchange rate between currency. It is implemented using XML and JAVA codes in Android Studio Platform.
We have used relative layout for the Edit text and send button. When the user selects that exchange rated between the two currencies i.e., when user presses result button the currency rate will be displayed

## XML Desgin
<p align="center">
  <img src="https://github.com/ysandeepkumarreddy/currency-exchange-andriod/blob/main/imagesgit/Picture1.png" width="500" height="400" />
  
  for xml file [mainactivity.xml](https://github.com/ysandeepkumarreddy/currency-exchange-andriod/blob/main/app/src/main/res/layout/activity_main.xml)
</p>

## Implementation

### Main Activity.java: 

It displays the home page of expense tracker where we can set the limit of our expenses so that we can enter the daily expenses which will be recorded and this helps in keep track of our spendings. 

### About Activity.java: 

It displays the about page in the tab we can see introduction and contact details where we can also check the version of app and value proposition and official mailed where we can contact them. 

[mainactivity.java](../blob/main/app/src/main/java/com/example/firstapplication/MainActivity.java)

## Testing

| Case ID     | Case Name     | Description | Status |
| ------------- |:-------------:| -----|-----:|
| 1 | Global support     | Different type of currency will be available from all around the world in different rates and prices are updated at real time market | `PASS` |
| 2 | Result     | Currency will be displayed as soon as the result button is clicked |   `PASS` |
| 3 | Different Currency | User will be able see the exchanged of currency in app available within API connected service |   `PASS` |
| 4 | Online Data | Real-time calculations of currency is generated and displayed in result |   `PASS` |
| 5 | Sharing | User will be able to share currency exchange values to other users. |   `PASS` |

## Results

<p align="center">
  <img src="https://github.com/ysandeepkumarreddy/currency-exchange-andriod/blob/main/imagesgit/image%20(1).png"  height="500" />
  <img src="https://github.com/ysandeepkumarreddy/currency-exchange-andriod/blob/main/imagesgit/image%20(2).png"  height="500" />
