<p align="center">
  <img height="350" src="https://github.com/ReqEng-Analysis/Ashlynn_Glitz-Glitter_Boutique/blob/main/Images/AD%20Logo%20Package%201.png">
</p>


# 1. Introduction
This document specifies the business requirements for Ashlynn Glitz and Glitter Custom Boutique.
  ## 1.1 Business purpose
  The organization's primary purpose is to provide the opportunity for others to express their personality and style through custom products. They also aim to offer unique gifts. 
  ## 1.2 Business scope
  Ashlynn is an overall brand that consists of activities under creation, freelance content design, marketing, and photography services. Ashlynn Glitz & Glitter Custom Boutique is a subset of this brand that offers custom products and unique gifts. This document outlines and specifically is focused on the subset of Ashlynn Glitz & Glitter Custom Boutique and their current systems.
  ## 1.3 Overview
  The major internal division that this document is concerned about is Ashlynn Glitz & Glitter Custom Boutique. The main external entity that we are concerned with is providing services and products for customers. The business is responsible for creating products that are designed by the customer. 
  ## 1.4 Definitions 
  Products: Currently include tumblers, pens, earrings, and seasonal items. Defines what is created by the business
  Supplies: Anything to use to create the products.
  Custom: A product that has been designed by the customer or business. 
  Creation: Products are handmade by the business by a custom design using supplies, including but not limited to, glitter, alcohol ink, vinyl, epoxy resin, and rhinestones. 
  ## 1.5 Major stakeholders 
  Major stakeholders include Ashley Denton, also known as Ashlynn, and customers of the business. It is worth noting that some products and supplies are sourced from various suppliers. 


