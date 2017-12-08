For my solution:

1. /models/website_sale_info.py: I added one2many field in the website object to be able to get information 
	of website_sale_info object from the website.

2. /views/template.xml: I added the button from which i will display my pupop contains the information from 
	website_sale_info based on the specific delivery and payment.
	
3. /static/src/js/sale_info.js: I added onclick functions in witch i defined what happend after clicking
	the button in the delivery and the payment which is to dynamically display a template based on the
	specific delivery or payment order.
	
	
PS: I marked my code with comments:
	the beginning of the comment start with "Ibtissem Added" and end with "End Ibtissem modification" 
	to facilitate the search for you.
