# WooCommerce Plugin for ShipperHQ

## Introduction

This plugin is for the interface to the ShipperHQ platform, the most intelligent rating platform in the world, trusted by 1000's of customers.

The Woocommerce integration supports:

* Support for over 50 Carriers (see list below)
* Advanced Rules Engine with support for shipping promotions, discounts, surcharges, prevent conditions, etc
* Shipping via Multi-Origin/Multi-Vendor
* Nearest Warehouse/Fewest Warehouse Algorithms
* Intelligent Dimensional Packing
* Estimated Time in Transit
* Custom Table Rates with ability to change rates down to a Product level
* Dynamic Address Type lookup
* Rate Shopping - show only the cheapest rates
* and much more

Carriers supported include:

* UPS
* FedEx
* USPS
* DHL
* Fastway
* Australia Post
* StarTrack
* YRC/Yellow Freight
* Canada Post
* Old Dominion
* Con-way
* Echo
* Estes
* Cerasis
* Gso
* and yours (contact us to discuss)

We also have the most advanced custom table rate solution in the world. This technology installed on tens of thousands of Magento sites worldwide.



## Installation

Firstly sign up for a trial account at [ShipperHQ.com](https://www.ShipperHQ.com). You will need this to obtain your api key/authentication code.

Configure ShipperHQ for your needs. See our [Getting Started Video](http://docs.shipperhq.com/getting-started/) for further information.

1. Download the release into wp-content/plugins/
2. In WordPress activate the Plugin ShipperHQ
3. Navigate to WooCommerce/Settings/Shipping/ShipperHQ
4. Enter api key/authentication code as taken from the ShipperHQ Dashboard

You should now be able to see shipping rates from ShipperHQ on the frontend.  



##  Product Setup

Once the plugin is installed you will a ShipperHQ tab when you edit a product listing. In this you can enter the attributes which will affect the shipping rating, depending on your needs.

In brief they are:

* **Shipping Group** - Similar to Shipping Class in WooCommerce, this specifies a category of products, E.g. BIKES, BEDS, ACCESSORIES, etc. A product can be assigned multiple shipping groups
* **Warehouse** - The set of Warehouses the product is available to be shipped from. If not set the default warehouse setup in ShipperHQ is used
* **Dimensional Rule Group** - Similar to Shipping Groups, but used to segment your dimensional rules. E.g. you may have a group called RODS and then you would use this to set the possible boxes for fishing rods in ShipperHQ. A product can only belong to one Dimensional Rule Group
* **Ships Separately** - Check this if the product ships in its own box
* **Freight Class** - The LTL Freight Class. Only applies if you are shipping via LTL and the product doesn't use the default freight class assigned to the carrier.
* **Must Ship Freight** - Used with LTL only. If set will force the cart to ship via LTL Freight depending on rules setup in ShipperHQ.


## Coming Soon

ShipperHQ itself has support for other capabilities that we do not yet have integrated in WooCommerce. If you are interested in these please contact us to discuss:

* Calendar Based Rate Selection
* Store Pickup
* Address Validation
* Split Amazon Style Checkout