# 2. References
References include Ashley Denton, who is the owner of the business. This also includes the [current business website](https://ashlynndesign.bigcartel.com/) and [Facebook storefront](https://www.facebook.com/ashlynnglitzandglitter). I, the developer and creator of this document, also pose as a resource as I have ordered and experienced working and ordering from the business several times. Because of this, I can provide a customer's perspective of the business and its systems.


# 3. Business management requirements
  ## 3.1 Business environment
  The business environment is primarily online, more specifically e-commerce. However, they often provide occasional in-person sales and participate in vendor events. Because of the specified environmental factors, there are competing businesses that offer the same services. A potential influence on the business and system is the idea that other businesses may have better services and systems that would entice customers to buy from a competitor. Another aspect of the business to consider is the overall cost of creating the products and the offered price. Since most of the company's revenue is from tumblers and their variations, we must take into consideration the cost of the product itself before being customized.
  ## 3.2 Mission, goals, and objectives
  Amplifying life through creativity, the Ashlynn brand’s mission is to always find joy in the creative scheme of life bringing a focus on branding, photography, design, and content creation while educating the future of marketing and media to discover their passion. Objectives include helping small businesses reach their marketing goals and allowing people to show off their personalities.
  ## 3.3 Business model
  The business mission is achieved by providing custom products that incorporate design and content creation. This achievement can be further enhanced by providing a sufficient system to scale the current range of the business and its influence on marketing and media.
  ## 3.4 Information environment
  The overall strategy of the organization should be defined under the goal of providing creative products through design and content creation. The business is in pursuit of providing the utmost quality when it pertains to branding, marketing, and the products that are being sold. The actions of the business should serve as a learning opportunity and analysis of both the future and current trends in marketing and media.  


# 4. Business operational requirements
  ## 4.1 Business processes
  * Customers can browse through previous designs and choose whether they would like a previous design or can generate their own. This generated design is simply a description of what they would like as their design. The majority of designs are documented on the Facebook storefront, but some can also be found on the website.
  * The customers can submit their order on the website or message the business directly to submit their order.
  * Invoices and payment is processed and submitted using Paypal. This invoice is sent to the customer's e-mail address after the products being ordered are specified.
  * After both the payment and designs for the products are submitted, the product is handmade, then shipped/delivered to the customer. 
  * The alternative process is the business creates various products and sells them in person or at vendor events.
  ## 4.2 Business operational policies and rules
  * Both the payment and design for a custom product, that is described by the customer, must be submitted before the product is created.
  * Custom products, that are related to consumption (tumblers and their variations), must be created in a clean environment or cleaned before shipping/delivering to the customer.
  * Shipping fees vary and are applied to orders during payment processing. 
  * The business has the right to ask for permission to change or alter the design given the supplies available or the capability of the employee creating the design on the product.
  * Due to the customized nature of the products, all sales are final, meaning no returns or exchanges.
  ## 4.3 Business operational constraints
  Solo operator, the business manages a small number of orders at a time. There is a small amount of inventory on hand but has a local supplier for the main items. The amount of time the products take to ship varies based on the number of orders, the number of products in an order, and the capacity of the business at a specific time. Customers may also experience longer shipping times for more specialty products. The ordering process for products is not completely automated, it often requires human intervention to ensure that the product can be created by the business based on the design or to simply order the custom products. Due to this, there are no defined time constraints since the business consistently works at varying times.
  ## 4.4 Business operational modes
  In an unsteady state, all products can be ordered by directly contacting the business. Limits are often enacted during seasons where the number of orders received is at a higher rate than normal. For example, products must be ordered before a specified date to ensure that it is delivered by a specified date/time of year.
  ## 4.5 Business operational quality
  The products and output of the business must always attempt to achieve the utmost quality promptly. Based on the mission statement of the organization, the quality of the business's products must be a priority over the speed at which the products are created.
  ## 4.6 Business structure
  The business consists of a single person. The business is under solo operation where only one individual is managing, creating, and dealing with the business and its products.


# 5. Preliminary operational concept of proposed system
  ## 5.1 Preliminary operational concept
  ### a) operational policies and constraints;
  * Both the payment and design for a custom product, that is described by the customer, must be submitted before the product is created.
  * Custom products, that are related to consumption (tumblers and their variations), must be created in a clean environment or cleaned before shipping/delivering to the customer.
  * Shipping fees vary and are applied to orders during payment processing. 
  * The business has the right to ask for permission to change or alter the design given the supplies available or the capability of the employee creating the design on the product.
  * Due to the customized nature of the products, all sales are final, meaning no returns or exchanges.
  * There are no defined time constraints since the business consistently works at varying times.
  ### b) description of the proposed system;
  The system to be created is an e-commerce website that would aid in the automation of ordering and displaying the products of the business in an organized manner. A sufficient system would allow for better marketing and smoother business operations.
  ### c) modes of system operation;
  The system should allow for the ordering and browsing of products. The site should also allow for the business to easily update the products, prices, and other information that is displayed on the site. The customer should also be able to view past orders. The functionality for communicating with the customer should also be assessed and implemented within the system.
  ### d) user classes and other involved personnel; and
  The system will allow for admin, guest, and customer use. The level of permissions would vary by user.
  ### e) support environment.
  The website should be supported on most browsers and the site should be compatible with mobile devices. More specifically, compatibility defines being able to use the site easily on mobile devices.
  ## 5.2 Preliminary operational scenarios
  * Customers will be able to view information regarding the business. They will be able to browse as a guest, create an account and log in, order products, and view past orders.
  * Operators/Maintainers will be able to add products to the site. This includes images of recently designed products or ready-to-ship products that are available. They should be able to add products for sale, change the price of products, and remove products. The site should allow this subset of users to also display any specialty descriptions, such as sales, deals, or highlighting new products.

# 6. Other preliminary life-cycle concepts
  ## 6.1 Preliminary acquisition concept
  Before developing the system, information and input should be collected from existing customers and stakeholders through elicitation to have a better idea of the specifics of how the site and its features should be implemented. After this, analysis of these results is essential in specifying detailed requirements for the site to be created in a timely and specified manner. Constant contact should be established with the major stakeholders to ensure that the product is clearly defined throughout its production. The design and usability of the system should be emphasized throughout the entire process.
  ## 6.2 Preliminary deployment concept
  The site should be introduced into operations when it is functional enough to continue business operations. This includes ordering capabilities and admin editing the site to add and edit products. Specific features, such as communication with customers on the site, customer login, and other features should be implemented and updated in iterations after the intial release.
  ## 6.3 Preliminary support concept
  Since this is a site for a small business, there is no dire need for a structured support system. The business is responsible for checking that the system is running as defined. If any issues may arise, the developers can be outsourced to fix the issues that are present. Customer support can also be outsourced to another company if needed, but cost and need must but assessed before acquisition. 
  ## 6.4 Preliminary retirement concept
  The system should only be retired if the business were to also be closed. The other case would be if the system is no longer sufficient for the functions of the business and would need to be redeveloped from scratch to coincide with the business's operation and mission. The system should be created with scaling in mind.


# 7. Project Constraints
Because of the nature of the small business, there is a limited budget for creating the site. The site must also be ready for its initial release within 5 months to allow for a shift into the new e-commerce site. There is no need to build a website that deals with the same traffic as a big corporation, but it is important to consider the opportunity for scaling. The cost of the system should be relatively low as the system does not need many developers and would only need the capabilities of storing site data and a website domain (which is already owned by the business). Because of the above constraints, some features may be basic and minor bugs may exist on the initial release.


# 8. Appendix
  ## 8.1 Acronyms and abbreviations
  N/A
