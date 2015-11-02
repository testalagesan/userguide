# Payment RealEx Plugin for J2store

#### Introduction

	The Payment RealEx Plugin for J2Store to pay online transaction amount for a product.

#### Requirements

The minimum requirements for this plugin to be installed is as follows:
* PHP 5.2 or higher
* Joomla 2.5 or above
* J2Store 2.7.3 or above

#### Installation
	
	You can install the plugin through the standard Joomla installer.

#### Configuration

**Payment option title:**

	 If required, Enter Option Title. This text will be displayed while listing the payment option.

**Display Image:**

  This option used to display payment logo in checkout.

**Payment Type:**

  There are two type of payment types:
		
		1. Redirect Method(Hosted):
		    It will redirect to RealEx payment form, here user will enter credit card 	details and make payment.
		
		2. Direct Method:
			It will make payment site itself.

**Merchant Id:**

	Your Merchant Id associated with your RealEx Account

**Account Id:**

	Your Account Id associated with your RealEx Account

**Secret Key:**

  Your Secret Key associated with your RealEx Account

**Use Realex Sandbox:**

Setting this yes will make the plugin to use the RealEx sandbox server.

>NEVER EVER set this to YES, when your site is live.

**Test Merchant Id:**

	Your Test Merchant Id associated with your RealEx Account

**Test Account Id:**

	Your Test Account Id associated with your RealEx Account

**Secret Key:**

  Your Test Secret Key associated with your RealEx Account

**Geo Zone**

By selecting a Geozone here, you can restrict customers of a selected Geo-regions from viewing the payment method. Choose all Geozones to show the payment method to customers of all Geo-regions.

**Display text on selection**

The text entered here is displayed when a customer selects this payment method. You can enter a language constant as a value here, if you are using a multi-lingual site and then
write a language override. Refer the tips below:

>**Tip - ONLY FOR MULTI-LINGUAL SITES**

For example, enter a language constant:
**J2STORE_TEXT_TO_DISPLAY_ON_SELECTION**

Now you can go to Joomla admin-> Language Manager->Overrides and create overrides for the language constant in all languages.

**Display text before payment**

The text entered here is displayed to the customer at the order summary screen before he makes the payment.

You can enter a language constant as a value here, if you are using a multi-lingual site and then write a language override. Refer the **Display text on selection** param.

**Display text on error in payment**

The text entered here is displayed to the customer when there is an error in the payment process.

You can enter a language constant as a value here if you are using a multi-lingual site and then write a language override. Refer the **Display text on selection** param.

**Display text on after payment**

The text entered here will be displayed to the customer on after payment in the payment process.

You can enter a language constant as a value here if you are using a multi-lingual site and
then write a language override. Refer the **Display text on selection** param.

**Debug Payment**

This option used to enable/disable log file.

**Payment Button Text**

The text of the payment button. The button will be displayed at the final checkout step.

#### Support

Still have questions? You can reach us in http://j2store.org/forum/index.html.

Thank you for using our extension.
