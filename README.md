## Advanced Product Reviews
Advanced Reviews is a great way to build trust in your store and automated follow up e-mails will remind your customers to share their survey with others. Boost your reputation and sales giving them a convenient tool to see, what other shoppers think about the products.

* Comprehensive info right on the product details page
* Get more product reviews by sending reminders to customers 
* Upload multiple images for review
* Represent graphically and in percentage the received reviews 

Compatible With:

* Community Edition version: All 
* Official version: 2.3.4+ (catalog design is not supported)
* Minimum PHP Version: 7.0

## Installation

1. Backup all files and database!

2. Unzip the archive and upload the files on server.

Files that will be replaced on the server:

- admin/includes/languages/english/reviews.php
- admin/includes/modules/dashboard/d_reviews.php
- admin/reviews.php
- includes/languages/english/product_reviews.php
- includes/modules/boxes/bm_reviews.php
- reviews.php

3. Manually make changes.

In admin/includes/application_top.php and includes/application_top.php

At the end of the file add

```php
  include 'includes/functions/reviews.php';  // advanced product reviews add-on
```

4. Open Administration Tool (Backend) in menu Catalog click Reviews Start

5. Install module:

- in menu Modules -> Boxes -> button "Install Module" -> select Reviews -> button "Install Module"

- in menu Modules -> Content -> button "Install Module" -> select Reviews List (group account) -> button "Install Module"

- in menu Modules -> Content -> button "Install Module" -> select Reviews To Product (group product_info_bottom) -> button "Install Module"

- in menu Modules -> Content -> button "Install Module" -> select Review Star Icons (group product_info) -> button "Install Module"
