## Development test for PHP, HTML, XML, Javascript Developer at OMNI.PRO

## Introduction
With this test we want to evaluate your skills in the following areas:

* Optimal use of Adobe Commerce Best Practices
* Optimal use of PHP
* Optimal use of MySQL
* Optimal use of Javascript and preferred libraries
* Medium use of HTML
* Medium use of Git
* Medium use of XML
* Programming best practices

During this test you can follow your personal development process. Please keep in mind that we want to get a product that balances quality and quantity, if you're not capable of finishing this test in its entirety in the given timeframe we still should be able to appreciate your work and skills. Think about this small application as a project that will be maintained and possibly extended in the future by other developers.

## Development
Build a simple Adobe Commerce module with blog functionality (only Admin Panel administration)

The form should have the following fields:
* Title
* Content
* Image
* Email address

It should not be possible to save the post if:
* The email address is invalid or empty
* The title is empty


After submitting a new post or edit the PHP backend will run another validation round:
* It will verify that the email address is equal to a Magento user email that holds the Administrator role.

After validating the post:
* Add a timestamp

From the Magento admin panel
* The existing posts should be visualized
* The posts can be created
* The posts can be edited
* The posts can be deleted

A concise and documented Git history is expected. When the development has been finished a Merge Request should be created in order to notify the technical team that the test is ready to be evaluated. It is only necessary to version the directory that holds the module and not the Magento application. The extension should be auto-installable with the command "magento setup:upgrade".

Good luck!


