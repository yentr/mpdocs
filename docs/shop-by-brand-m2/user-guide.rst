
By Mageplaza you can find many extensions that will help online stores improve customer search such as `Magento 2 Layered Navigation`_ and `Magento 2 Advanced Search`_ extension, and `Magento 2 Shop by Brand`_ extension is also one of such great tool. Similar to the navigation, Shop by Brand allows filtering by product attributes, but they are neither color or material or any physical features of the product. The plugin bases on brands (manufacturers) the products are made by. 

In this helpful Mageplaza documentation, you will achieve the guide of **How to use** and **How to config** on the frontend and backend of Shop by Brand Magento 2 module. 


I. How to use 
---------------

As soon as installing Shop by Brand completely, your customers can easily search all products under the favorite brands in your inventory. Especially, on its interface, there are two ways of shopping by brand: **Search Box** and **Alphabet Search**. You will follow these ways here.

1. Search Box
^^^^^^^^^^^^^^^^^^^

The search box on Magento 2 Shop by Brand has some functionalities that are alike to Magento 2 Ajax Search by Mageplaza. In the box, entering some words of the brand name and achieving the drop-down results instantly on the current page.

.. image:: https://i.imgur.com/wNIKZCz.gif

The brand results come with Brand Logo, Brand Name, and Brand Description. 

.. image:: https://i.imgur.com/xNsZsK0.png

2. Alphabet Search
^^^^^^^^^^^^^^^^^^^^^^^

Alphabet Search, placed under Search Box, is represented including "Show All" and the alphabets. Depending on the first characteristic of the brand name, the user will tap on the respective button.

.. image:: https://i.imgur.com/dybAloX.gif

II. How to config
------------------

Login to the backend of Magento 2 Shop by Brand. To cover full of the configuration as an administrator, you need to follow 3 parts: 

* Settings
* Create new brand
* Assign brand to product

1. Settings
^^^^^^^^^^^^^^^^^^^

**Settings** tab is a bunch of the basic configuration you need to set up firstly. 

* Go to `MAGEPLAZA > Shop by Brand > Configuration`
* Expand **General** section, please do the following:

  * `Enable` the module when choosing "Yes" to allow customers shop by brand
  * From the existing list of the product attribute, set `Brand Attribute` to the correct choice. In this guide, *manufacturer* is the option you have to select

    .. note:: To create a new product attribute under "Brand" name, please read `How to Create Product Attribute in Magento 2`_ topic in Magento 2 Tutorial by Mageplaza.

  * Enter `Brand Link Title`.
  * Choose the page to display Brand Link in `Show Brand Link In`.

.. image:: https://i.imgur.com/yj64Pfu.png

* Expand **All Brands Page Settings** section and do the following:

  * Enter `Brand route`, if passing it, the default (brands) is applied
  * Enter `Brand list name` or leave it as the default (Brands)
  * Choose to display Brand Logo only or display Logo and Label in `Display Option`
  * Select relevant color for the `Style Color` of Shop by Brand's interface
  * Set to `Show Brand Description` or not in the Brand Page
  * Add `Custom Css` for your own style.

.. image:: https://i.imgur.com/Z7wUVuc.png

  * Expand **Brand Search Settings** section,

    * Enable search box by setting "Yes" in `Show Search Block`
    * Set `Min chars`, that should be usually 1 or 2
    * Limit `Maximum Query Result` that match with the given request
    * Make brand image visible on the search by selecting "Yes".

.. image:: https://i.imgur.com/GgosIyw.png

  * Expand **Feature Brand Settings** section,
  
    * Choose to `Show Feature Brands` or not
    * Enter `Title` for feature brands or leave it as default (Feature Brands)
    * Choose `Display Information` of feature brands, Logo Only or Logo and Label
    * Use `Embedded Code` to show feature brand block in any place you want.
    
.. image:: https://i.imgur.com/uMrWGCA.png

* Click to expand **Brand Information**,

  * Choose `Default Image` for Brand. If passing, the product placeholder default image will be used.
  * Set `Default Block`
  * Choose to `Show Brand Image On Brand Page`, `Show Brand Description On Brand Page`, and `Show Brand Static Block On Brand Page` or not.
  
.. image:: https://i.imgur.com/GX7FMHY.png

2. Create new brand
^^^^^^^^^^^^^^^^^^^^^^

* On the Admin Panel, `Store > Attributes > Product`.
* Under **Attribute Code** column, search and choose "manufacturer", you will navigation its workplace.
* All brands are listed under **Manage Options** section, click on **Add option** on the bottom of the list, right after, a new row will appear.
* Click on `Save Config` to save new brand.
* Tap **Setting** to open the "Brand Information" page for configuration.

.. image:: https://i.imgur.com/lCHol98.gif

* Under **Brand Information** section,

  * Set `Page Title` for the new brand
  * Create **URL Key**
  * Upload `Brand Image` from your computer
  * Set the brand to be displayed on featured brand slider or not in `Featured` field
  * Enter `Short Description` (appear on the search result) and `Description` (appear on Brand Listing) 
  * Choose the `CMS Block` to show brand as a static block on anywhere of your page. You can disable it by leave it blank.

* Expand **Meta Information** section, you can complete all fields for your better SEO, including:

  * Meta Title
  * Meta Keywords
  * Meta Description

* `Save Brand` to ensure that the configuration for the new brand is successful.

  .. note:: For the existing brands, you can edit their information via **Setting** button.

3. Assign product to brand
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This guide helps you classify what brand a product is made by.

* On the Admin Panel, `Product > Inventory > Catalog`.
* Select an exact product you want to assign, and open `Edit` mode under **Action** column.
* On the settings page of the product, you will see ` Manufacturer` field that allows assigning a corresponding brand to that product.

.. image:: https://i.imgur.com/XxDH9n2.png

* `Save` the change to complete the brand attachment.
* When finish all, the brand logo will display on both Brand Listing Search and the product detailed page of the assigned product.

On Brand Listing
```````````````````

.. image:: https://i.imgur.com/4rGgrJF.png

On Product Page
`````````````````````

.. image:: https://i.imgur.com/Cs7XSXT.png

.. _Magento 2 Shop by Brand: https://www.mageplaza.com/magento-2-shop-by-brand/
.. _Magento 2 Layered Navigation: https://www.mageplaza.com/magento-2-layered-navigation-extension/
.. _Magento 2 Advanced Search: https://www.mageplaza.com/magento-2-search-extension/
.. _How to Create Product Attribute in Magento 2: https://www.mageplaza.com/kb/how-to-create-product-attribute-magento-2.html
