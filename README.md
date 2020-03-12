# Magento 2 FAQ

This module adds an easy way to use FAQ section to your Magento store with jQuery Accordion. In this module, admin can add and update FAQ. Admin can also create FAQ group with group icon. Admin can add widgets, blocks, images etc. in FAQ answer with wyswing editor.

# Magento Marketplace

https://marketplace.magento.com/mageprince-module-faq.html


# New Features

- Show all FAQ on CMS page and static block
- Show FAQ by group on CMS page and static block
- Load FAQ by ajax on group selection on the frontend
- Custom FAQ URL

<b>Check full description and user guid on <a href="https://marketplace.magento.com/mageprince-module-faq.html">Magento Marketplace</a></b>

# Use below code for CMS page and Static Block

<b>1. To show all FAQ</b>

<code>{{block class="Mageprince\Faq\Block\Index\Index" template="Mageprince_Faq::faq_main.phtml" show_group_title=1 show_group=1 page_type="scroll"}}</code>

<b>2. To show FAQ by group</b>

<code>{{block class="Mageprince\Faq\Block\Index\Index" template="Mageprince_Faq::faq_main.phtml" group_id=1 show_group_title=1}}</code>

# Installation Instruction

* Copy the content of the repo to the Magento 2 app/code/Mageprince/Faq
* Run command:
<b>php bin/magento setup:upgrade</b>
* Run Command:
<b>php bin/magento setup:static-content:deploy</b>
* Now Flush Cache: <b>php bin/magento cache:flush</b>


# Contribution

Want to contribute to this extension? The quickest way is to <a href="https://help.github.com/articles/about-pull-requests/">open a pull request</a> on GitHub.

# Support

If you encounter any problems or bugs, please <a href="https://github.com/mageprince/magento2-FAQ/issues">open an issue</a> on GitHub.


# Frontend

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Faq/front-page.jpeg" height="400"/>

# FAQ Content
<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Faq/font-page-faq.png" height="800"/>

# FAQ on CMS page

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Faq/CMS-page.png" height="400"/>

# Configration

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Faq/configuration.png" height="400"/>

# Code to display FAQ on CMS page and Static Block

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Faq/configuration-cms.png"/>
