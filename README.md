# basic-stripe-wordpress-plugin
Its the Basic Stripe plugin i have created which can be modified according to the need of the end user


First install the plugin or move the plugin to the wordpress plugin directory.

Once done activate the plugin from wordpres plugin menu.

After activating ..go the 'StripePayment Setting' section from side bar( If not visible after activating plugin, refresh the page)

Place your stripe live and test key and select the mode.

Create a new page and place this '[StripPaymentGateway]' shorcode.

Save it and view it a 'Paynow' button should appear.

Click it to initiate it

Stripe test credentials_>
Card_>4242 4242 4242 4242
Date_>Any date  > present date
CVC_>3-digit any number

Once done you will receive a message regarding the order and a mail.

Depend upon where you are running the plugin the mail will get sent if you are on local machine mails won't get sent..as you need to set SMTP and place your google credentials in order to sent mail via your google account. 
Modify this file in 'model/PaymentGatwayeModel.php' line number 138. Uncomment that section after filling it properly ( Read instruction their)

Also make sure Curl is installed in system if on local machine..otherwise payment request won't  sent.

You you have any Question regarding this please let me know..


