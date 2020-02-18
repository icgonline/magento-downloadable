# magento-downloadable
Fixes an issue with Magento 1.9.x with downloadable products

In certain circumstances Magento doesn't allocate a customer_id to a downloadable product.
This happens when the customer registers at the same time as they place the order.

This function changes the cross reference to order number.
