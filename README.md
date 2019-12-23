# TravelApp
:taxi: :bus: :minibus:

A Proof-of-concept "Uber-like" app with live location updates.
# :beetle: Bugs List:
* Authentication works both ways and is not validated i.e. A Drivers email & password will also work for Customer.
* Driver & Customer Login Screens:  App Crashes if no email and password are filled in and the user just clicks on "REGISTRATION".
* If logged in as Customer:  Double tapping "CALL DRIVER" will crash the app.
* "I'm a Customer" & "I'm a driver" screens: Pressing back on test device closed the entire app instead of returning to previous screen.
* Paypal Payouts dont work & so have been commented out in code.


Made using Android Studio, Firebase, Google Maps API, PayPal API


APK can be found under: android/app/build/outputs/apk/debug
Feel free to clone, improve and open issues on :octocat: GitHub if you find any bugs other than the ones mentioned above.

I'll maintain this app if demand increases.


:iphone: Tested on *Galaxy J7 Prime* running *LineageOS 15.1*.
