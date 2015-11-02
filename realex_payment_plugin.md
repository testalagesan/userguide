# Payment RealEx Plugin for J2store

#### Introduction

The Payment RealEx Plugin for J2Store to pay online transaction amount for a product.


#### Requirements
	
	PHP 5.2 or higher
	Joomla 2.5 or above
	J2Store 2.7.3 or above

#### Installation
	
	1. Use Joomla installer to install the plugin.
	2. At the backend, go to Extension -> Plugin Manager and open the RealEx(type=j2store).
	3. Enable plugin.
	4. Enter Plugin Params

#### Configuration

**Payment option title:**

If required, enter Option Title. This text will be displayed while listing the payment option.

**Display Image:**

This option used to display payment logo in checkout.

**Payment Type:**

There are two type of payment types:
	
		1. Redirect Method(Hosted):
			It will redirect to RealEx payment form, here user will enter credit card details and make 
			payment.
		
		2. Direct Method:
			It will make payment site itself.

**Merchant Id:**

Your Merchant Id associated with your RealEx Account

**Account Id**

Your Account Id associated with your RealEx Account

**Secret Key:**

Your Secret Key associated with your RealEx Account

**Use Sandbox**

Setting this yes will make the plugin to use the RealEx sandbox server.

>NEVER EVER set this to YES, when your site is live.

**Test Merchant Id:**

Your Test Merchant Id associated with your RealEx Account

**Test Account Id**

Your Test Account Id associated with your RealEx Account

**Test Secret Key:**

Your Test Secret Key associated with your RealEx Account

**Article ID for custom thank you message** 

You can create an Article ID with a message enter its ID here to show it to the customer after completion of the purchase.

**Display text on selection**

The text entered here will be displayed when customer selects this payment method.

You can enter a language constant as a value here if you are using a multi-lingual site and then write a language override. Refer the tips below

>Tip - ONLY FOR MULTI-LINGUAL SITES

For example, enter a language constant:

***J2STORE_TEXT_TO_DISPLAY_ON_SELECTION.***

Now you can go to Joomla admin-> Language Manager->Overrides and create overrides for the language constant in all your languages.

**Display text before payment**

The text entered here will be displayed to the customer at the order summary screen before he makes the payment. 

You can enter a language constant as a value here if you are using a multi-lingual site and then write a language override. Refer the Display text on selection parameter.

**Display text after payment/order**

The text entered here will be displayed to the customer after he makes the payment. 

You can enter a language constant as a value here if you are using a multi-lingual site and then write a language override. Refer the Display text on selection parameter.

**Display text on error in payment**

The text entered here will be displayed to the customer when there is an error in the payment process. 

You can enter a language constant as a value here if you are using a multi-lingual site and then write a language override. Refer the Display text on selection parameter.

**Display text on cancel payment**

The text entered here will be displayed to the customer when he cancels the payment at the gateway (NOT in your site). 

You can enter a language constant as a value here if you are using a multi-lingual site and then write a language override. Refer the Display text on selection parameter. 

#### Support
Still have questions? You can post in our support
forum: http://j2store.org/forum/index.html
