# Change log

All notable changes to this project will be documented in this file. This change log follows the conventions of [keepachangelog.com](http://keepachangelog.com/).

# [1.351.0] - 2021-08-19
### Added
- Added new warehouse administrator.


# [1.350.6] - 2021-08-17
### Fixed
- Fixed error when updating a withholding if the support document date is incorrect.
- Fixed error when getting the information of a client in accounts receivable report.


# [1.350.5] - 2021-08-12
### Fixed
- Fixed account owner id type generated in batch file for recurring debit.


# [1.350.4] - 2021-08-06
### Fixed
- Fixed error when recording a payment with Stripe if the invoice has more than one customer email.
- Fixed error when disabling a payment method.


# [1.350.3] - 2021-08-05
### Changed
- Enabled to save account owner identification and name when registering for recurring debit.


# [1.350.2] - 2021-08-04
### Fixed
- Fixed error in accounts receivable report when getting the information of a client.


# [1.350.1] - 2021-08-02
### Fixed
- Fixed error when disabling a payment method that caused it to be deleted in the two configured environments.
- Fixed error when configuring a payment method.


# [1.350.0] - 2021-07-30
### Added
- Added info modal about referrals program use.


# [1.349.3] - 2021-07-27
### Fixed
- Fixed error when saving an invoice with withholdings values.
- Fixed error when recording a payphone payment, it now supports correctly idempotency.


# [1.349.2] - 2021-07-23
### Fixed
- Fixed stripe payment properties.


# [1.349.1] - 2021-07-21
### Added
- Added publishable key to stripe credentials.


# [1.349.0] - 2021-07-21
### Added
- Added stripe to the list of payment methods for invoice.


# [1.348.0] - 2021-07-20
### Added
- Added help information about referral state in referral section.
- Deleted referral prize state column in referral section.
- Added support in datatable component to add help tooltips in headers.


# [1.347.0] - 2021-07-19
### Added
- Improves the option to import received documents.


# [1.346.1] - 2021-07-15
### Fixed
- Fixed overrided reponse variable on register referral invocation.


# [1.346.0] - 2021-07-12
### Added
- Added PayPhone to the list of payment methods for invoices.


# [1.345.4] - 2021-07-07
### Fixed
- Fixed error when creating a quote, the sequence is not as expected.

### Added
- Added sku product when searching and adding an item in quotes section


# [1.345.3] - 2021-07-07
### Fixed
- Fixed error in debit order section. Pagination is working correctly now.


# [1.345.2] - 2021-07-06
### Fixed
- Fixed error when issuing an invoice or credit note, if status is not autorized inventory transaction is generated anyway.


# [1.345.1] - 2021-07-05
### Fixed
- Fixed wrong argument name in register referral function.

# [1.345.0] - 2021-07-02
### Added
- New Referrals program section on datil panel.
- Form to invite contacts on referrals program section.
- Referrals list on referrals program section.
- DatilOS services to invite, list, register referrals.

# [1.344.4] - 2021-06-30
### Fixed
- Fixed error in batch issue section for connect accounts, the option to download the report was not displaying information.
- Fixed error in credit note batch issue, the option to see credit notes belonging to a batch was not displaying information.
- Fixed error when issuing documents.


## [1.344.3] - 2021-06-24
### Fixed
- Fixed error when canceling an adjustment transaction.
- Fixed error when filtering purchases settlements and credit notes by batch.


## [1.344.2] - 2021-06-24
### Fixed
- Fixed credit validations allowing invoices being created when the credit exceeds the invoice's balance.


## [1.344.1] - 2021-06-22
### Fixed
- Fixed download feature when the custom template feature flag is enabled


## [1.344.0] - 2021-06-21
### Added
- Added option to issue batch invoices for connect accounts.


## [1.343.0] - 2021-06-18
### Added
- Process to import Banco Pichincha debit transactions.


## [1.342.0] - 2021-06-16
### Added
- Added field to specify payment method in invoices with credit


## [1.341.2] - 2021-06-16
### Fixed
- Makes item "codigo_auxiliar" field in purchase settlements not required.


## [1.341.1] - 2021-06-15
### Fixed
- Makes supplier address field in purchase settlements not required as it should be.


## [1.341.0] - 2021-06-15
### Added
- Added option to issue batch purchases settlements.


## [1.340.5] - 2021-06-15
### Fixed
- Displays error message when issuing a document in batch.
- Fixes error when filtering by sales representative in sales report.


## [1.340.4] - 2021-06-14
### Fixed
- Improves perfomance in the sales report


## [1.340.3] - 2021-06-12
### Fixed
- Added restrictions when accessing the sales report
- Fixed error when exporting the sales report.


## [1.340.2] - 2021-06-11
### Fixed
- Fixed error when filtering in the sales report.


## [1.340.1] - 2021-06-11
### Fixed
- Fixed sales report, discounts were not being considered and it always was filtering by test environment.


## [1.340.0] - 2021-06-10
### Added
- Added customer, product, sales representative and category filter in the sales report.

### Fixed
- Fixed error in sales report.


## [1.339.2] - 2021-06-10
### Added
- Added category when downloading the sales by items report.


## [1.339.1] - 2021-06-09
### Fixed
- Fixes bug in generated debit account file.


## [1.339.0] - 2021-06-08
### Added
- New option to generate bank account debit orders.


## [1.338.1] - 2021-06-07
### Fixed
- Fixed error when issuing a credit note with items with and without warehouse, inventory transaction was not generated.


## [1.337.14] - 2021-06-05
### Fixed
- Fixed error when issuing a credit note, inventory transaction was not generated.


## [1.337.13] - 2021-06-03
### Fixed
- Fixed error when issuing an invoice with sales representative.


## [1.337.12] - 2021-06-02
### Added
- Added salesrep when issuing an invoice via API.

### Fixed
- Fixed error when paying an invoice.


## [1.337.11] - 2021-05-28
### Fixed
- Fixed error when import received receipts.


## [1.337.10] - 2021-05-27
### Fixes
- Fixed bug when listing documents with wrong filter parameters


## [1.337.9] - 2021-05-27
### Changes
- Reverts shadow-cljs version.


## [1.337.8] - 2021-05-26
### Changes
- Updates shadow-cljs version.


## [1.337.7] - 2021-05-25
### Fixed
- Fixed bug when issuing invoices with reimbursements issue date in ISO format.


## [1.337.6] - 2021-05-25
### Fixed
- Added validation to avoid uploading unsupported file in the batch issuance section.


## [1.337.5] - 2021-05-20
### Fixed
- Fixed error in withholding batch.


## [1.337.4] - 2021-05-17
### Changes
- Adds status code to get document REST API endpoint.
- Fixed email delivery tests.


## [1.337.3] - 2021-05-17
### Fixed
- Fixes New Sales report encoding.
- Fixes New Sales report model.


## [1.337.2] - 2021-05-15
### Fixed
- Fixes New Sales report filter queries.
- Fixes New Sales report model.


## [1.337.1] - 2021-05-14
### Changes
- Changes default value of the rounding method for withholdings. Now it is ROUND_HALF_UP to wittholdings.


## [1.337.0] - 2021-05-14
### Added
- Added first version of the new sales report


## [1.336.1] - 2021-05-14
### Fixed
- Fixed error when importing contacts. Now it saving additional information and contact type.
- Fixed error when exporting contacts. Missing mobile phone number, additional information and contact type.


## [1.336.0] - 2021-05-12
### Added
- Added restriction by point of sales for user with salesrep and warehouse keeper role.
- Fixed error when importing xml.


## [1.335.5] - 2021-05-11
### Fixed
- Fixed SuspiciousOperation error when request is ajax.
- Fixed error in Location series validation.


## [1.335.4] - 2021-05-11
### Fixed
- Fixed error when saving or editing receipts.
- Fixed error when cost is a large value.


## [1.335.3] - 2021-05-10
### Fixed
- Fixed bug in issuing and reissuing endpoints where a user could create a document with a date with an invalid year.


## [1.335.2] - 2021-05-10
### Fixed
- Fixed error when sending a email.
- Fixed error in email validations in Tax profile form, Location Form.


## [1.335.1] - 2021-05-07
### Fixes
- Fixes batch issue UI


## [1.335.0] - 2021-05-06
### Added
- Added option to issue batch credit notes.


## [1.334.0] - 2021-05-04
### Added
- Added option to see documents associated to a batch.
- Added option to export the batch source file.


## [1.333.5] - 2021-05-04
### Changes
- Changes email delivery lambda to work with python3.


## [1.333.4] - 2021-05-04
### Changes
- Changes styles in sales list to show actions by documents.


## [1.333.3] - 2021-05-04
### Fixed
- Fixed menu error in batch-issue view.


## [1.333.2] - 2021-05-03
### Fixed
- Fixed error in filters to Peru documents.


## [1.333.1] - 2021-05-02
### Fixed
- Fixed error when exporting payments.


## [1.333.0] - 2021-05-02
### Added
- Added date range and status filters for Peru documents.


## [1.332.7] - 2021-04-30
### Fixed
- Fixed error when cancelling purchase invoice.
- Fixed error when editing waybill items.


## [1.332.6] - 2021-04-30
### Fixed
- Fixed error when exporting shippers.
- Separate product sku when exporting stock by items report.


## [1.332.5] - 2021-04-28
### Fixed
- Fixed error in product form.


## [1.332.4] - 2021-04-27
### Fixed
- Fixed error when saving waybill items.


## [1.332.3] - 2021-04-27
### Fixed
- Fixed error when printing document in public view.


## [1.332.2] - 2021-04-27
### Fixed
- Fixed sales service returning wrong URLs in `next` and `pervious` fields


## [1.332.1] - 2021-04-26
### Fixed
- Fixed error when searching products in catalog.
- Fixed error when updating product image.


## [1.332.0] - 2021-04-26
### Added
- Added option to issue batch withholdings.


## [1.331.1] - 2021-04-26
### Fixed
- Fixed error when creating or editing product with a big image.
- Fixed error when printing document.


## [1.331.0] - 2021-04-26
### Added
- Added option to issue batch invoices.


## [1.330.2] - 2021-04-22
### Changed
- Changed Sales API not returning the correct documents when given the `environment` parameter as a number.


## [1.330.1] - 2021-04-19
### Fixed
- Fixed error when signing a document.


## [1.330.0] - 2021-04-12
### Added
- Added category, unit of measurement and description when exporting catalog.


## [1.329.2] - 2021-04-12
### Fixed
- Fixed bug when updating a purchase invoice.


## [1.329.1] - 2021-04-12
### Security
- Fixed unrestricted access to edit the point of sale sequences for another account.


## [1.329.0] - 2021-04-12
### Added
- Added an endpoint to set a document's status to `error`. This endpoint is used by an SNS Subscription


## [1.328.3] - 2021-04-09
### Fixed
- Fixed bug when downloading an empty XML from a doc.


## [1.328.2] - 2021-04-08
### Changed
- Upgraded Django version.


## [1.328.1] - 2021-04-08
### Security
- Fixed unrestricted access to api to get receipts.


## [1.328.0] - 2021-04-06
### Added
- Added option to export catalog in XLS format.


## [1.327.0] - 2021-04-05
### Added
- Added tax included price in the catalog list.

## [1.326.1] - 2021-04-01
### Fixed
- Fixed error when voiding or issuing a credit note with items with track inventory.


## [1.326.0] - 2021-03-31
### Added
- Added tax included price and stock when exporting catalog.


## [1.325.2] - 2021-03-30
### Fixed
- Fixed API sales and purchases endpoints returning wrong `next` and `previous` URLs


## [1.325.1] - 2021-03-30
### Changed
- Replaced `glovo` with `peya` (PedidosYa) in account signup.


## [1.324.2] - 2021-03-25
### Fixed
- Fixed SuspiciousOperation error when request is ajax.


## [1.324.1] - 2021-03-25
### Fixed
- Fixed error when cancelling credit note. Now updates inventory when receipts is signed.


## [1.324.0] - 2021-03-24
### Added
- Added tax included price in stock per items report.


## [1.323.11] - 2021-03-24
### Fixed
- Fixed error when cancelling withholding.


## [1.323.10] - 2021-03-23
### Fixed
- Fixed error when cancelling purchase invoice. Inventory transactions was archiving when cancelling invoice.


## [1.323.9] - 2021-03-22
### Fixed
- Adds endpoints to get purchases invoice and received withholding with legacy information.


## [1.323.8] - 2021-03-22
### Fixed
- Fixed error when voiding a received document.


## [1.323.7] - 2021-03-20
### Fixed
- Fixed error when importing received withholdings and waybills.


## [1.323.6] - 2021-03-19
### Fixed
- Fixed error when importing received receipts.


## [1.323.5] - 2021-03-19
### Added
- Detects new expiration message returned by the signer.
- New invalid certificate error is registered. Previously this error was treated as a
service error.


## [1.323.4] - 2021-03-19
### Fixed
- Fixed error when trying to upload a file.


## [1.323.3] - 2021-03-18
### Fixed
- Activates API key authentication for wallet API


## [1.323.2] - 2021-03-18
### Fixed
- Fixed error when importing received receipts. If the issuer of the receipt is a datil customer then when a receipt is imported a duplicate error appears.


## [1.323.1] - 2021-03-18
### Fixed
- Fixed authentication middleware order for public documents API


## [1.323.0] - 2021-03-17
### Changed
- Enabled public documents API using master API key authentication


## [1.322.2] - 2021-03-12
### Fixed
- Fixed error when issuing a credit note


## [1.322.1] - 2021-03-12
### Fixed
- Fixed error when voiding a sales document


## [1.322.0] - 2021-03-11
### Added
- Added option to reverse document void status
- Fixes received document, now it is void when an issued document is void.


## [1.321.4] - 2021-03-08
### Fixed
- Fixed error when printing or downloading the PDF of a received document, the status was wrong.


## [1.321.3] - 2021-03-08
### Fixed
- Fixed unnecessary balance calculation when exporting purchases invoice.
- Fixed unnecessary balance calculation in accounts payable report.


## [1.321.2] - 2021-03-08
### Changed
- Adds log when creating, editing, deleting contacts.


## [1.321.1] - 2021-03-05
### Fixed
- Fixed bug in purchases invoices, payments aren't displayed even when an issued invoice has payments.


## [1.321.0] - 2021-03-03
### Added
- Added warehouse manager role that allows to view invoices.


## [1.320.1] - 2021-03-03
### Fixed
- Fixed error when recording payment as received.


## [1.320.0] - 2021-03-02
### Added
- Added event to save payments as received when issuer record payments.


## [1.319.6] - 2021-03-01
### Fixed
- Fixed ICE calculation for products with mixed rate ICE in credit notes.


## [1.319.5] - 2021-03-01
### Added
- Added sale price field in inventory stock report.


## [1.319.4] - 2021-02-28
### Fixed
- Fixed purchase invoice subscription.


## [1.319.3] - 2021-02-27
### Fixed
- Fixed payment button in purchase invoice view to show 'pagar' option.


## [1.319.2] - 2021-02-27
### Fixed
- Fixed error when issuing a withholding, purchase invoice balance was not being subtracted.


## [1.319.1] - 2021-02-25
### Fixed
- Fixed reverse url error when ret value is invalid.
- Fixed unnecessary balance calculation in purchases invoice list.
- Fixed an error when reissuing an invoice with a credit's expiration date that is earlier than the issuing date.
- Adds new endpoint to request purchase invoice without items.


## [1.319.0] - 2021-02-25
### Added
- Added a new "Account subscription" attribute to the Intercom company data integration
to help the customer hapiness team rapidly review the account susbcription information.
- New option to the switch to account feature to allow redirection to custom account
sections.


## [1.318.4] - 2021-02-24
### Fixed
- Fixed register inventory button in purchases invoice list.


## [1.318.3] - 2021-02-24
### Fixed
- Fixed filter to list received receipts.
- Adds indexes in 'status_code' field in new tables to received receipts.
- Change DJANGO_REST_PAGE_SIZE default value to 30.


## [1.318.2] - 2021-02-24
### Fixed
- Fixed invoice link when viewing a received withholding and received credit note.
- Fixed issue in Purchase invoice REST service.


## [1.318.1] - 2021-02-24
### Fixed
- Fixed error in receipts status.


## [1.318.0] - 2021-02-23
### Added
- The accounts payable report now gets the invoices with the correct status
- Adds action to cancel receipts received.
- The correct status of the receipts received is displayed.
- The status of the receipts received is correctly exported.
- Adds action to register and cancel purchase invoice payment.
- Related withholding with correct status is displayed and filtered in sales invoices.
- The accounts payable report now gets the invoices with the correct status.
- Saves correct status in new tables when received receipts are imported
- Saves documents as received


## [1.317.1] - 2021-02-21
### Fixed
- Fix a bug when creating a product with too long name.
- Saves the information of fixed price and unit of measure when creating a product from quotes and settlements.
- In cognito migration servicio avoid checking if it is a mail with a regex when the username does not have an '@'.


## [1.316.4] - 2021-02-23
### Fixed
- Fixed error when creating a withholding without support document's date.


## [1.316.3] - 2021-02-22
### Fixed
- Fixed bug when issuing aditional information with a descriptions that contains a leading colon.


## [1.316.2] - 2021-02-22
### Fixed
- Fixed error when issuing a document with an unlimited plan


## [1.316.1] - 2021-02-20
### Fixed
- Fixed error when searching a product.


## [1.316.0] - 2021-02-19
### Added
- Added a limit (1000) to the amount of documents issued in a test environment


## [1.315.7] - 2021-02-19
### Fixed
- Handles image names with unicode chars in the stock report.


## [1.315.6] - 2021-02-19
### Fixed
- Handles empty images in the stock report.


## [1.315.5] - 2021-02-19
### Added
- Added image URL field in stock report download.


## [1.315.4] - 2021-02-18
### Fixed
- Added expected moto version.


## [1.315.3] - 2021-02-11
### Fixed
- Fixed copy and link to bank debit authorization form.


## [1.315.2] - 2021-02-05
### Fixed
- Fixed an error when sending statements via email.


## [1.315.1] - 2021-02-04
### Fixed
- Fixed error in available actions in sales invoices. Now a draft invoice cannot register inventory.
- Adds "contribuyenteespecial" and "informacionadicional" fields when creating contact from new sale invoice.
- Logged error when creating contact in new invoice.


## [1.315.0] - 2021-02-03
### Added
- Adds section to register properties associated with a client.


## [1.314.0] - 2021-02-02
### Added
- Added "agente de retencion" and "régimen de microempresas" attributes when creating copy, waybill and credit note from invoice, and when creating an invoice from quote.

### Fixed
- Fixed error in purchase settlements, the "agente de retencion" and "régimen de microempresas" attributes of the account's tax profile where not considering when creating o editing a purchase settlement.


## [1.313.0] - 2021-02-01
### Added
- Added tax profile section to account settings form. This new section includes "agente de retencion" and "régimen de microempresas" attributes.


## [1.312.6] - 2021-01-29
### Fixed
- Fixed error in company data when statement_url is not in session.


## [1.312.5] - 2021-01-29
### Security
- Removed public key authentication from Django REST framework backed views.

### Changed
- New Statement URL company data property is sent to Intercom
- Usage stats are read from session no need to query the database again.

### Fixed
- Quotes are no longer displayed as received invoices.


## [1.312.4] - 2021-01-25
### Fixed
- Fixed validations when creating or updating shipper information.
- Creates contacts when updating billing emails and contact does not exists.


## [1.312.3] - 2021-01-24
### Fixed
- Fixes error in accounts receivable report.


## [1.312.2] - 2021-01-22
### Fixed
- Fixed item validation in inventory transfer.


## [1.312.1] - 2021-01-21
### Fixed
- Fixed inventory transfer, it was saving wrong cost in input transaction.
- Fixed inventory transfer, it was displaying unknown error (500) when stock is insufficient.


## [1.312.0] - 2021-01-20
### Added
- Adds contact information in data sent to the RIDE.

### Fixed
- Fixed error when product has ICE tax in quote. ICE value was not saving when customer edit product.


## [1.311.5] - 2021-01-18
### Fixed
- Fixed error in subscription section when adding a payment method.


## [1.311.3] - 2021-01-18
### Fixed
- Fixed inventory transfer, it was saving wrong cost in input transaction.
- Fixed validation error when requesting workflow information.


## [1.311.2] - 2021-01-15
### Fixed
- Fixed sales by items report, it was taking a long time.


## [1.311.1] - 2021-01-14
### Fixed
- Fixed ice calculation for products with mixed rate ICE in quotes.


## [1.311.0] - 2021-01-13
### Added
- Added option to register billing emails.


## [1.310.0] - 2021-01-13
### Changed
- Adds client information in data sent to the invoice RIDE.


## [1.309.0] - 2021-01-13
### Changed
- Documents with PRE-AUTORIZADO clearance status, now display AUTORIZADO in the "online"
XML version.


## [1.308.9] - 2021-01-12
### Fixed
- Fixed error when updating an invoice, it was taking too much time.


## [1.308.8] - 2021-01-08
### Fixed
- Fixed the ice calculation to allow decimal numbers in product quantity.


### [1.308.7] - 2021-01-08
### Fixed
- Fixed error when performing inventory adjustment.


### [1.308.6] - 2021-01-07
### Fixed
- Fixed quote item price, is taking the latest sold item price by customer but it's not displaying the catalog price.


### [1.308.5] - 2021-01-07
### Fixed
- Fixed certificate deletion. Now to delete a certificate it is required to make a request with post or delete method.


### [1.308.4] - 2021-01-07
### Fixed
- Fixed an error when trying to issue an incomplete document.


### [1.308.3] - 2021-01-06
### Fixed
- Fixed error when requesting workflow information and Link return 500.


### [1.308.2] - 2021-01-06
### Fixed
- Fixed status filter.
- Fixed email status in document list. It was not displaying.

### Changed
- Displays errors in document list when it was not authorized or with errors.


### [1.308.1] - 2021-01-06
### Fixed
- Fixed error when copying a withholding document


### [1.308.0] - 2021-01-05
### Added
- Added backwards compatibility for Withholdings v2. Support documents' information is now added in the `items` field when requesting withholdings


### [1.307.3] - 2021-01-03
### Fixed
- Fixed document menu.
- Fixed status filter.
- Fixed error in document status update


### [1.307.2] - 2021-01-03
### Fixed
- Fixed error when issuing a document when password has unicode characters.


### [1.307.1] - 2020-12-31
### Fixed
- Fixes stock validation when receipts already have inventory registered.


### [1.307.0] - 2020-12-30
### Changed
- Inventory output transactions are now performed after the document was successfully
signed.

### Fixed
- Prevent invoice XML from changing if it's already being processed.


### [1.306.2] - 2020-12-29
### Fixes
- Adds validation to prevent documents in processing status from being editted via the REST API.


### [1.306.1] - 2020-12-28
### Fixed
- Fixed bug in sales documents list.


### [1.306.0] - 2020-12-26
### Added
- Option to mannually generate an inventory output transaction for sales invoices and
sales credit notes.


### [1.305.1] - 2020-12-24
### Fixed
- Fixed document actions, disables delete, update, void and issue options depending document status.


### [1.305.0] - 2020-12-22
### Added
- Added endpoint to issue batch documents.


### [1.304.0] - 2020-12-22
### Added
- New REST API endpoint to retrieve information of a list of documents.


### [1.303.0] - 2020-12-22
### Changed
- Add parameter in endpoint to get information about receiver and issuer.


### [1.302.2] - 2020-12-21
### Added
- Add endpoint to authorize receipts through Link.


## [1.302.1] - 2020-12-21
### Changed
- New REST API endpoint to retrieve an accounts' certificate information now returns 400 as error code when account does not have certificate.

## [1.302.0] - 2020-12-19
### Added
- New REST API endpoint to retrieve an accounts' certificate information.


## [1.301.6] - 2020-12-19
### Fixed
- Fixed bug with boolean settings.
- Rename forgotten url name in html template.
- Updates link to account settings section in panel.


## [1.301.5] - 2020-12-19
### Changed
- Migrates old edocs settings module to datil-os account settings module.

## [1.301.4] - 2020-12-18
### Fixed
- Fixes permission validations to enable inventory in products.


## [1.301.3] - 2020-12-17
### Fixed
- Changes permission to enable inventory in products.


## [1.301.2] - 2020-12-14
### Fixed
- Fixes style in multi price list when creating or editing a quote.


## [1.301.1] - 2020-12-11
### Fixed
- Fixes bug in contact search when contacts have email in null


## [1.301.0] - 2020-12-10
### Added
- Saves supplier or issuer information when importing a received document from XML.


## [1.300.1] - 2020-12-09
### Changed
- Migrations are compacted to reduce the execution time of the tests.


## [1.300.0] - 2020-12-08
### Added
- Added option that allows to upload SRI file to import received documents.


## [1.299.5] - 2020-12-08
### Fixed
- Fixed api to update product images.
- Fixed message when link to change password has expired.


## [1.299.4] - 2020-12-04
### Fixed
- Fixed bug when importing contacts.


## [1.299.3] - 2020-12-04
### Fixed
- Fixed bug when creating a reimbursement invoice when item has ICE.


## [1.299.2] - 2020-12-03
### Fixed
- Fixed bug when creating quote with items with discounts.


## [1.299.1] - 2020-11-30
### Fixed
- Fixes error when listing custom templates by establishment.
- Fixed error when printing by default and there is an A4 template
- fixed error when sending mail with authorized document and there arenot A4 template.


## [1.299.0] - 2020-11-30
### Added
- Added endpoint to reissue Debit Notes


## [1.298.7] - 2020-11-27
### Fixed
- Fixed error when recording payment from receivable report.


## [1.298.6] - 2020-11-28
### Fixed
- Fixes bug in issue document issue date field. Now the localized date is used as the
default value, previously UTC date was used and the default date in the screen after
7 p.m. Ecuador time next day's date was displayed.
- Added a few lines to the Dockerfile to install timezones.


## [1.298.5] - 2020-11-27
### Fixed
- Fixed recently updated, incompatible react-dates dependencies.


## [1.298.4] - 2020-11-26
### Changed
- Updated base Docker image to a recent Ubuntu version.


## [1.298.3] - 2020-11-26
### Fixed
- Updated and cleaned up Python dependencies.


## [1.298.2] - 2020-11-25
### Added
- Added accounting integration setting.
- Integration setting status is included in emitted SNS events as attributes.


## [1.298.1] - 2020-11-23
### Fixed
- Fixed contacts type filter in contacts list.


## [1.298.0] - 2020-11-23
### Added
- Added contacts type filter in contacts list.


## [1.297.0] - 2020-11-23
### Added
- Added endpoints to get purchase setllements.


## [1.296.4] - 2020-11-20
### Fixed
- Fixed error when creating withholding from purchase invoice, when tax type had variable rate.


## [1.296.3] - 2020-11-19
### Fixed
- Fixed bug when importing contacts.


## [1.296.2] - 2020-11-19
### Fixed
- Fixed payment date for record payment from receivable report.


## [1.296.1] - 2020-11-19
### Fixed
- Change select input to search input in the template configuration registration form in admin.
- Fixed bug in migration service and tests.


## [1.296.0] - 2020-11-18
### Added
- Added option to record payment for some invoices by client.


## [1.295.5] - 2020-11-16
### Fixed
- Fixed price list in quote.


## [1.295.4] - 2020-11-14
### Fixed
- Fixed the style when creating a quote for mobile.


## [1.295.3] - 2020-11-13
### Fixed
- Fixed bug in inventory.


## [1.295.2] - 2020-11-12
### Fixed
- Fixed bug in quotes.


## [1.295.1] - 2020-11-12
### Fixed
- Added sales representative in quotes.


## [1.295.0] - 2020-11-10
### Fixed
- Fixed admin form when inserting new subscription


## [1.294.1] - 2020-11-11
### Added
- Added restrictions in quote beta version.


## [1.294.0] - 2020-11-10
### Added
- Added option to have several templates.
- Added option to select template when printing, downloading or sending a receipt.

## [1.293.3] - 2020-11-10
### Fixed
- Fixed bug when creating invoice from quote.


## [1.293.2] - 2020-11-09
### Fixed
- Fixed bug when importing credit note.
- Fixed bug when creating credit note.


## [1.293.1] - 2020-11-09
### Fixed
- Fixed tests to run simultaneously.


## [1.293.0] - 2020-11-09
### Added
- Added system notifications subscriptions


## [1.292.2] - 2020-11-06
### Fixed
- Fixed bug when creating point of sale, location and business.


## [1.292.1] - 2020-11-05
### Fixed
- Fixed bug when creating an invoice from quote with preset additional information.


## [1.292.0] - 2020-11-03
### Added
- Added option to create withholding from purchase invoice.


## [1.291.5] - 2020-10-30
### Fixed
- Fixed error when updating a purchase settlement


## [1.291.4] - 2020-10-27
### Fixed
- Fixed bug when issuing export invoices by API


## [1.291.3] - 2020-10-26
### Fixed
- Fixed the style of export invoices section


## [1.291.2] - 2020-10-24
### Fixed
- Fixed bug when issuing invoices with item whose quantity is a float


## [1.291.1] - 2020-10-24
### Fixed
- Fixed bug in export invoices


## [1.291.0] - 2020-10-23
### Added
- Added option to manage export invoices


## [1.290.20] - 2020-10-23
### Fixed
- Fixed error when issuing waybills with zero item's quantity


## [1.290.19] - 2020-10-22
### Fixed
- Fixed error's format when issuing an invoice's item that exceeded the allowed length


## [1.290.18] - 2020-10-22
### Fixed
- Fixes error in accounts payable reports.


## [1.290.17] - 2020-10-19
### Fixed
- Fixed incorrect document type when requesting waybills edoc


## [1.290.16] - 2020-10-15
### Fixed
- Fixed bug in the product inventory transactions.


## [1.290.15] - 2020-10-14
### Fixed
- Fixed bug in the product inventory history.


## [1.290.14] - 2020-10-08
### Fixed
- Fixed bug when creating xml representation when invoice has additional discount.


## [1.290.14] - 2020-10-11
### Fixed
- Fixed error in the top items report.


## [1.290.13] - 2020-10-08
### Fixed
- Adds additional information from invoice when generating a waybill or credit note from an invoice.


## [1.290.12] - 2020-10-07
### Fixed
- Fixed bug when copying an invoice without preset additional information.


## [1.290.11] - 2020-10-06
### Added
- Added purchase settlement support document to withholdings.


## [1.290.10] - 2020-10-06
### Fixed
- Fixed bug when switching account.


## [1.290.9] - 2020-10-05
### Fixed
- Fixed an error that deleted the preset additional information when updating a receipt via API.


## [1.290.8] - 2020-10-05
### Fixed
- Improved new inventory transfer button text.


## [1.290.7] - 2020-10-05
### Fixed
- Fixed error when issuing receipts with an a sequence that exceeds the maximum length

## [1.290.6] - 2020-10-03
### Fixed
- Fixed bug when registering inventory from a purchase invoice.


## [1.290.5] - 2020-10-02
### Added
- Added preset additional information when creating credit note from invoice.
- Added preset additional information when creating waybill from invoice.

## [1.290.4] - 2020-10-02
### Added
- Adds option to configure additional information to quotes.
- Added preset additional information for quotes through Web.


## [1.290.3] - 2020-10-01
### Fixed
- Fixes the structure of the inventory transfer view.
- Saves user identifier when an invitation is accepted.


## [1.290.2] - 2020-10-01
### Fixed
- Performance improvements when queriying preset additional information.


## [1.290.1] - 2020-09-30
### Added
- Adds option to configure additional information to purchase settlements.
### Fixed
- Consider the environment type to create and display the additional information.


## [1.290.0] - 2020-09-30
### Added
- Adds feature to configure additional information for all types of documents.

## [1.289.0] - 2020-09-28
### Added
- Adds inventory transfer between two warehouses.


## [1.288.0] - 2020-09-25
### Added
- Added preset additional information for debit note through API and Web.
- Added preset additional information for waybill through API and Web.
- Added preset additional information for credit note through API and Web.


## [1.287.0] - 2020-09-25
### Added
- Added preset additional information for invoice through API.
- Added preset additional information for withholding through API and Web.


## [1.286.0] - 2020-09-24
### Added
- Added preset additional information for purchases settlements through API and Web.


## [1.285.6] - 2020-09-23
### Fixed
- Fixed unit cost in the margin section of the invoice when product doesn't have unit price.


## [1.285.5] - 2020-09-23
### Fixed
- Fixed unit cost in the margin section of the invoice.


## [1.285.4] - 2020-09-23
### Added
- Added stock alarm configuration filter in stock per item report.


## [1.285.3] - 2020-09-22
### Fixed
- Fixed an error when registering inventory from a purchase invoice.


## [1.285.2] - 2020-09-21
### Added
- Added export to XLS format option in product inventory movements.


## [1.285.1] - 2020-09-19
### Changed
- Improves inventory reports performance.


## [1.285.0] - 2020-09-17
### Added
- Added inventory movements report.


## [1.284.2] - 2020-09-16
### Changed
- Displays a more clear error when issuing invoices with an incorrect tax code or tax percentage code.


## [1.248.1] - 2020-09-15
### Fixed
- When issuing a invoice with a phone number that exceeds the limit of characters, now it shows a better error message


## [1.284.0] - 2020-09-09
### Added
- Added API endpoint to reissue purchase settlements


## [1.283.11] - 2020-09-09
### Fixed
- Fixed error when exporting waybills without recipient information.


## [1.283.10] - 2020-09-08
### Fixed
- Fixed log messages displayed and saved when mailing an invoice.


## [1.283.9] - 2020-09-07
### Fixed
- Fixed error when deleting the digital certificate.


## [1.283.8] - 2020-09-04
### Fixed
- Fixed error in catalog, the alarm was displayed even though the product didn't have the minimum stock configured.


## [1.283.7] - 2020-09-03
### Fixed
- Fixed error that does not allow to see the consumption statistics if the contract is inactive.
- Fixed bug that allows using the api even when the contract is inactive.


## [1.283.6] - 2020-09-02
### Fixed
- Fixed stock per item report.


## [1.283.5] - 2020-09-01
### Fixed
- Fixed the style of stock per item report for mobile


## [1.283.4] - 2020-09-01
### Fixed
- Fixed inventory transaction duplication error by invoice.
- Adds additional information configured in a new quote.

## [1.283.3] - 2020-08-31
### Fixed
- Fixed the style of stock per item report for mobile


## [1.283.2] - 2020-08-31
### Fixed
- Fixed UI in purchase settlement issue date


## [1.283.1] - 2020-08-30
### Fixed
- Fixed UI in purchase settlement issue date


## [1.283.0] - 2020-08-30
### Added
- Added filters in stock per item report.


## [1.282.8] - 2020-08-27
### Fixed
- Fixed permission error when deleting payments in invoice view.
- Fixed bug when edit an authorized invoice .


## [1.282.7] - 2020-08-24
### Fixed
- Fixed error when exporting the catalog.


## [1.282.6] - 2020-08-21
### Added
- Added product search in stock per item report.


## [1.282.5] - 2020-08-20
### Changed
- The new version of the stock per item report changed.

### Fixed
- Fixed the style of stock per item report for mobile.


## [1.282.4] - 2020-08-19
### Fixed
- Fixed bug that allows auto-delete or self-edit in the team section.
- Fixed bug when updating username.
- Fixed user migration error with blank space in username.
- Fixed bug when creating url to reset password and verify mail.


## [1.282.3] - 2020-08-18
### Fixed
- Fixes bug in sales by items report.


## [1.282.2] - 2020-08-17
### Fixed
- Fixed error when calculating ice to services product.


## [1.282.1] - 2020-08-17
### Fixed
- Fixes bug when creating a credit note.


## [1.282.0] - 2020-08-14
### Added
- Adds feature to calculate ice.


## [1.281.9] - 2020-08-11
### Fixed
- Fixed bug when making an input transaction if the items of an invoice don't have main code.


## [1.281.8] - 2020-08-07
### Fixed
- Fixed ticket average card.


## [1.281.7] - 2020-08-06
### Fixed
- Added invoices number and credit notes number in panel.
- Fixed error when creating or editing a poduct.
- Fixed date error when exporting the receivable report.


## [1.281.6] - 2020-08-06
### Fixed
- Fixed error when creating a product.
- Fixed error in the sales by items report.
- Fixed error in panel, credit notes total wasn't displayed.

## [1.281.5] - 2020-08-05
### Fixed
- Fixed error when resetting password.
- Fixed character encoding error.

## [1.281.4] - 2020-08-05
### Fixed
- Fixed stock per items report.


## [1.281.3] - 2020-08-04
### Fixed
- Fixed error when getting units sold in a period from the sales by items report and catalog.


## [1.281.2] - 2020-08-04
### Fixed
- Fixed stock per items report


## [1.281.1] - 2020-08-03
### Fixed
- Fixed error when making an adjustment


## [1.281.0] - 2020-08-02
### Added
- Added option to configure a minimun stock count when creating or editing a product and from the stock by items report. With this option it is possible to view the product stock level in a warehouse and the quantity of products to buy.
- Added option to filter by closing date in the stock by items report.

### Fixed
- Fixed error when creating or editing a waybill.


## [1.280.12] - 2020-07-30
### Fixed
- Fixed an error in Accounts Receivable URL
- Fixed an error in the customer statement link that appears in the Sales Invoice view
- Fixed an error that allowed customers to cancell a document that was already cancelled


## [1.280.11] - 2020-07-30
### Fixed
- Fixes Ecuador Waybill XML bug


## [1.280.10] - 2020-07-29
### Fixed
- Fixes problematic, legacy JS dependency.


## [1.280.9] - 2020-07-28
### Fixed
- Added purchase unit price when creating or editing a product.


## [1.280.8] - 2020-07-28
### Fixed
- Shows location commercial name if it exists in Ecuador XML documents.


## [1.280.7] - 2020-07-24
### Fixed
- Fixed an error when sending the account statement for account that have custom SMTP
settings.

### Changed
- The pending invoices warning now links directly to the accounts payable report


## [1.280.6] - 2020-07-23
### Fixed
- Fixed a UI error in Accounts Receivable by customer report.


## [1.280.5] - 2020-07-22
### Fixed
- Fixed invoice reimbursement error.


## [1.280.4] - 2020-07-21
### Fixed
- Fixed payment date problem.


## [1.280.3] - 2020-07-21
### Fixed
- Fixed a bug in Payment orders.


## [1.280.2] - 2020-07-21
### Fixed
- Fixed an error when trying to make a reimbursement invoice.


## [1.280.1] - 2020-07-21
### Fixed
- Retored link to internal invoice view in Accounts receivable report. Customers
complaint that they were not able to register payments to sales invoices through this
report.
- Prevent a user delete herself or edit her role.


## [1.280.0] - 2020-07-19
### Added
- Added export option to Accounts Receivable by customer report.
- New option to send via email a customer her accounts receivable report.

### Fixed
- Our customers will now see the correct number of overdue invoices they have.


## [1.279.0] - 2020-07-17
### Added
- Added API endpoint to edit Waybills.

### Fixed
- Fixes audit log feature when editing Credit Notes via API.


## [1.278.2] - 2020-07-16
### Fixed
- Fixed bug when viewing a sales invoice.


## [1.278.1] - 2020-07-14
### Changed
- Improved performance in documents queries features when requesting a document print
log.


## [1.278.0] - 2020-07-07
### Added
- Adds feature to update and delete user accounts.


## [1.277.8] - 2020-07-03
### Fixed
- Fixed salesman name when creating or editing invoices.


## [1.277.7] - 2020-07-03
### Changed
- Added purchase unit price when creating or editing a product


## [1.277.6] - 2020-07-02
### Fixed
- Fixed error when issuing a credit note with an invalid porcentaje code.


## [1.277.5] - 2020-07-01
### Fixed
- Fixed error when the password is less than 8 characters.
It only happens in the chrome browser.


## [1.277.4] - 2020-06-30
### Fixed
- Fixed error when updating an invoice with associated credit notes or withholding.
- Fixed error when creating a waybill from invoice.


## [1.277.3] - 2020-06-29
### Fixed
- Fixed error when issuing purchases settlements via API.


## [1.277.2] - 2020-06-29
### Fixed
- Fixed message that was displayed when activating a reminder.


## [1.277.1] - 2020-06-28
### Fixed
- Fixed some UI bugs in beta version of quotes.
- Improves performance in product search when creating or editing a document.


## [1.277.0] - 2020-06-25
### Added
- Adds invite team member feature


## [1.276.3] - 2020-06-24
### Fixed
- Fixed credit note's buyer's e-mail being saved as identification when re-issuing it.


## [1.276.2] - 2020-06-23
### Fixed
- Fixed error in waybill and withholding issue date.


## [1.276.1] - 2020-06-23
### Fixed
- Servers raw Datil Peru XML documents, instead of prettifying it, which affected the digital signature.


## [1.276.0] - 2020-06-17
### Added
- Added endpoint to reissue credit notes through API.


## [1.275.11] - 2020-06-17
### Fixed
- Fixed error when reversing a voided invoice.
- Fixed error in purchases invoices, inventory was not registering.
- Fixed error that allowed the buyer identification to be empty when issuing an invoice via API.


## [1.275.10] - 2020-06-16
### Fixed
- Fixed bug when. The lowercase username was not validated.
- Fixed bug when a user tries to reset their password multiple times.
- Fixed error new users have inactive status.
- Fixed error of incomplete information of the account stored in the session.


## [1.275.9] - 2020-06-15
### Fixed
- Fixed error in sales by item report and VAT tax report.


## [1.275.8] - 2020-06-15
### Fixed
- Fixed an error when viewing an invoice with additional discount.


## [1.275.7] - 2020-06-12
### Fixed
- Fixed an error when making an output transaction.


## [1.275.6] - 2020-06-12
### Fixed
- Fixed an error when creating an invoice that included items with no stock record.


## [1.275.5] - 2020-06-11
### Fixed
- Fixed error in sales by item report, there were negative net sales.
- Fixed error when voiding an authorized credit note.


## [1.275.4] - 2020-06-10
### Fixed
- Fixed error when creating a member with an existing username.
- Fixed error in inventory history, it allowed negative stock when the same item appeared more than once on a sales invoice


## [1.275.3] - 2020-06-10
### Fixed
- Fixed error when voiding an inventory input transaction.


## [1.275.2] - 2020-06-10
### Fixed
- Fixed error when authorizing an waybill with many additional details.


## [1.275.1] - 2020-06-04
### Fixed
- Fixed error when editing an invoice containing items with bulk sale.


## [1.275.0] - 2020-06-01
### Added
- Added option to reverse invoice void status.

### Fixed
- Fixed error when creating a member.


## [1.274.1] - 2020-05-30
### Fixed
- Fixed an error when downloading documents.


## [1.274.0] - 2020-05-29
### Added
- Added a new feature to create user and give access to points of sale.


## [1.273.5] - 2020-05-29
### Fixed
- Fixed an error in subscription plan usage stats. Total number of available documents
was not correct in some cases and the progres bar that visually displayed the usage
was not working.


## [1.273.4] - 2020-05-28
### Fixed
- Fixed error in VAT tax report when invoices have additional discount.


## [1.273.3] - 2020-05-21
### Fixed
- Fixed error when viewing an invoice.


## [1.273.2] - 2020-05-19
### Fixed
- Fixed email with username changed.
- validated existence of mail when registering new users.


## [1.273.1] - 2020-05-14
### Fixed
- Fixed weekly invoices stats.


## [1.273.0] - 2020-05-13
### Added
- Added reimbursement invoices total to dashboard.

### Fixed
- Fixed payment confirmation preview.


## [1.272.7] - 2020-05-13
### Fixed
- Fixed form to activate Market.


## [1.272.6] - 2020-05-12
### Fixed
- error codes when creating new users
- migration problem of certain users
- validations when resetting password


## [1.272.5] - 2020-05-11
### Fixed
- Fixes email style.
- Adds an email payment confirmation preview.


## [1.272.4] - 2020-05-11
### Fixed
- Added Kushki payment method as payment gateway.

## [1.272.3] - 2020-05-11
### Fixed
- Fixed public invoice view. Kushki payment method doesn't appear.


## [1.272.2] - 2020-05-08
### Fixed
- Fixed the style of the payment confirmation email for mobile.


## [1.272.1] - 2020-05-08
### Fixed
- Fixes error when sending email.


## [1.272.0] - 2020-05-07
### Added
- Added support for TwoCheckout payment method.
- Added new option to enable sending payment confirmation email.


## [1.271.3] - 2020-05-08
### Fixed
- Fixed problem when creating an invoice from quote, the total when editing the invoice was different from the quote total.


## [1.271.2] - 2020-05-08
### Fixed
- fixed problem when user has a password with less than 8 characters and his username is an email.
- unnecessary information by logging

## [1.271.1] - 2020-05-06
### Fixed
- fixed problem of users logged in Token.


## [1.271.0] - 2020-05-05
### Added
- Added authentication with cognition
- Added migration service to cognito
- Change a user's account


## [1.270.9] - 2020-05-05
### Fixed
- Fixed error when creating a purchase settlement via API, supplier's email wasn't saved.
- Fixed error when making a quote copy.
- Subscription section was improved.


## [1.270.8] - 2020-05-03
### Fixed
- Restored previous account usage calculation configuration.


## [1.270.7] - 2020-05-02
### Fixed
- Fixed error when viewing received documents.


## [1.270.6] - 2020-05-01
### Fixed
- Fixes error in account stats reports, total invoice number is wrong.


## [1.270.5] - 2020-05-01
### Fixed
- Fixes error in account stats reports.


## [1.270.4] - 2020-05-01
### Fixed
- Performance optimizations in account stats reports.


## [1.270.3] - 2020-04-29
### Fixed
- Fixed Peru perceptions template bug.


## [1.270.2] - 2020-04-27
### Fixed
- Fixed bug when getting contacts list.


## [1.270.1] - 2020-04-25
### Fixed
- Fixed payables by supplier report URL.


## [1.270.0] - 2020-04-20
### Fixed
- Deleted duplicated datil-os client code

### Added
- Pagination for Peru documents


## [1.269.24] - 2020-04-18
### Fixed
- Fixed error when issuing waybill via API.
- Fixed error when importing a Purchase Invoice from an XML.
- Fixed product search. Some products that matched the search criteria were not being displayed.


## [1.269.23] - 2020-04-17
### Fixed
- Fixed error when issuing invoice via API.


## [1.269.22] - 2020-04-17
### Changed
- SMTP settings section changed. It now shows the reason for error when testing settings before saving.

### Fixed
- Fixed error when issuing invoice via API.


## [1.269.21] - 2020-04-17
### Fixed
- Fixes link for Peru XML retention downloads.


## [1.269.20] - 2020-04-16
### Added
- Added support for credit notes, debit notes, perceptions and retentions in Datil Peru Dashboard.
- Fixes compatibility bugs with DatilOS REST API.


## [1.269.19] - 2020-04-09
### Fixed
- Fixed error when creating custom print template.
- Fixed error when creating purchase settlement, uuid was generated with an incorrect issue date.


## [1.269.18] - 2020-04-08
### Changed
- Added new event when issuing purchase settlements.


## [1.269.17] - 2020-04-06
### Changed
- Fixed error on invoice, it was showing unrelated withholdings.


## [1.269.16] - 2020-04-05
### Changed
- Fixed error when inferring document status.


## [1.269.15] - 2020-04-04
### Fixed
- Fixed error when issuing a waybill via API.


## [1.269.14] - 2020-04-03
### Fixed
- Fixed error when viewing payout receipts.


## [1.269.13] - 2020-04-03
### Fixed
- Fixed error when sending payout receipts.


## [1.269.12] - 2020-04-02
### Fixed
- Fixed error when processing a VPOS credit card payment.


## [1.269.11] - 2020-04-01
### Fixed
- Fixed error when consulting the authorization status of a document by API.
- Fixed error when editing a purchase settlement, the issue date was incorrect.


## [1.269.10] - 2020-03-31
### Fixed
- Fixed error in get business information REST API.


## [1.269.9] - 2020-03-31
### Fixed
- Fixed bug when consulting the status of a document by API.
- Fixed bug when creating a purchase settlement. The issue date was incorrect.


## [1.269.8] - 2020-03-30
### Fixed
- Fixed bug when consulting the status of a document via API.


## [1.269.7] - 2020-03-30
### Fixed
- Fixed bug when searching for a product.


## [1.269.6] - 2020-03-30
### Fixed
- App menú for Peru customers is back.


## [1.269.5] - 2020-03-28
### Fixed
- Fixed product search.


## [1.269.4] - 2020-03-27
### Changed
- Improves product search.


## [1.269.3] - 2020-03-26
### Fixed
- Fixes bugs when getting products by API.


## [1.269.2] - 2020-03-26
### Fixed
- Fixes bugs when viewing a waybill or invoice in pdf.


## [1.269.1] - 2020-03-26
### Fixed
- Fixed error in VAT tax report.


## [1.269.0] - 2020-03-23
### Added
- Product search was improved and is smarter now. Products that match any of the search terms is now displayed in the list instead of just the ones that exactly match the terms


## [1.268.0] - 2020-03-20
### Added
- Invoice subtotal amount before item discount is now available to use in the custom
print template.


## [1.267.3] - 2020-03-18
### Changed
- SMTP settings section was improved. We now make sure your settings work before you are able to save them.


## [1.267.2] - 2020-03-18
### Fixed
- Fixed error message when sending a non-existent identification type in a purchase settlement via API.
- Fixed error message when sending a non-existent document type in a purchase settlement with reimbursement via API.
- Fixed error when getting related withholdings to an invoice.
- Fixed error when creating a waybill with quantities of more than two decimal places, it was rounded up to two decimal places.
- Fixed error that occurred when creating or editing a point of sale if the description was longer than 50 characters.
- Fixed error when exporting the stock per item report.


## [1.267.1] - 2020-03-17
### Fixed
- Fixed a problem when importing products with a stock recount transaction.


## [1.267.0] - 2020-03-16
### Added
- Added entry date when creating a purchase invoice and registering inventory.
- It is now possible to view the name of the product while making a quote or purchase settlement.

### Fixed
- Fixed bug when creating a purchase settlement with reimbursement, the items subtotal with reimbursement type was validated instead of the total.


## [1.266.18] - 2020-03-12
### Fixed
- Fixed bug when creating a purchase settlement, item auxiliary code was ignored.


## [1.266.17] - 2020-03-11
### Fixed
- Fixed an error that occured when processing a Credit note.
- Fixed an error when creating an Inventory stock recount transaction.


## [1.266.16] - 2020-03-11
### Fixed
- Fixed bug when setting the sequence for purchase settlement documents.


## [1.266.15] - 2020-03-11
### Fixed
- Fixed some accuracy errors in unit price and cost margin calculations in
beta quotes section.


## [1.266.14] - 2020-03-10
### Fixed
- Fixed some validations bugs in beta quote section and purchase settlement.


## [1.266.13] - 2020-03-09
### Fixed
- Fixed a bug in import Products option.
- Performance improvements in Catalog Product list.


## [1.266.12] - 2020-03-09
### Fixed
- Fixes bug when creating reimbursement purchase settlement.
- Fixed bug when creating a purchase settlement by XML.


## [1.266.11] - 2020-03-06
### Fixed
- Fixed a bug when creating a purchase settlement.


## [1.266.10] - 2020-03-06
### Fixed
- Fixed a performance bug for accounts with many transactions.


## [1.266.9] - 2020-03-05
### Fixed
- Fixed an error that was sometimes generated when registering a sales invoice.
- Fixed error message when sending a non-existent tax code in a purchase settlement via API.
- Fixed error when editing a withholding via API, taxes received were ignored.
- Fixed error in purchase settlements, it was not possible to add unit discounts.


## [1.266.8] - 2020-03-04
### Fixed
- Fixed error in beta quotes section, unit cost used was from catalog instead of average unit cost.


## [1.266.7] - 2020-03-04
### Fixed
- Fixed error when exporting Product Catalog.


## [1.266.6] - 2020-03-04
### Fixed
- Fixed bug when creating a Sales Invoice via the app. The problem was the
Invoice was saved even when an error was displayed on the screen.
- Fixed a bug in REST API create invoice endpoint that caused info adicional to
be truncated when the description included colons.
- Fixed bug when importing withholding version 2.
- Fixed bug in Purchase Settlement XML parser.

### Changed
- Turns off validation for record_payments when updating a Sales Invoice.


## [1.266.5] - 2020-03-03
### Fixed
- Fixed a performance issue with some search fields.


## [1.266.4] - 2020-03-02
### Fixed
- Fixed a problem with search fields.


## [1.266.3] - 2020-03-02
### Changed
- It's now possible to generate a waybill from a draft invoice.

### Fixed
- Fixed some UI bugs in beta version of quotes.


## [1.266.2] - 2020-02-29
### Fixed
- Fixed bug in add/update products in bulk.


## [1.266.1] - 2020-02-28
### Changed
- Application performance improvements.


## [1.266.0] - 2020-02-28
### Added
- A new option to add Products and perform inventory adjustment transactions in bulk.

### Changed
- Changed the way Product price list column is printed when exporting the Catalog.
- Stock recount transaction now allows to perform recount on a product with no prior
stock record. In this case the stock record is created with the supplied quantity.

### Fixed
- Audit log for Purchase settlements was not being saved with useful information.
- Fixes a nasty bug in clearance REST API end points. If an exception ocurred while
attending the request a 400 response was returned instead of a 500 one.


## [1.265.1] - 2020-02-24
### Added
- Added PDF download link for Peru documents.


## [1.265.0] - 2020-02-21
### Added
- Added reimbursement purchase settlement by XML.
### Fixed
- Fixed bug when creating a reimbursement invoice.


## [1.264.1] - 2020-02-21
### Fixed
- Fixed bug in Copy Invoice feature.


## [1.264.0] - 2020-02-20
### Added
- Added first version of quotes with profit margins.


## [1.263.3] - 2020-02-18
### Fixed
- Fixed bug when updating a purchase settlement.


## [1.263.3] - 2020-02-17
### Fixed
- Fixed a bug when creating a purchase settlement via API if product code has accent mark.


## [1.263.2] - 2020-02-12
### Fixed
- Fixed a bug in get edoc authorization information service.sfe


## [1.263.1] - 2020-02-12
### Fixed
- Fixed bug in invoice view, inventory section was being shown to users that were not supposed to see it.


## [1.263.0] - 2020-02-10
### Added
- Added reimbursement purchase settlements.
- Added reimbursement document information on invoice and purchase settlement view.


## [1.262.2] - 2020-02-07
### Fixed
- Fixed Purchase Settlement transformation to include supplier email.


## [1.262.1] - 2020-02-07
### Fixed
- Fixed bug when searching contacts in purchase settlement section.
- Fixed bug due to consulting payment reminder information on received invoices.


## [1.262.0] - 2020-02-06
### Added
- Now claveAcceso is generated automatically when creating a Purchase Settlement via XML

### Fixed
- Purchase Settlements public view was not public, now it is.
- Fixes a bug in creating Purchase Settlements via XML. Payment methods were completely
ignored.


## [1.261.11] - 2020-02-04
### Fixed
- Fixed error in create Purchase Settlement from XML endpoint that happened when sending
non ASCII characters in the XML.


## [1.261.10] - 2020-02-02
### Fixed
- Fixed error when submitting an empty document filename template


## [1.261.9] - 2020-01-31
### Fixed
- Fixed bug in the inventory history, when canceling a transaction of an item, if there aren't more transactions, stock's number doesn't restore.


## [1.261.8] - 2020-01-30
### Fixed
- Fixed bug when creating a purchase settlement with reimbursement by API.


## [1.261.7] - 2020-01-29
### Fixed
- Fixed bug when updating a purchase invoice.
- Fixed purchase settlement's title in RIDE.


## [1.261.6] - 2020-01-23
### Fixed
- Fixed bug at generating the xml from a Purchase Settlement.


## [1.261.5] - 2020-01-23
### Fixed
- Fixed bug when editing a purchase settlement, point of sale was incorrect.


## [1.261.4] - 2020-01-23
### Fixed
- Fixes bug when viewing an invoice. Logs show the invoice's receiver email but not the actual email where it was sent.


## [1.261.3] - 2020-01-23
### Fixed
- Fixes some bugs in register inventory view when creating a product.
- Fixes UI bug in taxes report.


## [1.261.2] - 2020-01-23
### Fixed
- Fixes bug in custom document filename feature where user configuration wasn't loading.


## [1.261.1] - 2020-01-23
### Fixed
- Fixes encoding error when downloading a PDF and XML file.


## [1.261.0] - 2020-01-21
### Added
- Added new option to business setting. User can now specify a file name template for downloaded documents (PDF and XML)


## [1.260.4] - 2020-01-19
### Fixed
- Fixed date when issuing and filtering documents.


## [1.260.3] - 2020-01-17
### Fixed
- Fixed reimbursement section when creating a supplier.


## [1.260.2] - 2020-01-16
### Fixed
- Fixed default start date in documents list.


## [1.260.1] - 2020-01-15
### Fixed
- Fixed default date in documents list and payment orders.


## [1.260.0] - 2020-01-14
### Changed
- The date range options changed.
- Changed the default selected date range to MTD in all date range pickers.


## [1.259.6] - 2020-01-14
### Fixed
- Fixed bug when voiding a purchase invoice, transaction was saved with a wrong document support date.


## [1.259.5] - 2020-01-13
### Fixed
- Fixed bug in purchase settlement when there is only one point of sale.
- Fixed bug when creating a supplier in reimbursement section.


## [1.259.4] - 2020-01-11
### Fixed
- Fixed bug in purchase settlement view.
- Fixed bug when setting a product in purchase inventory section.


## [1.259.3] - 2020-01-10
### Fixed
- Fixed bug in purchase settlement xml when discount or total amount had more than two decimal places.


## [1.259.2] - 2020-01-09
### Fixed
- Fixed bug when editing purchase settlement.
- Added payment methods section to ride.


## [1.259.1] - 2020-01-06
### Fixes
- Fixes emails marked as sent even when an error had happened.


## [1.259.0] - 2020-01-06
### Added
- Added new feature to issue purchase settlements through the Dashboard.


## [1.258.2] - 2020-01-06
### Fixed
- Response after creating a Purchase Settlement with XML was updated to return all the
document information.


## [1.258.1] - 2020-01-06
### Fixed
- Fixed error when authorizing invoice.


## [1.258.0] - 2020-01-05
### Added
- New REST service endpoint to create Purchase Settlements using XML as input.


## [1.257.10] - 2020-01-03
### Fixed
- When sending emails, logs wouldn't show up when viewing invoice


## [1.257.9] - 2020-01-02
### Fixed
- Fixed a bug that prevented access to received documents from the app.datil.com domain.


## [1.257.8] - 2019-12-26
### Fixed
- Fixed a bug that happened when generating a waybill from an invoice that has items
with longer that 25 chars in their codes.


## [1.257.7] - 2019-12-26
### Fixed
- Fixed error at making an input transaction when the invoice has discounts.


## [1.257.6] - 2019-12-21
### Fixed
- Fixed error when loggin SMTP credentials. Error was due to SMTP not accepting unicode.
- Fixed error when sending email and the entity associated didn't have information in certain fields.


## [1.257.5] - 2019-12-17
### Fixed
- Fixed a bug where the email icon didn't showed up even if the email was sent.
- Fixed error getting stuck when viewing an invoice and sending an email


## [1.257.4] - 2019-12-17
### Added
- Added new proyect `serverless`. Built with AWS SAM. It sends emails synchronously and has scripts to deploy and create or update other AWS services like S3, Lambda functions or API Gateway.
- Service that calls the lambda function and passes all the information to be sent in the email.
- View that takes the `weburl` of a document and uses the Email service

### Fixed
- The email sent status is now more accurate. Now the email is registered as sent, only when the email successfully reaches the SMTP server.

### Changed
- Emails now are sent throug a Lambda function that is build with AWS SAM.


## [1.257.3] - 2019-12-17
### Fixed
- Fixed a UI JS bug that prevented customers from opening Team and Account Statement
options.


## [1.257.2] - 2019-12-13
### Fixed
- Fixed bug in purchase settlement when creating xml representation.

## [1.257.1] - 2019-12-13
### Fixed
- Fixed bug at making an input transaction, existing supplier contact was replaced.
- Fixed some bugs in purchase settlement.


## [1.257.0] - 2019-12-05
### Added
- Support for Banco del Pacifico payment order bank response to automatically register
payments to invoices and mark payment orders as paid.

### Fixed
- A bug in the payment order bank inbox email address that was displaying an incorrect
address.
- A bug that caused paid orders to be returned when calling PaymentOrder.objects.latest_for_invoice.
- Cliente model UUID field set as unique.


## [1.256.20] - 2019-12-04
### Fixed
- Fixed bug when parsing an invoice.


## [1.256.19] - 2019-12-03
### Fixed
- Fixed bug when recording invoice payments from API.


## [1.256.18] - 2019-12-02
### Fixed
- Fixed bug when creating a purchase invoice, if the entity associated to the supplier doesn't have a country.
- Fixed bug when updating a purchase invoice, the balance was not updating.
- Fixed bug when creating or updating a purchase invoice, if an item was deleted, totals weren't updating.


## [1.256.17] - 2019-11-29
### Fixed
- Fixed UI bug in documents notification email section.


## [1.256.16] - 2019-11-29
### Fixed
- Fixed bug when issuing a withholding, presumptive type withholdings were shown.
- Fixed bug in documents notification email section, the email example wasn't displaying.
- Added validation of code field when creating a location.


## [1.256.15] - 2019-11-28
### Fixed
- Fixes message not displaying when doing a payment order in a public page.
- Adds message to renew certificate before it expires.


## [1.256.14] - 2019-11-28
### Fixed
- Fixed bug when trying to view an invoice that doesn't exist via API.


## [1.256.13] - 2019-11-27
### Fixed
- Fixes a bug in ecuador invoice parser.


## [1.256.12] - 2019-11-27
### Fixed
- Fixed bug when making an input transaction through a purchase invoice if the item name is too long.


## [1.256.11] - 2019-11-27
### Fixed
- Fixed bug when recording payments to an invoice via API, the balance was not updating.


## [1.256.10] - 2019-11-27
### Fixed
- Fixed bug when creating a product from register inventory view.
- Fixed bug when creating a supplier from reimbursement section.


## [1.256.9] - 2019-11-25
### Fixed
- Fixed bug when viewing a purchase invoice, the issuer's locations were unnecessarily charged.
- Fixed bug when deleting a purchase invoice, inventory was not void.
- Fixed bug when making inventory adjustment, clicking several times the transaction was doubled
- When making an input transaction through a purchase invoice discounts were not considered.
### Added
- Added unit cost in register inventory view.


## [1.256.8] - 2019-11-22
- Fixes error when showing invoice.

## [1.256.7] - 2019-11-21
- Fixed link copy to clipboard showing as a banner message
- Fixed UI bugs in carriers template
- Fixed navbar not showing in payables template

## [1.256.6] - 2019-11-21
### Fixed
- Fixed off-centered page when in test mode


## [1.256.5] - 2019-11-20
### Fixed
- Fixed receipt balance not being updated when reminder is send.
- Fixed pages 'jumping' when displaying banner messages


## [1.256.4] - 2019-11-18
### Fixed
- A bug that caused the new documento notification email to be sent multiple times for
documents that remained in "en proceso" status for too long.
- Fixes a bug in session refresh middleware.


## [1.256.3] - 2019-11-17
### Fixed
- Style improvements and fixes to Team Members list view.


## [1.256.2] - 2019-11-15
### Fixed
- Fixes bug at creating a credit note and waybill from invoice.
- Fixes bug at creating and editing a purchase invoice.


## [1.256.1] - 2019-11-15
### Fixed
- Fixes team list view.
- Fixes bug in weekly summary.
- Fixes bug when printing invoice, canceled status isn't displayed.


## [1.256.0] - 2019-11-13
### Added
- Adds list of users associated with my account.


## [1.255.1] - 2019-11-11
### Fixed
- Fixes typo in 'app_recurringcharges.html'
- Fixes expired certificate message showing even after it's been paid.

## [1.255.0] - 2019-11-11
### Fixed
- Fixed bug not showing multiple messages to users.
- Fixed wrapper div containing banner messages show before the actual message
- Fixed banner messages not appearing in templates that included app_cljs.html

### Added
- Templates for banner messages and toasts
- CSS rules for toasts and banner messages

### Changed
- Messages now are displayed as toasts
- Expired certificate and pending invoices now display as banner messages
- Main JS script changed to handle toasts
- Changed templates to use the banner and toast templates


## [1.254.6] - 2019-11-11
### Fixed
- Fixes bug when creating a purchase invoice with some items with the same id.


## [1.254.5] - 2019-11-11
### Fixed
- Shows correct issue date when viewing a Peru document.


## [1.254.4] - 2019-11-07
### Fixed
- Allows scrolling inside Peru documents.


## [1.254.3] - 2019-11-06
### Fixed
- Fixed a bug at making an input transaction when a product doesn't have unit of measurement.
- Fixed a bug at editing a category with a large amount of items.


## [1.254.2] - 2019-11-06
### Fixed
- Generates payment orders for all enabled banks.

## [1.254.1] - 2019-11-01
### Fixed
- Support for a new order_by parameter was added to the Sales Invoices REST API. When
this param was not supplied the issue_date was set as a default. This default overrode
the previous default ordering, thus changing the beahviour.
- Fixes Quotes usage stats function bug.


## [1.254.0] - 2019-10-31
### Fixed
- Fixed bug related to templates.
- Fixed bug so that Peru document CSV export works correctly.


## [1.253.2] - 2019-10-30
### Fixed
- Fixed bug that occurs when a sales invoice with items that have a selected warehouse and items without a warehouse is issued. Items without a warehouse are not inventoried.


## [1.253.1] - 2019-10-30
### Fixed
- Fixed a bug in a internal (used by the support team) Payment Order view.


### Changed
- Updated the certificate expiration notification email template to include the Jotform
link.


## [1.253.0] - 2019-10-30
### Added
- Adds temporary Dashboard for Peru customers integrating DatilOS


## [1.252.4] - 2019-10-29
### Fixed
- Sets Invoice document as default in withholding documents list.
- Adds waybill option to invoice view.
- Adds permissions to generate credit note and waybill from invoice.
- Fixed bug in product view. If the product isn't inventoriable, the inventory section was displayed.


## [1.252.3] - 2019-10-29
### Fixed
- Fixed delete option enabled/disbled logic.
- Exclude Invoice Payments from cancelled invoices from Payments list.


## [1.252.2] - 2019-10-28
### Fixed
- Removes duplicated Payments section in Invoice viewer.


## [1.252.1] - 2019-10-27
### Fixed
- NPE fix in documents view controller.


## [1.252.0] - 2019-10-25
### Added
- New Quotes section.


## [1.251.0] - 2019-10-26
### Added
- Allows to generate a waybill from an invoice.
- Adds purchase settlement to subscription.


## [1.250.1] - 2019-10-22
### Fixed
- IVA report organization. Previous version was not easy to read.
- Rolled back a minor change in sfe/settings to fix deploy issue.


## [1.250.0] - 2019-10-22
### Added
- Ability to enable multiple Payment Gateways for any account.
- Adds support for Banco del Pacífico in Payment Orders module.
- A script to run migrations in the correct order for a newly created test database.
- Sales Invoices list REST API endpoint now accepts `order_by` parameter.


## [1.249.3] - 2019-10-22
### Added
- Added all documents in withholding's support document list.


## [1.249.2] - 2019-10-22
### Fixed
- Allows users to access to register inventory option in purchases invoices list.
### Added
- Adds owner group by default when creating an account.


## [1.249.1] - 2019-10-22
### Fixed
- Fixes bug in check permissions middleware.


## [1.249.0] - 2019-10-21
### Added
- Added permissions for owners, sales and cashiers.


## [1.248.6] - 2019-10-16
### Fixed
- Fixed bug at creating a purchase invoice when there are more than one ice-tax with the same code.


## [1.248.5] - 2019-10-11
### Fixed
- Adds channel param in reimbursement information received via API.


## [1.248.4] - 2019-10-10
### Fixed
- Changed document type and tax value in reimbursement information received via API.
- Changed payments parameter in purchase settlement information received via API.


## [1.248.3] - 2019-10-08
### Fixed
- Fixed in purchase settlement api. Added authorization information to purchase settlement response.


## [1.248.2] - 2019-10-08
### Fixed
- Fixed in purchase settlement api.


## [1.248.1] - 2019-10-07
### Fixed
- Fixed in xml view.


## [1.248.0] - 2019-10-05
### Added
- Added purchase settlements to issued receipts, they can be authorized from datil.


## [1.247.1] - 2019-10-04
### Fixed
- Fixes bug at exporting sales by item report in excel or CSV when it is filtered by status.
- Changes the url that returns to locations list.


## [1.247.0] - 2019-10-02
### Added
- New IVA monthly report.


## [1.246.3] - 2019-09-25
### Fixed
- Removes duplicated "Crear una copia" button from Invoice viewer.
- Removes accents from document type name when sending the notification email.


## [1.246.2] - 2019-09-25
### Fixed
- Fixed bug when exporting received withholdings with version 2.0, they don't appear in the downloaded CSV or XLS file.
- Non-active users appear in the sales representatives list, they should not appear.


## [1.246.1] - 2019-09-19
### Fixed
- Fixed bug when making an input transaction. If the warehouse is empty, the item is shown duplicated in the inventory history.
- Fixed bug in purchase inventory.


## [1.246.0] - 2019-09-17
### Added
- Added sale note in withholding's support document.
- Added create account unit of measurement when user registers.
### Fixed
- Fixed some bugs in purchase inventory section.
- Fixed bug at editing a purchase invoice. When the warehouse is empty, the item is shown duplicated in the inventory history.


## [1.245.2] - 2019-09-17
### Fixes
- Adds a new setting entry for Payment Orders so that the PO batch file is sent to a
customers email address. Now it is fixed to a Datil email address.
- Pichincha Payment orders: Restrict row description length to 50 characters.


### Changed
- Pichincha Payment orders: If the invoice includes more than one item, the description
is set to: "Factura 001-003-000012394" for example.


## [1.245.1] - 2019-09-12
### Added
- Added reimbursement document in withholding's support document list.


## [1.245.0] - 2019-09-11
### Added
- Contracts now support an "extra transactions" field, that sums up to the plan transaction limit.
- Reports usage stats to Intercom.


## [1.244.2] - 2019-09-09
### Fixed
- Fixes bug so that Kushki charges are created with the correct taxable amount, considering invoice additional discount.


## [1.244.1] - 2019-09-09
### Fixed
- Fixes copy withholding bug.
- Fixed bug in business stats report. A string is expected in the dynamo table that
stores business that have made sales during the week (active businesses)


## [1.244.0] - 2019-09-07
### Added
- New option to duplicate a Withholding.


### Fixed
- Fixed bug in business stats report. Now the report calcution functions expect the
EntidadTributaria id instead of the RUC.


## [1.243.0] - 2019-09-06
### Added
- Added fee type product, this product type is not considered in tip calculation.
### Fixed
- Fixed bug when rendering input transaction view.
- Fixed bug when copying invoice because unit of measurement was a dict.


## [1.242.0] - 2019-09-05
### Added
- Added input transaction from a purchase invoice.


## [1.241.0] - 2019-09-04
### Added
- New option to duplicate a Waybill.

### Changed
- Display certificate expiration date in settings


## [1.240.1] - 2019-08-30
### Fixed
- Fixed bug at exporting sales by item report in excel. Sale return wasn't displaying.


## [1.240.0] - 2019-08-27
### Added
- A new model, FeatureFlag, that will help enable or disable features for accounts.
- New option to send the notification email right after creating an Invoice.
- New setting that will allow to turn on and off automatic generation of Invoice
payment orders.

### Fixed
- Fixes a know issue with payment orders. Banco Pichincha ID validation algorithms are
outdated and this causes problems when uploading orders to the bank. The problematic
IDs are detected and that piece of information is removed from the batch.


## [1.239.11] - 2019-08-26
### Fixed
- Fixed bug in business stats report.


## [1.239.11] - 2019-08-26
### Fixed
- Fixed bug at getting email report with business stats.


## [1.239.10] - 2019-08-23
### Added
- Displays year when filtering by dates not in the same year.


## [1.239.9] - 2019-08-22
### Fixed
- Fixed bug in panel filter when  making a new sale.


## [1.239.8] - 2019-08-22
### Fixed
- Fixed bug in panel filter when location has long name.


## [1.239.7] - 2019-08-21
### Fixed
- Editing invoice error due to variable not being properly initialized.

## [1.239.6] - 2019-08-21
### Fixed
- Fixed bug in panel filter when location has logo, logo was removed from parameters.


## [1.239.5] - 2019-08-19
### Fixed
- Fixed bug in panel filter when location has logo.


## [1.239.4] - 2019-08-19
### Added
- Added location filter to panel.


## [1.239.3] - 2019-08-19
### Fixed
- Fixed error when editing an invoice which included a product non-existent in the database.


## [1.239.2] - 2019-08-15
### Fixed
- Unit of measurement values weren't being correctly saved when creating or editing an invoice.


## [1.239.1] - 2019-08-07
### Fixed
- Fixed bug at viewing an inventory transaction when there are more than one user with the same token.
- UI style fix in reports, filters with long names were overflow.   


## [1.239.0] - 2019-08-02
### Added
- Added status filter to the Sales By Items report.


### Fixed
- Fixed Dashboard bug. Credit notes where not being filtered by the selected status.


## [1.238.4] - 2019-08-01
### Fixed
- Fixed bug after canceling an inventory adjustment transaction, url sent was null.


## [1.238.3] - 2019-07-29
### Fixed
- Fixed bug at canceling an inventory adjustment transaction.


## [1.238.2] - 2019-07-24
### Added
- Added support for Datil.com domain.


## [1.238.1] - 2019-07-24
### Fixed
- Fixed bug when trying to see a receipt from inventory history.


## [1.238.0] - 2019-07-23
### Fixed
- Fixed bug when editing purchase invoice, discount was showing incorrect.
- Fixed bug when creating purchase invoice, there was a problem with environment.
### Added
- Added a button to cancel Inventory Transactions. This cancel option will only be available for users in the owners group and for transactions generated from Inventory Adjustments


## [1.237.7] - 2019-07-19
### Fixed
- Fixed bug when updating affected documents balance.


## [1.237.6] - 2019-07-17
### Fixed
- Fixed login bug that redirected free plan customers to purchases index
- Fixed a bug in filter invoices function
- Improved filtering in invoice list function


## [1.237.5] - 2019-07-17
### Fixed
- Fixed inventory at editing a purchase invoice, stock was incorrect.
- Fixed at editing and saving a purchase invoice, environment always was in production.

## [1.237.4] - 2019-07-12
### Fixed
- Changed support document date in credit notes to take authorization date instead of creation date.
- Fixed bug that caused at getting withholding support document.
- Added rebuild_inventory_for_items_in_tx function.


## [1.237.3] - 2019-07-12
### Fixed
- Changed support document date to take authorization date instead of creation date.


## [1.237.2] - 2019-07-08
### Fixed
- Added expiration date field to Invoice with Credits
- Fixed a bug that prevented deleting an user from admin.


## [1.237.1] - 2019-07-08
### Fixed
- Fixed a bug that prevented updating the subscription payment method.


## [1.237.0] - 2019-07-06
### Changed
- Changed worker type to async (gevent)


## [1.236.12] - 2019-07-05
### Fixed
- Adds missing field to report view.


## [1.236.11] - 2019-07-05
### Fixed
- Foreign key related bug with reports.models.InvoiceWithCredits fixed.


## [1.236.10] - 2019-07-04
### Fixed
- Offline compression error fix.


## [1.236.9] - 2019-07-04
### Fixed
- Fixed another bug in TokenService client.
- Style fixes for mobile devices in Dashboard and Credit note view screens.
- If an error occurs while loading the dashboard data, and error message is shown.
Previously the loading wheel remained spinning forever.
- Now the import edoc REST API endpoints return a 400 error when an invalid XML is
received instead of raising an exception and returning a 500 status
- Dashboard performance was greatly improved. Lots of queries where not correct and not
optimized


## [1.236.8] - 2019-07-03
### Fixed
- Changed Payout Receipts export file extension to .xls so it can be opened correctly.


## [1.236.7] - 2019-07-02
### Fixed
- Fixed a bug in TokenService client.
- Using the `EntidadTributaria` id instead of the ruc field to get reports. Report
queries should run a lot faster using the id instead of ruc field.
- Added a new check in the first custom middleware to force logout if the logged user
does not have an account (cuenta) in her session.
- Improved Ecuador CreditNote XML parser to raise an InvalidReceiptXML exception when
required fields are not found in the XML.
- Added missing DB indexes to some models to improve speed of common queries.
- Applying the proper ordering to customer reports functions to improve performance.


## [1.236.6] - 2019-07-01
### Fixed
- Fixed bug in draft invoices, when current unit cost of item in stock is zero, profit margins calculation is wrong.  


## [1.236.5] - 2019-06-27
### Fixed
- Fixed bug in draft invoices, services were shown in inventory transactions.


## [1.236.4] - 2019-06-27
### Fixed
- Fixed a bug that prevented customers with inactive contracts to see the accounts
payable report and pending invoices


## [1.236.3] - 2019-06-26
### Fixed
- Fixed updating affected documents balance after authorizing a withholding.


## [1.236.2] - 2019-06-24
### Fixed
- Fixed rounding when creating or editing a waybill item.


## [1.236.1] - 2019-06-21
### Fixed
- Fixed coding error in the new margin section in draft invoices.


## [1.236.0] - 2019-06-21
### Added
- Added profit margins to draft invoices.


## [1.235.10] - 2019-06-21
### Fixed
- Fixed when importing withholdings with incomplete authorization information.


## [1.235.9] - 2019-06-19
### Fixed
- Fixed withholdings related to an invoice were not shown.
- Fixed Withholding serializer, it was referring to Factura.
- Add Documents to Withholding serializer.
- Fixed in received withholdings, the environment was always PRODUCTION.


## [1.235.8] - 2019-06-18
### Fixed
- Fixed edit invoice option when product_id is null.


## [1.235.7] - 2019-06-17
### Fixed
- Fixed edit invoice option.


## [1.235.6] - 2019-06-14
### Added
- Added customer name in inventory output.


## [1.235.5] - 2019-06-14
### Fixed
- Fixed bug in additional details of invoice items when inventory wasn't enabled.


## [1.235.4] - 2019-06-13
### Fixed
- Fixed bug in additional details of invoice items.
- Fixed bug in catalog. It was not possible to change the unit of measure of a product when it already had stock register.
- Fixed bug at editting a withholding without document date


## [1.235.3] - 2019-06-12
### fixed
- Fix bug in inventory when stock is negative.


## [1.235.2] - 2019-06-12
### Fixed
- Show banner ad when printing an invoice.


## [1.235.1] - 2019-06-11
### Fixed
- In the withholdings received, the total was not being calculated correctly.
- Fixed at getting withholding version.
### Added
- Add TipoSustento and TipoRegimenFiscal to admin


## [1.235.0] - 2019-06-10
### Added
- Now it's possible to import withholding with version 2.0.
### fixed
- UI style fix in item quantity and total transactions inside sales by producto report.


## [1.234.9] - 2019-06-05
### Fixed
- The invoice in pdf dind't show Reimbursement claim information.


## [1.234.8] - 2019-06-04
### Fixed
- When an Invoice was being copied, did not copy Reimbursement claim information.
- UI style fix in sales by producto report.
- Fix on delete receipt, logs were being deleted too.


## [1.234.7] - 2019-05-31
### Fixed
- The sales by product report was showing duplicated items.
- UI style fix, top sold items were not ordered by net sales.
- Added producto_id in DetalleFactura at create invoice json.


## [1.234.6] - 2019-05-30
### Fixed
- The sales by product report was not calculating correctly the net sales, number
of items sold and total discounts.
- In the section of best selling items It was considering the items returned.
- UI changes. Added total quantity and tooltips to gross sales, net sales and total
discounts in sales by product report.
- UI changes in the menu. Points of sale with long names couldn't be seen.  
- Added an alert in case the invoices include additional discounts in sales by product report.


## [1.234.5] - 2019-05-30
### Changed
- PayoutReceipts are exported in Excel format by default.
### Fixed
- The correct client IP was not being logged, now it is.


## [1.234.4] - 2019-05-28
### Fixed
- PayoutReceipts now render correctly in small screens (i.e. smartphones)

### Added
- Support custom PayoutReceipt templates


## [1.234.3] - 2019-05-24
### Fixed
- Temporarily ignore InvalidXML exceptions to enable automatic retry since a
false positive InvalidXML exception y being thrown by `sign_request` function
- Stop using django.request logger for InvalidXML exceptions.
- Fixes JSON serialization bug in Market view
- Switch to regular logger in core.middleware ExceptionMiddleware.
- Fixes a bug in Product edit view related to "list_propiedades" field.


## [1.234.2] - 2019-05-23
### Fixed
- Allow visiting Payout Receipt public view without being logged-in


## [1.234.1] - 2019-05-23
### Fixed
- Get business ID correctly when checking setting in context processor.


## [1.234.0] - 2019-05-23
### Added
- Support for issuing payout receipts that can be digitally signed. It can be activated through the "New Menu" setting.


## [1.233.1] - 2019-05-22
### Fixed
- Fixed at getting product type, it can be null and it wasn't validated.


## [1.233.0] - 2019-05-22
### Added
- Added reimbursement claim section. Now users can make reimbursement invoices.


### Fixed
- Fixed Edit Purchase Invoice save. The CSRF was not being sent in the request


## [1.232.2] - 2019-05-18
### Fixed
- Fixed functions that infer customer first and last names using the only name
supplied when creating it.
- Fixes bug in Invoice edit view that happened when an Invoice tried to get its
related product and this related product code was duplicated in the Catalog.


## [1.232.1] - 2019-05-17
### Fixed
- Corrects attribute name for cellphone number.


## [1.232.0] - 2019-05-16
### Fixed
- Correctly display location logo in view.


### Added
- Phone number attribute to Destinatario model.
- Considers contact's cellphone number when saving edoc.
- Waybill shows client's phone number.


## [1.231.1] - 2019-05-15
### Fixed
- Added Active Contract attribute to Intercom Company propierties.


## [1.231.0] - 2019-05-15
### Added
- Added Outstanding Invoices and Outstanding Amount to Intercom Company properties.


## [1.230.3] - 2019-04-30
### Fixed
- Fixed a bug in the edit Invoice option when trying to update an Invoice with
items that are out of stock and had no stock record.
- Fixed a bug in the middleware that checks the account usage. The bug showed
up when a request was made with an invalid API key. Now the correct 401 status
code is returned in the response.


## [1.230.2] - 2019-04-17
### Fixed
- Fixed bug in receipts. Before a cancelled receipt could be authorized.
- Ignore lack of stock at edit/create a draft invoice.
- Fixed bug at create/edit an invoice with items that are not in stock.
- Fixed bug at create/edit an invoice. Tip was calculated with subtotal without
global discount.


## [1.230.1] - 2019-04-16
### Added
- Fixed bug in dashboard. The total sales shown didn't consider the global discount.


## [1.230.0] - 2019-04-15
### Added
- Added filter by location. Before it was only possible to filter by points of sale, now
it has been separated to filter by location and points of sale.
- UI style fix in add/edit Invoice. Removed position absolute in tip switch and changed global discount side at left.


## [1.229.5] - 2019-04-14
### Fixed
- Fixed bug in invoice that appeared when global discount compare with subtotal
including discount instead of subtotal before discount.
- UI style fix in view Invoice. When the screen was reduced, the table with
invoice summary was overflow


## [1.229.4] - 2019-04-10
### Fixed
- Fixed bug that appeared when adding Products that have a price list to an
Invoice.
- UI style fix in add/edit Invoice. Tip and discount subtotals were shown in
2 lines instead of one.


## [1.229.3] - 2019-04-10
### Fixed
- Fixed bug at create invoice with ICE.


## [1.229.2] - 2019-04-04
### Fixed
- Fixed some bugs in Invoices and Credit Notes.


## [1.229.1] - 2019-04-04
### Fixed
- Fixed discount amount bugs in Invoices and Credit Notes.


## [1.229.0] - 2019-04-03
### Added
- Added a global discount field at edit or add an invoice. This additional discount will be
subtracted to the subtotal with 12% VAT.
- At generate a credit note the additional discount will be prorate to the items with 12% VAT.


## [1.228.2] - 2019-04-04
### Fixed
- Fixed item profit rate calculation in Invoice Inventory section.


## [1.228.1] - 2019-04-03
### Fixed
- Reduced the number of queries made to the database in the view document
public view. Defer loading of Location `can_be_deleted` attribute. The
implementation of the function `efactura.models.establecimiento` was optimized
by replacing unnecesary count() with exists()

### Added
- Added pre-commit which is a development tool to easily install pre-commit
hooks after cloning the repository. The configured hooks will automate Python
code formatting and linting.


## [1.228.0] - 2019-04-02
### Added
- Use of signals to deactivate payment reminder when invoice is paid.


## [1.227.6] - 2019-04-01
### Fixed
- Explicitly set cookie-related security settings to comply with PCI-DSS
- Fixed look and feel of public Invoice view page.


## [1.227.5] - 2019-03-29
### Fixed
- Fixes profit rate and profit margin rate calculations. Product discount where
not being taken into account.


## [1.227.4] - 2019-03-28
### Fixed
- Adds missing validation to prevent an invalid division error.
- Fixes Invoice item additional details control bug.


## [1.227.3] - 2019-03-28
### Fixed
- Adds missing validation to prevent an invalid division error.


## [1.227.2] - 2019-03-27
### Fixed
- Fixed an issue with the changes in the previous release.


## [1.227.1] - 2019-03-27
### Fixed
- Fixed an issue with the changes in the previous release


## [1.227.0] - 2019-03-27
### Added
- Added total cost, profit margin ratio and profit rate to the Invoice
Inventory section.

### Changed
- Changed column names to more appropriate ones for the transaction items in
the Invoice Inventory section.


## [1.226.1] - 2019-03-26
### Fixed
- A bug caused by an uninitialized variable


## [1.226.0] - 2019-03-21
### Fixed
- Removes auto number feature for documents added in previous version.
This feature added a huge amount of workload to the database causing the whole
system to crash. We will have to revisit the idea of how to implement this
constraints in another way.

### Added
- Added codes to inactive account and quota error responses. This will provide
more information on the cause of the error to API clients and the web app UI.


## [1.225.2] - 2019-03-18
### Fixed
- Fixed bug in core.invoice.models.invoice.create function.


## [1.225.1] - 2019-03-18
### Changed
- Related field "detalle" is now prefetched when needed.
- Added monthly spend param to IntercomCompanyData


## [1.225.0] - 2019-03-16
### Added
- Automatic document number feature added to Waybills, Debit Notes when
creating this types of documents via web service.

### Fixed
- Checks for document number uniqueness are stronger now. A new DB table for
each document type will help ensure document numbers do not repeat.
- Fixed auto-number for Invoices, Credit Notes and Withholdings. Since no
constraint enforced this at the DB level, if this feature was used and invoices
were sent in concurrent requests, duplicated numbers were generated.


## [1.224.1] - 2019-03-13
### Changed
- In stock per item report now all Catalog Items, with track inventory enanbled,
are displayed regardless if they have a Stock Record in the selected warehouse
or not.
- Adds logging for unhandled exceptions in task_enviocorreo.
- Display up to 6 decimals for the unit price when creating or editting a
Purchase Invoice.
- New optimization in filter Invoices function. The field representacion.xml
is deferred.

### Fixed
- Fixes bug in Kushki record payment function. Invioce balance was not being
updated after registering the payment.


## [1.224.0] - 2019-03-12
### Changed
- Uses serverless edoc signer


## [1.223.3] - 2019-03-12
### Fixed
- Optimizations for core.invoice.models.invoice.filter function use to to
list invoices.

### Changed
- Set default number of decimals to 6 when creating Purchase Invoice items


## [1.223.2] - 2019-03-10
### Fixed
- Fixed middleware that obtains account and its contract from session or
directly from DB when a request is received.
- Changed HTTP response code from 507 to 402 when a disabled account or an
account who has reached usage limit makes a request.


## [1.223.1] - 2019-03-09
### Changed
- Always return an accounts contract regardless of its status. This will fix an
issue in the subscription section when customers with inactive accounts try to
view their susbscription information.


## [1.223.0] - 2019-03-09
### Added
- Added cost field to Product view screen.
- Added cost column to stock per item report.
- Usage restrictions added to API.

### Changed
- Now imported e-invoices are not marked as paid. Payments are ignored.


## [1.222.0] - 2019-03-02
### Fixed
- Fixes bug that logged out users when trying to update their personal profile
- Changes order of "onboarding checklist"
- Improvements and fixes


## [1.221.4] - 2019-02-28
### Fixed
- Fixes unit price (average) calculation when increasing stock.
- Adds a new update_output_transaction function.
- Fixes rebuild inventory, input and output functions.
- Improves Product Stock history report by hiding quantity for cost adjustment
transactions.
- Fixes bug in stock per item report.
- Fixes a bug in Product edit form that caused track inventory setting to be
turned off when a user without inventory management privileges edited a product
that had inventory tracking on.


## [1.221.3] - 2019-02-22
### Fixed
- Improved Withholding tax get or create method.
- Ensure XML document exists before accessing it to delete it.


## [1.221.2] - 2019-02-22
### Fixed
- Fixes bug in middleware that checks account status. The error appeared when
an empty apikey was received.


## [1.221.1] - 2019-02-22
### Fixed
- Adds check to return a 401 error when a request made to API endpoints:
/enviosri, /autorizacionsri, /enviocorreo, and /consulta includes an empty API
key.
- Fixes product SKU uniqueness validation.

### Changed
- Removed code that created deals and contacts in HubSpot.


## [1.221.0] - 2019-02-21
### Added
- Option to send plain Account welcome email that includes password.

### Fixes
- Connect account creation endpoint now works as expected.


## [1.220.3] - 2019-02-13
### Fixed
- Fixes subscription screen for customers with unlimited plan.


## [1.220.2] - 2019-02-12
### Fixed
- Adds usage restriction for accounts with one point of sale.


## [1.220.1] - 2019-02-12
### Fixed
- Fixed bug from previos release


## [1.220.0] - 2019-02-12
### Added
- Account usage limit middleware to detect usage and display messages when the
customer reaches the plan limit.
- Tooltip for issued withholdings list and product list (Catalog).

### Fixed
- Fixed a bug in signup create customer process. It was not checking correctly
if the Contact already existed in our records before attempting to create it.
- Fixed session expired exception bug in update profile view.
- Catches Pago.DoesNotExist exception to prevent displaying an error when
someone attempts to delete an invoice payment that has been already deleted.
- Fixed import XML bug that happened when the tmp file was saved in one server
and the subsequent request that finished the import process took place in a new
server. It was fixed by using S3 for storing and retrieving this tmp file.

### Changed
- Set default pos code to 100 for customers of Glovo Connect.
- Added code to try decoding the uploaded contacts import file and accept files
encoded in other encodings that UTF-8.
- Improved error handling in Import Contacts feature.
- Style improvements to Account subscription section.


## [1.219.2] - 2019-02-09
### Fixed
- Temporarily undo PCI-DSS cookie-related security settings, until we
fix modules that depend on it.


## [1.219.1] - 2019-02-09
### Fixed
- Explicitly set cookie-related security settings to comply with PCI-DSS


## [1.219.0] - 2019-02-05
### Added
- Audit log feature added. This API will allow to log additions, changes and
deletions of any Django Model.
- Recent activity section added to document view to display actions captured in
the audit log.
- Added stock information to GET Product info web service endpoint.

### Changed
- Allow customers to set their certificate issue and expiration dates.
- Improves EC Withholdings edocs parser. Defaults to 01 when codDocSustento
is not found since we found these documents were accepted by SRI.

### Fixed
- Fixes update inventory transaction.

### Security
- Fixed validation so only owners of a Withholding can register it.
- Added validation so only owners of a Credit note can register it.


## [1.218.2] - 2019-01-29
### Fixed
- Fixes update inventory transaction.


## [1.218.1] - 2019-01-29
### Fixed
- Fixes search business in login screen
- Fixes VPOS transaction processing. Prevents duplicated payments from being
recorded.


## [1.218.0] - 2019-01-26
### Fixed
- Clean taxes before saving an Invoice. This will prevent invoices imported
from an XML to have duplicate Invoice total (TotalImpuestoFactura) records.

### Changed
- Adds EntidadTributaria as a foreign key of Custom print templates. This
change allows proper ordering of existing templates in the admin panel and
enables search by business name and tax ID.
- Trigger Invoice paid events regardless of its authorization status. Before
this change only invoices marked as authorized (Factura.autorizado = True)
produced the "invoice.paid" event. The problem with only taking into
consideration authorized ones was that sometimes SRI was not available but the
Invoice was sent to the customer and later paid.
- Display unit of measurement in Invoice print template by default.


## [1.217.1] - 2019-01-17
### Fixed
- Adds missing field to then new get edoc endpoint response.
- Fixed generate payment order function that arised when an invoice had more than
one "active" payment order.


## [1.217.0] - 2019-01-15
### Added
- New API endpoint to get electronic documents related information, such as
authorization, status, edoc URL, etc.
- Added missing link to Adjusment transaction in Product View dialog.

### Fixed
- Fixed a CSS bug introduced in a previous commit


## [1.216.0] - 2019-01-15
### Added
- New Export feature added to Inventory Item History screen.
- New Inventory Transaction view.

### Fixed
- Fixes an issue when creating Inventory adjustments. The description field
entered by our customers was completely ignored.


## [1.215.2] - 2019-01-14
### Fixed
- Now deactivates a reminder when invoice has been voided.


## [1.215.1] - 2019-01-14
### Fixed
- Fixes Waybill issue date bug. The start date is now used as the issue date.
- Fixes bug in new Profile update feature.
- Prevent the account from being deactivated when deleting the PFX certificate.
- SMTP configuration validation fix.


## [1.215.0] - 2019-01-12
### Changed
- Moved Configuration menu option inside Your Business.
- Added menu icon to the "Dátil Admin" option.
- Create Personal Profile page with password and user profile update


## [1.214.2] - 2019-01-08
### Fixed
- Fixes load Custom Print template logic.

### Changed
- Display issue date and expiration date fields when uploading PFX for everyone


## [1.214.1] - 2019-01-08
### Fixed
- Fix display of item list when creating and editing invoices.


## [1.214.0] - 2019-01-08
### Added
- Added new feature to Custom Print Templates. A different template can be set
as the email attachment.
- Added tooltip for customer name in Sales Invoices list.
- New column displaying link to Invoice in the Payment Orders list.

### Changed
- Removed DB constraint that restricted an Invoice to have multiple cancelled
payment orders.


## [1.213.2] - 2019-01-04
### Fixed
- Only generate inventory transaction for valid credit notes. When the Invoice
associated with a Credit Note did not generated an inventory transaction, no
inventory transaction will be generated for the Credit Note.


## [1.213.1] - 2019-01-03
### Changed
- Decreases wait time to fix docs


## [1.213.0] - 2019-01-03
### Changed
- Improved dead docs authorization backgound job. Now docs issued via web are
also considered.


## [1.212.2] - 2019-01-02
### Fixed
- Fixes year end report glitches.


## [1.212.1] - 2018-12-31
### Fixed
- Reverse incorrect change in factura.js.


## [1.212.0] - 2018-12-31
### Added
- 'venta_granel' to Product Model.
- Bulk sale when creating and editing invoices.


## [1.211.2] - 2018-12-26
### Fixes
- Validates if pending invoices exist


## [1.211.1] - 2018-12-26
### Added
- Improves account inactivation screen and copy.


## [1.211.0] - 2018-12-26
### Added
- Returns 507 HTTP error or "account deactivated" page when _contract_ is not active


## [1.210.0] - 2018-12-20
### Added
- Adds ability to specify customer car license plate field when creating an
Invoice via the REST API.


## [1.209.0] - 2018-12-06
### Added
- Adds ability to set a different print template for each point of sale (Esttablecimiento)


## [1.208.0] - 2018-12-05
### Added
- Add customer id to Datil document events


## [1.207.2] - 2018-11-28
### Fixed
- Purchases withholding's report correctly display data under headings.
- Bug while updating price when creating a debit note.


## [1.207.1] - 2018-11-23
### Fixed
- Fix key error in previous version.


## [1.207.0] - 2018-11-23
### Fixed
- Sets EmissionPoint min and max number to 0 and 999 accordingly.
### Added
- comprador_placa to Factura Model.
- Sales API extracts car plate from additional information.
- XML now adds <placa> </placa> tag.


## [1.206.1] - 2018-11-20
### Fixed
- Added "additional information" from Contacts in the CSV export file.


## [1.206.0] - 2018-11-17
### Added
- Add simplified onboarding checklist
- Add certificate request form (Jotform) in Configuration


## [1.205.2] - 2018-11-12
### Fixed
- Add 6 decimal positions to unit discount.


## [1.205.1] - 2018-11-09
### Fixed
- Fixes subsidy calculation when editting invoices via REST API.


## [1.205.0] - 2018-10-31
### Changed
- Adds new field to to contact form.


## [1.204.0] - 2018-10-31
### Added
- Adds a new button to toggle visibility of "Detalles adicionales" control for
Invoice create/edit form.


## [1.203.1] - 2018-10-30
### Fixed
- Inventory information is only displayed for users with the correct priviliges.


## [1.203.0] - 2018-10-25
### Changed
- Increments sku database field length in Inventory module, so it can store long codes produced by concatenating "codigoprincipal" and "codigoauxiliar".


## [1.202.0] - 2018-10-10
### Added
- New permission created to control if a user can view a Products inventory
information or not.


## [1.201.3] - 2018-10-06
### Fixed
- Fixes a bug in the signup process. For some businesses, datum doesn't return
the street address so a 'Key Error' was thrown.

### Changed
- Improves performance of the send_email function when sending the same template multiple times.
- Adds a back-end validation to the signup setup process to prevent having
EntidadTributaria and Cliente records with empty names.


## [1.201.2] - 2018-10-05
### Fixed
- Updates django-cors-headers to a later version that supports Django 1.9


## [1.201.1] - 2018-10-05
### Fixed
- Updates django-compressor to a later version that supports Django 1.9


## [1.201.0] - 2018-10-04
### Added
- New task auto send account statement to Datil customers.
- Validation for the RUC length. When a customer who has a RUC with more or
less than 13 digits, an error message is shown prompting them to update the RUC.
They will be taken to "Tu Negocio" screen so that they can complete update their
information.

### Fixed
- Fixes export Payments report bug. Environment was not taken into account for
the export report view.
- Restricts payment notes field to the max length of the field in the register
payment form.

### Changed
- Fixes a bug in reminders module. The scenario when the reminder is deleted
from the reminders service and not from datil-py database caused a recurring
error. This change fixes that bug.
- Upgrades Django to version 1.9! :tada:
- Upgrades djangorestframework to version 3.1



## [1.200.1] - 2018-10-02
### Fixed
- When filtering by payed,pending or due status only authorized invoices are return.


## [1.200.0] - 2018-09-27
### Changed
- New toolbar icons

### Added
- Marketing > Google Analytics section
- Add Google Tag Manager to all app templates

## [1.199.1] - 2018-09-16
### Added
- Redirect bad conversions (i.e. registration incomplete) to "/", before loading page.

## [1.199.0] - 2018-09-15
### Added
- Implement Google Tag Manager to deploy Analytics and Ad conversion tracking
- Add conversion landing page where users are directed after a successful signup


## [1.198.1] - 2018-09-12
### Added
- Fixes edit invoice option when location has no warehouse


## [1.198.0] - 2018-09-11
### Added
- Maintenance tasks to get authorization for docs "EN PROCESO" state and repair
the authorization status for docs that have authorization with AUTORIZADO status


## [1.197.2] - 2018-09-10
### Fixed
- Undo latest change, it was not needed
- Find existing customers in registration, only in Datilmedia S.A. account

## [1.197.1] - 2018-09-10
### Fixed
- Fix bug when creating a customer on account registration


## [1.197.0] - 2018-09-09
### Added
- Creates new Datil accounts as Contacts in Datilmedia S.A. account


## [1.196.1] - 2018-09-06
### Fixed
- Improves error messages when adding and managing credit cards.
- Fixes the credit card brand logo static link.


## [1.196.0] - 2018-09-06
### Changed
- Adds ability to store email templates in the database. The renewal
notifications now use this feature to be able to edit the template without
having the need to make a new release.


## [1.195.7] - 2018-08-31
### Changed
- Page count is now included as a parameter when exporting edocs through vulcan to modify job parameters accordingly.


## [1.195.6] - 2018-08-29
### Fixed
- Sign endpoint REST API fix. Response status was not 500 for unhandled
exceptions. Now it is.


## [1.195.5] - 2018-08-29
### Fixed
- Fix contact search when creating new purchases invoices
- Fix contact creation when issuing documents


## [1.195.4] - 2018-08-29
### Fixed
- Maintain the cliente.id property to not break the web interface
- Use the correct account id (Datil`s, not the customer´s)


## [1.195.3] - 2018-08-28
### Fixed
- Deletes extra unnecesary migration


## [1.195.2] - 2018-08-28
### Fixed
- Make customer uid optional


## [1.195.1] - 2018-08-28
### Fixes
- Changes were made to consider the fact that multiple EntidadTributaria can
have the same RUC. This changes prevent datil-py from thowing an exception and
continue with registering the invoice.
- CSS improvements
- Fixes subsidy total calculation: The total was not being correctly calculated
when an Invoice contained products with and with no subsidy.


## [1.195.0] - 2018-08-28
### Added
- Add UUID field to customer and use it in CRUD views
- Add UUID field to entidadtributaria, so we can link it to customers
- Add Payment Method section in Suscripción, integrated to Stripe


## [1.194.0] - 2018-08-27
### Added
- Adds a check in stock history view to automatically rebuild item inventory.
- Adds test session banner app-wide.

### Fixed
- Fixes model configuration based on Django warnings.
- Fixes Pagos list bug. List was not being filtered by environment.
- Attempt to fix celery beat daemon startup error.

### Changed
- Repositions dreaded Dashboard New Sale button.


## [1.193.0] - 2018-08-25
### Fixed
- Fixed a bug in crear nota de crédito REST view.
- Fixes a bug in Banco Pichincha payment order payment method in invoice.
Cancelled payment orders should not be displayed.

### Added
- New feature to cancel a Payment Order. This will allow a new order to be
generated.


## [1.192.1] - 2018-08-25
### Fixed
- Fixes supervisor.conf for recently added celery beats program.


## [1.192.0] - 2018-08-24
### Fixed
- Checks if it's an AJAX request to prevent duplicating messages.

### Added
- Server side render flash messages banner to prevent the screen from "jumping".
- Enables Celery Beat to periodically send certificate expiry reminders.
- Temporarily hides IVA tax from the sales by items report.


## [1.191.0] - 2018-08-23
### Added
- Added tasks to automatically notify customers that their certificate is
expiring soon.
- A new middleware that checks the certificate expiration date and displays a
flash message reminding them to renew their certificate.

### Fixed
- ICE tax was not being displayed in the register Invoice form
- Fixes setting bug in admin.


## [1.190.4] - 2018-08-21
### Changed
- Adds request information to unknown errors in account setup and login views
- Changed EntidadTributaria query for existing businesses in signup to prevent
errors. Our records have duplicate entries and this causes errors, this change
prevents this errors from happening.

### Fixed
- Now only if EntidadTributaria contract is active, the signup is considered as
repeated. Otherwise it should let the person signing up continue to use Datil.


## [1.190.3] - 2018-08-21
### Added
- Include price list when exporting catalog.

## [1.190.2] - 2018-08-18
### Fixes
- Fixes form labels font-size and font-weight.
- Adds missing translations and sets a fallback to prevent None ot be displayed
when no validations are found.


## [1.190.1] - 2018-08-17
### Fixes
- Bug not showing single price


## [1.190.0] - 2018-08-17
### Changed
- Updates to Django 1.8.19:
-- Adds templates in settings.py
-- Changes base loader
### Adds
- "Error" filter when exporting edocs.
- Support for price list for products.


## [1.189.12] - 2018-08-17
### Fixed
- Fixes a bug in edit Invoice form that appeared when editting an invoice whose
products descriptions has line breaks.
- Removes update token account to fix a signup issue.

### Changed
- Adds ability to edit the customer's email address in credit notes edit form


## [1.189.11] - 2018-08-16
### Fixed
- Making phone field not required


## [1.189.10] - 2018-08-16
### Fixed
- Signup form improvements:
-- Adds a new tax ID type field to the form.
-- One important improvement included in this release is the auto fill for
customers trying to download received documents.


## [1.189.9] - 2018-08-15
### Fixed
- Fixed import Purchase Invoice from XML dialog

### Changed
- Improved `ReceivedInvoiceParser` class and now an XML with no authorization
info is consider as valid, and escaped XMLs are now accepted too.

## [1.189.8] - 2018-08-14
### Fixed
- Adds back accidentally deleted filter params
- Adds missing subsidy calculation logic to edit invoice REST legacy API

### Changed
- Changes the middleware used by the products and categories REST endpoints to
be able to use the Master API key authorization feature.
- Improves payment order text copy


## [1.189.7] - 2018-08-14
### Fixed
- Fixes total subsidy calculation.


## [1.189.6] - 2018-08-13
### Fixed
- Fixes repeated new invoice form bug.


## [1.189.5] - 2018-08-13
### Fixed
- Add entity filter for Product search_by_code


## [1.189.4] - 2018-08-11
### Fixed
- Fixes invoice authorization process for invoice with ICE taxes.
- Fixes menu bugs.


## [1.189.3] - 2018-08-09
### Fixed
- Fixes `core.invoice.models.invoice.save` function.
- Hides "Nota de crédito" option for purchase invoice view.


## [1.189.2] - 2018-08-09
### Fixed
- Fixes export account payables option.
- Mail admins log setting restored. Exception emails are not being sent to
devops.


## [1.189.1] - 2018-08-09
### Fixed
- Adds missing require needed in advanced compilation mode so the compiler does
not exclude this lib.


## [1.189.0] - 2018-08-08
### Added
- New Accounts Payable by supplier report. This will be used in this release to
be able to show our customers their pending Datil service invoices. The next
release will include a complete version of this report that will replace the
current one.
- New Purchases app that includes invoices list for now. This new section is
still hidden and will be opened for beta testing later when some missing
features are added. The original purpose for this new section is to be able to
issue withholdings using the information already found in the Invoice. (alpha)
This new app includes:
-- Purchase Invoices list
-- Invoice view
-- Credit note view inside an invoice.
-- Withholdings view
-- Withholdings issue dialog inside Invoice view
- New CLJS based application using reagent and re-frame. Check app_cljs.html
and purchase_app.html templates for an example on how to add new features to
datil-py using ClojureScript.
- Added admin form for Units of measurement model.

### Changed
- Side navigation bar has a new closed look. Icons are shown while closed for
faster navigation between the app modules.
- Updates to Banco Pichincha payment orders. The bank reference number is now
a 10 digit random number that will allow to generate as many Payment Orders as
needed per Invoice without worrying about having to cancel them in the bank app
- Using new "Nunito Sans" font to replace Avenir for which we no longer have
rights to use.
- Buttons style changed from rounded corners to square with slightly rounded
corners.

### Fixed
- Fixes some style minor bugs in public invoice view.
- Retina images for non-webkit based browsers.


## [1.188.4] - 2018-07-31
### Fixed
- Fixes a couple of signup bugs.
- Fixes inventory bug when editting an invoice. Selected warehouse was not being
set when duplicating invoices and the stock info was not bein loaded correctly
when loading the edit invoice view.
- Really redirect free accounts to purchases list.


## [1.188.3] - 2018-07-30
### Fixed
- Redirect free accounts to purchases list.
- Fixed bug is export to CSV payments feature.

### Added
- The channel through which the document was created.


## [1.188.2] - 2018-07-25
### Fixed
- Fixes actions in documents list


## [1.188.1] - 2018-07-25
### Fixed
- Shareable link option fixed.


## [1.188.0] - 2018-07-24
### Added
- Adds payment options to Invoice PDF (RIDE)
- Copy shareable link to clipboard.
- Adds "Pay" button to received Invoice view

### Fixed
- Fixes duplicate invoice option bug.


## [1.187.0] - 2018-07-24
### Added
- Adds fast account switch link to Intercom company data.


## [1.186.1] - 2018-07-23
### Fixed
- Dashboard JSON serialization bug.


## [1.186.0] - 2018-07-23
### Added
- Adds ability to select the target point of sale when duplicating an Invoice.
- Restriction added to only allow credit notes to be generated for authorized
invoices.
- Adds "Marcar como anulada" and "Crear una copia" options to document viewer
toolbar.

### Fixed
- Fixes Point fo sale reservation feature when copying invoicess or generating
credit notes from invoices.


## [1.185.0] - 2018-07-19
### Added
- New validation settings section. This settings will allow customers to tweak
validation parameters (for documents issued via the API for now). This release
includes two new settings: *level* and *rounding mode*
- Adds support for saving documents with validation errors. Adds a new state
"Error" for invalid documents saved via API. Tables AutorizacionSRI and
MensajesAutorizacionSRI are used to store this validation messages.
- New status "Error" in status filter in the issued documents list.
- New auto height variation of dt-table-flex, use dt-table-auto-height

### Fixed
- Adds missing customer name column in payments report file.

### Changed
- Now the requirements dashboard card is shown while the account has no
certificate.
- Withholding percentage was removed from the line item description because
it was redundant and misleading when adding a variable percentage withholding.
- Sign errors are now saved too and the status of the document is set to "Error"
- Totals were added to inventory transactions section inside the invoice view.


## [1.184.1] - 2018-07-03
### Fixed
- Fixes a bug in Invoice viewer. The code that generates the list of inventory
transactions was not considering that the `Producto` record can be deleted
without restriction. This commit adds code to check if the product exists before
getting it from the DB.


## [1.184.0] - 2018-06-29
### Fixed
- Removes consumidor final ID type from Contact form.

### Fixed
- Fixes a bug in invoice edit option caused by not selecting the item stock
record based on the bodega_seleccionada invoice item field.


## [1.183.6] - 2018-06-29
### Fixed
- Warehouse picker in Invoice edit option.


## [1.183.5] - 2018-06-28
### Fixed
- Warehouse picker bug caused by ordering. The default (selected) stock record
is set using the first item of the list fo warehouses from that location. The
problem was that instead of sending an array of warehouses to the UI, a hash
map was used. Hash-maps do not guarantee order as arrays do.


## [1.183.4] - 2018-06-28
### Fixed
- Restored accidentally deleted CSRF token.


## [1.183.3] - 2018-06-28
### Fixed
- Fixes a bug added in previous release when singing documents


## [1.183.2] - 2018-06-27
### Fixed
- Fixes a bug in the Invoice viewer for customers with Inventory enabled.
- Fixes a bug in export received documents feature.

### Changed
- Mark document as pre-authorized when signing it in the web app.


## [1.183.1] - 2018-06-26
### Fixed
- Fixed awful bug in edit invoice.
- Fixed status filter in payment orders.

### Added
- Warehouse picker in Item inventory transactions report.
- Experimental improvement in login select page: Added search filter


## [1.183.0] - 2018-06-25
### Added
- New warehouse picker when adding an line item to an Invoice.
- Inventory transactions section inside the invoice viewer.

### Changed
- Disable validation on payment registration for payment orders
charge.succeeded received event.
- Added request information on unhandled exceptions in exception middleware


## [1.182.3] - 2018-06-20
### Fixed
- invoice.paid event was not being triggered after recording the payment upon a
successfull VPOS credit card payment.

### Added
- Customer name to payments list
- Wraps VPOS result processing inside a DB transaction.


## [1.182.2] - 2018-06-18
### Fixed
- Adds missing Order Payment status: Cancelled
- Fixes bug in create payment order batch viewFixes to_withholding
transformation function.
- Updates Invoice balance when processing VPOS payment.


## [1.182.1] - 2018-06-15
### Fixed
- Fixes to_withholding transformation function


## [1.182.0] - 2018-06-15
### Added
- De-duplication support for invoice create request via the REST API.

### Fixed
- Fixes to_withholding transformation function
- Fixes division by zero bug in my subscription section
- Fixes new Payments section JS dependencies bug


## [1.181.2] - 2018-06-14
### Fixed
- Fixed a to_credit_note function call


## [1.181.1] - 2018-06-14
### Fixed
- Fixed a runtime error added in the previous release.
- Fixes bug in function that calculates credit notes sequence.


## [1.181.0] - 2018-06-13
## Added
- List, filter and export registered Payments
- List and filter Payment Orders and create Batch file to send to the bank.
- Payments are shown in the public invoice view. This is part of the fixes
included in this release to support paying a partially paid invoice
- Adds new invoice.paid event.
- Adds admin screens for PaymentOrderBatch to allow ops team to set the batch
ID that is shown on screen after uploading the batch file

## Changed
- Improved PaymentOrder data model by adding the referece (Contrapartida) sent
to the bank. This new field will allow to match the received processed payment
order with the record that originated the PO.
- Improved notes formatting of Invoice payments section. Linebreaks are
replaced by <br> tags to

## Fixed
- Fixed PaymentOrder.from_invoice function. Now the Invoice balance is used
instead of the total.
- Fixes a format bug in new invoice notification template.
- Fixes in Invoice public template. Invoice balance is now used instead of
the total.


## [1.180.1] - 2018-06-13
## Fixed
- Export dropdown menu not being displayed correctly.

## [1.180.0] - 2018-06-12
## Added
- Export of documents in PDF or XML format.

## [1.179.0] - 2018-06-12
## Added
- Include location and POS "description" field in issued documents.

## [1.178.0] - 2018-06-01
## Added
- Banco Pichincha payment method
- New public Invoice view design oriented towards payments and not SRI
information.
- Improved access control for Credit Customer and Register Payments options
inside Invoice view


## [1.177.2] - 2018-05-30
### Fixed
- Added personal id param to Contifico integration request payload in an attempt
to fix the error.

## [1.177.1] - 2018-05-30
### Fixed
- Fixes send email task for customers with custom SMTP settings.


## [1.177.0] - 2018-05-29
### Changed
- Add setting in api to set legal name as default for sending email notifications.

## [1.176.1] - 2018-05-29
### Fixed
- Fixed Contifico integration customer type information was being sent wrong
when an Invoice was issued to a personal tax identification.
- Fixed reapply_transactions function to sort item transactions by date and id
to preserve the order they were processed in the first place.

### Added
- Added index to sujeto_identificacion field in efactura.Retencion table to
improve queries to Withholdings.


## [1.176.0] - 2018-05-28
### Fixed
- Fixed a bug when saving a password containing an special character gave a
Unicode Error.

### Changed
- SMTP configuration test uses same implementation as Hermes.

### Added
- A configuration option to enable the account to always send emails using the
business name.


## [1.175.0] - 2018-05-10
### Fixed
- Fixed a logo bug in waybill RIDE.

### Changed
- ORM related performance improvements to core.invoice.\_filter function.
- Only return invoice print log if specified in the `select_keys` parameter.
- PAGINATE_BY setting set to 100 by default.

### Added
- Added the ability to set PAGINATE_BY using the DJANGO_REST_PAGE_SIZE envvar


## [1.174.1] - 2018-05-08
### Fixed
- Adds customer ID length check to invoice, credit note and withholding
API endpoints.


## [1.174.0] - 2018-05-08
### Changed
- Sign document REST API endpoint now also marks the document as pre-authorized.


## [1.173.5] - 2018-05-03
### Fixed
- Fixes error logging in purchase invoices handler.
- Only include businesses with a valid email to the list of active businesses
that will receive the weekly summary email.


## [1.173.4] - 2018-05-03
### Fixed
- Improved active businesses query in an attempt to revive Weekly Summary report.


## [1.173.3] - 2018-05-02
### Changed
- Improved max height CSS and HTML of RIDE to make it work in al browsers.


## [1.173.2] - 2018-05-02
### Changed
- Fixes logo sizing issue in printable templates.
- Changes document recipient address DB field from CharField to TextField to be
able to store longer addresses since Contacts address book already stores
addresses in a TextField.
- Address field in xml/factura.html truncated to 300 characters which is the
maximum allowed by the IRS.
- Product SKU (código principal y auxiliar) field in xml/factura.html and
xml/notacredito.html truncated to 25 characters which is the maximum allowed
by the IRS for those fields.
- Regenerate representacionXML when viewing a document that has no
`representacion`. This usually this happens when there is overload in our
servers and things go out of whack.


## [1.173.1] - 2018-04-25
### Fixed
- Botocore version changed from 1.4.10 to 1.7.8 for AWS Batch support.


## [1.173.0] - 2018-04-25
### Added
- Adds print status filter to issued documents REST APIs.

### Changed
- Improved error logging in efactura/api.py and purchases/views/invoices.py
- Increased the length of the sujeto_direccion field in efactura.Retencion to
match SRIs XML schema. This was changed to be able to import some withholdings
that were throwing errors due to the field length.


## [1.172.0] - 2018-04-25
### Added
- Enables detailed item report for sales invoices.


## [1.171.0] - 2018-04-16
### Added
- Restores existing Returning vs Existing Customers Dashboard card. Now it can
be enabled using settings.


## [1.170.1] - 2018-04-16
### Fixed
- Fixed PFX certificate django admin form.


## [1.170.0] - 2018-04-10
### Changed
- Automatically calculate waybill sequence on save
- Save estado "EN PROCESO" in AutorizacionSRI table when no valid response is
returned from SRI.


## [1.169.1] - 2018-04-08
### Added
- Added a last "Totals" row in subscription documents usage section.

### Fixed
- Usage percentage in subscription section.

### Changed
- Finished changing wording from "Dispositivo" to "Caja registradora" in
"Tu negocio" section.


## [1.169.0] - 2018-04-08
### Added
- Adds new Billing/Subscription section to "Your Business" section.


## [1.168.0] - 2018-04-08
### Added
- Adds print log feature which helps keep track of how many times, by whom and
from where documents were printed.


## [1.167.0] - 2018-04-03
### Added
- New e-doc (XML) received Waybill import endpoint.
- New e-doc (XML) received Debit Note import endpoint.
- New list Purchases Invoices REST endpoint.
- New list Purchases Credit Notes REST endpoint.
- New list Purchases Debit Notes REST endpoint.
- New list Purchases Waybills REST endpoint.
- New list Sales Withholdings REST endpoint.
- Adds new field "legal_name" to later deprecate "business", "person" fields


## [1.166.0] - 2018-04-03
### Added
- Invoices API now returns subsidy value for product if it is not included in the request.


## [1.165.0] - 2018-04-02
### Added
- New edoc (XML) waybill import endpoint.


## [1.164.0] - 2018-03-30
### Added
- New save waybill function in core module.
- New endpoint to List issued Withholdings in purchases_service.
- New XML waybill parser and import feature.

### Changed
- Improves filtering for credit notes, debit notes and waybills in core.


## [1.163.2] - 2018-03-28
### Fixed
- Fixed bug in EcuadorDebitNoteParser class.


## [1.163.1] - 2018-03-28
### Fixed
- Fixed bug in core.withholding.models.withholding.save a try except block was
referencing non existing constant.


## [1.163.0] - 2018-03-27
### Added
- New Debit note parser and core API to save and list debit notes.
- Adds debit notes sales service endpoint to import edoc debit notes

- Adds select_keys feature to credit notes list function.
- New contacts_service app that provides a Contacts interface to the
old Cliente model
- Adds debit note issued and received events.

### Changed
- Improvements to EC Credit Note and Invoice parsers. Customer and Supplier
names and address are now unescaped to make sure they are saved correctly
in the DB.

### Fixed
- Contacts list search improvements. The "X" button for clearing the search
text works again. When searching and no contacts are found, a message is
diplayed, previously no message was shown.


## [1.162.1] - 2018-03-21
### Fixed
- Only display withholding items that belong to the invoice.


## [1.162.0] - 2018-03-21
### Added
- Allows editing customer address when issuing an invoice

## [1.161.0] - 2018-03-16
### Added
- Adds an account setting to choose which XML version will be emailed.

### Changed
- Send email task now checks xml version setting.


## [1.160.1] - 2018-03-15
### Fixed
- Style bug in Firefox Windows fixed in Issued Documents list.

## [1.160.0] - 2018-03-13
### Added
- Adds new endpoints to be able to import previously issued documents.
- New accounts REST endpoint for root access to account info
- New REST endpoint to import sales e-invoices
- New REST endpoint to import sales e-credit-notes
- New REST endpoint to import issued e-withholdings
- Adds support to Invoice parser to parse authorization XMLs.

### Fixed
- Fixes validation bug for Contacts identifications
- Fixes Invoice create bug. Tax was not skipped when supposed to
- Fixes a bug that prevented pasting the ID in the New Contact form


## [1.159.1] - 2018-03-07

### Fixed
- Adds invoice update balance function in some other missing places.


## [1.159.0] - 2018-03-07

### Fixed
- Invoice balance is now calculated for Invoices created via REST API.
- Fixes bug in Sales Credit Note inventory transaction.


## [1.158.0] - 2018-03-07

### Added
- Withholding views for exporting Sales Withholdings.
- Sales Withholdings are now exported using vulcan.

### Changed
-  Changed success message when exporting Sales Invoices reports.

## [1.157.4] - 2018-02-21

### Fixed
- Dealing with the fact that Invoices are duplicated.
- Fixes waybills filter function.


## [1.157.3] - 2018-02-19

### Fixed
- Error in Product transaction history.


## [1.157.2] - 2018-02-18

### Fixed
- Fixes overdue invoices filter, for good!


## [1.157.1] - 2018-02-18

### Fixed
- Fixed report filtering, environment is now being considered and grouping is
performed by customer tax id now.


## [1.157.0] - 2018-02-17

### Changed
- Reimplemented Accounts Receivable report using a DB view.


## [1.156.1] - 2018-02-17

### Fixed
- Fixes edit Invoice controller. Outstanding balance update was missing after
deleting payments.
- Fixes create Invoice function for Invoices with IVA PRESUNTIVO
- New attempt to fix overdue invoices filter.


## [1.156.0] - 2018-02-16

### Added
- In the previous version, an Invoice outstanding balance was calculated every
time it was needed. Now the field `efactura.models.Factura.saldo` keeps the
current balance, and it is calculated on every transaction that affects it:
Register Payments, Issue Credit Notes, Receive Withholdings.
- Ignore `TotalImpuestoFactura`s that have taxable_amount equal to zero.
- Adds filter by razonsocial to legacy Received Retencion JSON REST service.

### Fixed
- Fixes bug in inventory.output_transaction that was caused by stock check
routine. Negative inventory should always be allowed in order to support
creating transactions at any point in time.
- Fixes bug in inventory transactions that was caused when attempted to process
an Invoice with Products that were deleted from the Catalog.
- Fixes a bug in overdue Sales Invoices filter.



## [1.155.1] - 2018-02-13

### Fixed
- "Crear copia" and make Credit note hot fix.


## [1.155.0] - 2018-02-13

### Added
- A new web service endpoint to list issued waybils.
- Triggers new waybill.issued event after a Waybill is authorized by SRI.

### Fixed
- Fixes issues with void Inventory transaction. An exception was raised while
trying to void an inventory transaction. This issue was seen when an Purchase
Invoice was created with repeated products in multiple line items and then
edited. After fixing the previous issue, a new issue was detected that caused
a product to have an erroneous stock count after editing a Purchase
Invoice that had been previously edited. The field support_doc_date was
added to the Transaction model to be able to filter transactions using
this date when reversing stock and reapplying inventory transactions
during the voiding process.
- Fixed a UI inconsistency in Purchase Invoice form.
- Fixes a bug in the Accounts Receivable per Customer Report. Credit notes are
now considered as part of the `Factura.saldo_actual` function so it was
redundant to calculate credits again.
- Fixes bug in edit Invoice/Credit Note for products with & o quotes in their
names.
- Fixes a bug that made the logo in the notification email to look stretched.

### Changed
- Inventory Input and Output transactions received an upgrade. Now, before
increasing or decreasing stock for every item (Product) in the transaction, we
check for any previous or later transactions that include the item. The new
`Transaction.support_doct_date` field determines its place in time. And if
transactions later in time are found the items' (Product) stock is recalculated.
- Improves ConfirmDialog by adding the ability to guard against double click
on the confirm button.
- Changes Void input inventory transaction implementation. Now a new inverse
transaction is created to reverse the effects of the original transaction
instead of just restoring stock and marking it a VOIDED. Previous and new
inverse transactions are marked as ARCHIVED to present a clean transaction
history by default.


## [1.154.0] - 2018-01-27
### Added
- Adds back legacy (online) SRI mode XML download.

### Fixed
- Changes retrieve_by_tax_id fn to stop preventing docs from being authorized.



## [1.153.0] - 2018-01-18
### Changed
- Allow voiding documents even when they are not authorized
- Make email optional when creating customers
- Expand ICE decimal places to 6
- Now receipts are always signed except when they are authorized

### Fixed
- ICE is now calculated correctly when applied to IVA 0 products
- Fixes UTF-8 bug when issuing documents

## [1.152.0] - 2018-01-17
### Added
- Max length constraints added to waybill number in Purchase Invoice form,
custom SMTP port number, and invoice item additional details.
- Waybills now have an HTML notification email template like Invoices, Credit
Notes and Withholdings do.

### Changed
- Sign API endpoint regenarates and signs XML even if already signed. This only
happens if the document has not been authorize yet.
- Download XML endpoint now downloads the stored XML document, the authorization
wrapper has been completely removed.
- base print template font size changed to 9pt.

### Fixed
- Subtotals in Invoice notification email are only displayed if the
"show subtotals" option is enabled.
- The annoying double click bug in the login company select screen is gone for
good.
- Fixes an SRI authorization bug that appeared when creating a Credit Note from
an Invoice that has products with both codigo auxiliar and codigo principal and
both concatenated together are longer than 25 characters.



## [1.151.6] - 2018-01-17
### Fixed
- Add support for automatic sequence when issuing credit notes


## [1.151.5] - 2018-01-16
### Fixed
- Sets the Kushki environment correctly, based on the invoice environment

## [1.151.4] - 2018-01-10
### Fixed
- The function for calculating the next sequence for Invoices, Credit Notes,
Debit Notes and Waybills now considers the arbitrary sequence settings.
- Fixes `core.invoice.api.related_credit_notes` to filter related credit notes
by environment. Adds environment filter to
`core.credit_note.models.credit_note._filter`.
- Fixes Business Profile logo section. The logo is displayed again and the
button to delete it is back!


## [1.151.3] - 2018-01-05
### Fixed
- Fixes invoice payment confirmation alert bug


## [1.151.2] - 2018-01-04
### Fixed
- Fixes sales report export using the safer get method from dict.
- Fixes Purchase Invoice create/update by limiting the authorization number
form field to 49 characters, since that's the maximum length allowed in the
database field.


## [1.151.1] - 2018-01-04
### Fixed
- Validates that only invoices use the payment gateway functions


## [1.151.0] - 2018-01-04
### Added
- Support for paying invoices with Kushki payment gateway


## [1.150.6] - 2017-12-20
### Fixed
- Fixes sales by items report. Credit notes items were not being added correctly


## [1.150.5] - 2017-12-14
### Fixed
- Fixes bug when downloading pdf.


## [1.150.4] - 2017-12-04
### Fixed
- Fixes Waybill RIDE.
- Adds missing validation to withholding create API.


## [1.150.3] - 2017-12-01
### Fixed
- pyopenssl version frozen to 17.4.0 because 17.5.0 introduced some breaking
changes.


## [1.150.2] - 2017-11-30
### Fixed
- Reimbursement document total fixed.


## [1.150.1] - 2017-11-29
### Changed
- Reimbursement documents totals are displayed per document now, before they were
grouped and displayed at the end of the list of all the documents.


## [1.150.0] - 2017-11-28
### Changed
- Adds rounding to withheld value calculation. Uses the rounding setting of the
business.


## [1.149.2] - 2017-11-25
### Fixed
- Fixes inventory untested code


## [1.149.1] - 2017-11-24
### Fixed
- Fixes division by zero bug in void input transaction.


## [1.149.0] - 2017-11-24
### Fixed
- Adds missing subtotals and taxes for Invoice Reimbursements

### Changed
- Allows negative stock to be able to edit Purchase Invoices.


## [1.148.5] - 2017-11-23
### Fixed
- credit note XML item tax rate tag is optional. The parser previously considered it as required and it failed importing e-credit-notes when this tag was missing.
- Contract is saved as active on signup. Previously it was saved as inactive and this caused unexpected errors for customers on a trial plan.
- Payment status dot color fixed. The status name was correct but the dot color wasn’t


## [1.148.4] - 2017-11-22
### Fixed
- Inventory adjustment screen fixed. Was not working correctly and the issue only
happened for businesses with more than 2 warehouses.

## [1.148.3] - 2017-11-16
### Fixed
- Function `efactura.models.estado_pago` now considers the current balance in order
to determine the payment status. Before this change an Invoice with a Withholding
or Credit Note associated to it was displayed as pending.


## [1.148.2] - 2017-11-10
### Fixed
- `core.withholding.models.withholding.retencion_to_withholding` and
`core.credit_note.models.credit_note.nota_credito_to_credit_note` conversion
functions fixed. Authorization information was not included.


## [1.148.1] - 2017-11-07
### Changed
- Upgrades psycopg2 version to 2.7.3.2.


## [1.148.0] - 2017-11-07
### Added
- Releasing async Sales Invoices download to everybody.

## [1.147.0] - 2017-10-25
### Added
- Adds new Stock recount inventory adjustment transaction.

### Fixed
- Fixes a UI titlebar bug in Windows. Horizontal scroll bar was shown always
not only when really needed.


## [1.146.1] - 2017-10-25
### Fixed
- Fixes bug in Product View. The dialog was not rendering for inventoriable
products with no Stock records.


## [1.146.0] - 2017-10-20
### Added
- Adds status filter to Dashboard. Created a new static function in
`efactura.models.Comprobante` that contains all the logic required to filter
documents by status.

### Fixed
- Fixes layout issue with Transportistas list view.
- Fixes ACL menu bug. Dashboard option menu was shown even for users with no permission to see the Dashboard.
- Fixes encoding issue in Export received Withholdings option.


## [1.145.1] - 2017-10-19
### Fixed
- Fixes issued debit note list layout issues.


## [1.145.0] - 2017-10-18
### Changed
- Moved "platform" endpoints to its own submodule called "connect"

### Added
- Added signing certificate upload endpoint


## [1.144.2] - 2017-10-18
### Fixed
- Fixes sales by products report. The Products list was no being filtered by
business.
- Received Invoices report fixed. All types of VAT are now extracted from
TotalImpuestoFactura


## [1.144.1] - 2017-10-17
### Fixed
- Fixes inventory adjustment dialog. Decrease inventory was not working

## [1.144.0] - 2017-10-17
### Added
- Product core api new `stock_info` and `fields` parameters added to `catalog_service.product.api.list` that allow to include/exclude
product stock information and return a subset of fields of each Product.

### Fixed
- Sales Report fixes and edit Credit Note form fixes.

## [1.143.3] - 2017-10-16
### Fixed
- Fixed select all documents checkbox issue.

## [1.143.2] - 2017-10-16
### Fixed
- Layout issue in product edit screen.
- Filter by category in Products API see `catalog_service.product.views.products._request_params_to_filter_params`

## [1.143.1] - 2017-10-16
### Fixed
- Layout issue in issued documents list.
- Layout issue in Purchase Invoice Form.

## [1.143.0] - 2017-10-16
### Added
- Filter Sales report by Category.

### Fixed
- When editting an Invoice, the product_id was set to null for the unchanged
products.
- Restored check for selecting multiple documents from the issued documents
list.

## [1.142.1] - 2017-10-15
### Fixed
- Login screen scroll fixed.

## [1.142.0] - 2017-10-13
### Added
- A new section for managing Devices.
- A new view for the list of issued documents.

### Changed
- Allow to adjust inventory in all the available warehouses.
- Relocated Locations (Establecimientos) to Business & Account (Tu Negocio)
section.
- Relocated Business Profile (Mi Negocio) to Business & Account (Tu Negocio)
section.
- Section Mi Negocio was renamed to Tu Negocio and now includes Business Profile
Locations and  Device management tabs.
- Application layout complete overhaul. Now most of the screens use the new
layout that places the navigation aside the section title. Filters and actions
are now part of the content.
- Ditched the mobile menu and the mobile version uses the same menu as the
desktop app.

### Fixed
- The correct validation message is shown when updating an Invoice and trying to
set the due date prior to the issue date.
- Fixes lots of layout details that were broken for small screens.

## [1.141.1] - 2017-10-13
### Added
- Include both authorized and not authorized documents when downloading received documents.

## [1.141.0] - 2017-10-05
### Added
- Support for fixed rate ICE taxes.
- Shows taxes (ICE and VAT) in order when viewing invoces and credit notes
- Sanitizes newlines from buyer address in invoices

### Fixed
- Fixes bugs when issuing invoces and credit notes with ICE

## [1.140.3] - 2017-10-03
### Changed
- RIDE view now receives 'screen' parameter.
- Receipt url for htmlToPDF now uses 'screen' parameter.

## [1.140.2] - 2017-10-02
### Fixed
- Credit note parser was missing `person` entry in `customer` key when customer type was not business.
- Inventory service client was not correctly serializing data and that caused
some exceptions.
- Inventory API function was updated in a previous release but another function
that depend on it was not updated accordingly.
- Logging call bug fix. Data format changed and the function `index` was not
able to find the item in the array
- Updates reimbursement dictionary transformation function to match the
final spec.
- Updates invoice view to correctly export using payed status filter.

## [1.140.1] - 2017-09-28
### Fixed
- Adds exists check for related object `Reimbursement` to consider invoices
that don't have this information.


## [1.140.0] - 2017-09-28
### Added
- Support  for Ecuador Invoice Reimbursement info by adding new data
structures related to the Invoice (Factura). New DAO objects in `efactura.models`:
Reimbursement, ReimbursementDocument, ReimbursementDocumentTax

### Fixed
- Fixes authorization task bug that caused a weird message to be shown
to the customer when issuing a document to another Datil Business that
had no API key.
- Fixes bug in edit Invoice via REST API, now the `propina` field is
updated.
- Removes Invoice payments validation in edit invoice REST API.

## [1.139.4] - 2017-09-27
### Fixed
- Fix syntax error in lista.html introduced in previous commit.


## [1.139.3] - 2017-09-27
### Changed
- Enables async export for invoices.

## [1.139.2] - 2017-09-26
### Fixed
- Edit Invoice bug fixed. This bug was caused by a JSON serialization error.
Since `catalog.services.InventoryService` class is now using the
`inventory_service` modules directly and not the REST API, some of this data is
not in string anymore.

## [1.139.1] - 2017-09-25
### Fixed
- Products bug in query view (`productos.py`).

## [1.139.0] - 2017-09-25
### Added
- Access Control Logic for the Reports section.

### Changed
- Products stock in now retrieved in batch when getting the list of available
products in the legacy view `efactura.productos.view`.
- Some of the functions implementations in
`catalog.services.inventory.InventoryService` are now using the Warehouse and
Stock api directly instead of using the `inventory_service` REST API
- htmlToPdf lambda params format changed


## [1.138.0] - 2017-09-23
### Added
- Disables outstanding balance validation in REST API.

### Fixed
- Improves printable templates font size units are now in points (pt).


## [1.137.0] - 2017-09-22
### Added
- API endpoint to create platform accounts.

## [1.136.2] - 2017-09-18
### Fixed
- Fixes `trigger_post_auth_withholding_events` function. A Withholding has a
`recipient` and not a `customer`

## [1.136.1] - 2017-09-15
### Fixed
- Excludes Sales Invoices issued to customers with Tax ID type License Plate (PLACA)
from the query to generate the Accounts Receivable report


## [1.136.0] - 2017-09-13
### Added
- Adds a new type of adjustment transaction, it’s called the cost adjustment
transaction. Use this new adjustment transaction to overwrite the unit price
of an item Stock record.

### Fixed
- Withholding view fixed. `efactura.models.Retencion.numerodocumentosustento_formato`
function was not considering this value could be None. The same happened when
the template tried to format recipient email address and since some documents
are imported via XML, not all the information is available in the electronic
document (XML)

## [1.135.0] - 2017-09-13
### Added
- Adds events triggers when approving Credit Notes and Withholdings.

### Fixed
- Fixes void Inventory Transaction to support multiple line items of the same
product by associating `StockHistory` with Transaction `Item`
. This new
relation between a Transaction Item and a StockHistory record is necessary to
support adding the same product (item_id) to multiple line items.
- Wraps save Purchase Invoice view with `transaction.atomic` block to
prevent the Invoice from being saved if something fails with the
Inventory module.
- Adds validation to WarehousePicker when creating/editing a Purchase
Invoice to prevent sending invalid data to the server

## [1.134.0] - 2017-09-11
### Added
- Adds product options to Product REST service.
- New product options model. Create, query and delete ProductOptions.
- Add documentation for product options.

### Fixed
- Fixes accounts receivables report bug of double discount for a credit note.

## [1.133.2] - 2017-09-10
### Fixed
- Fixes Credit Note tax totals bug. Tax totals were not being updated
when editing, or even created when creating a new Credit Note
- Fixes Invoice Copy feature, Invoice item product ID was not being
copied to new Invoice.
- Fixes Invoice Edit view which was not considering the “producto_id”
could be None.
- Fixes catalog_service middleware, it now considers inactive accounts
and prevents them from accessing the API.
- Attempts to fix bug in “autorizacion_sri” task when the response from
the SRI did not contain the field “numeroComprobantes”.
- Contifico integration fix for Invoices addressed to foreign
businesses.
- Fixes typos in Credit Note and Copy Invoice messages.

## [1.133.1] - 2017-09-09
### Fixed
- Invoice downloads in CSV/Excel did not work

## [1.133.0] - 2017-09-08
### Changed
- Allows you to print draft documents from the list view.
- Print actions display the "ride" view instead of a plain PDF.

## [1.132.1] - 2017-09-05
### Fixed
- Fixes Inventory bug that appeared when using coding auxiliar and dashes

- Now the `inventoriable_items` methods tries to find the product using
its UUID if present, otherwise it uses the SKU as before.
- Splits SKU into maximum 2. This at solves the issue of getting by SKU
when using codigo_auxiliar with dashes and codigo_principal with no
dashes. A future release will include a new SKU field in the product
table to completely solve this issue.

### Added
- Automatically generate business API key upon registration.

### Changed
- XML download uses the authorization template whenever an auth number is found.
- Authorization date in XML authorization template changed to ISO8601 date format

## [1.132.0] - 2017-09-01
### Added
- Support for Presumptive withholdings (Retención presuntiva) when importing
Invoices.
- New import received Withholding that does not require location ID

### Fixed
- Import Received Withholding bug introduced in previous release.

## [1.131.0] - 2017-09-01
### Added
- New import electronic Purchase Invoice endpoint
.
- Import operation is now inside a db transaction :)

### Changed
- Ignore payments when importing Invoices if payments have errors.
- Show pre-authorized Purchases Invoices in the list of Invoices.

## [1.130.0] - 2017-08-29
### Fixed
- Fixes bug in authorization task raised when trying to get the Datil account
from Invoice recipient (Customer) to trigger the INVOICE_RECEIVED event.

### Added
- New API endpoint to register payments. New view
`sales_service.invoice.views.payments` and core API function
`core.invoice.api.register_payments`
- Adds new option to export Received Invoices including products.

## [1.129.2] - 2017-08-29
### Fixed
- Fixes triggering an event for business with no API key.
- Fixes `core.invoice.models.invoice.get` function broken in previous release.

## [1.129.1] - 2017-08-28
### Fixed
- Updates the conversion according to spec. These two documents were not
following the “Next” spec.
- Fixes `core.credit_note.models.credit_note.get` function to make it actually
return a Credit Note.
- Secures `core.invoice.models.invoice.get` adding business id as a filter.
Only owner, recipient or issuer should be able to get a given Invoice.
- Secures `core.withholding.models.withholding.get` adding business id as a filter.
Only owner, recipient or issuer should be able to get a given Withholding.
- Fixes `list` methods of `purchases_service.services.credit_note` and
`purchases_service.services.invoice`.
- Removes '"' from filename when downloading a documents' XML or PDF file.

### Added
- Endpoints for triggering INVOICE_RECEIVED and CREDIT_NOTE_RECEIVED events.
These endpoint will probably transform into something else, but for now we need
them until this event model is completely established and events are treated as
entities.

## [1.129.0] - 2017-08-28
### Changed
- Updates events module to the new spec.
- Payments methods table header name updated from "Pagos" to "Método"

### Added
- An INVOICE_RECEIVED event is triggered when a Business issues an
Invoice addressed to another Data Business.

## [1.128.1] - 2017-08-25
### Changed
- Fixes get invoices API endpoint. Now correctly returning paged results instead
of full query set.

## [1.128.0] - 2017-08-24
### Added
- New API endpoint to get invoices applying filters.

### Changed
- Export invoices feature enabled for superusers.


## [1.127.9] - 2017-08-23
### Fixed
- Fixes bug in Inventory Service which prevented an Invoice to register multiple
Inventory transactions. This scenario happens after performing multiple edits in
a Purchase Invoice.


## [1.127.8] - 2017-08-22
### Fixed
- Fixes division by zero bug in Inventory service void transaction


## [1.127.7] - 2017-08-15
### Fixed
- Fixes get active businesses API endpoint. Now uses total sales card to check
if the business has had any activity during the given period.


## [1.127.6] - 2017-08-14
### Fixed
- Fixes weekly report that broke with a change in the previous version that
started considering the session environment setting to display the Dashboard
information.

### Changed
- Adds business_name field to every item in API that returns a list of
businesses which recorded activity during a given period. It also improves
performance by getting only the active businesses from the DB.
- List of active businesses now supports a business with no user associated to
it. When no user is associated to the business it uses the business email
address.


## [1.127.5] - 2017-08-07
### Fixed
- Fixes `core.credit_note.models.credit_note._credit_note_header` function.
Customers of type Person were not being considered when creating or updating
the document.


## [1.127.4] - 2017-08-07
### Fixed
- Fixes weekly report that broke with a change in the previous version that
started considering the session environment setting to display the Dashboard
information.
- Invoice viewer fix for small screen devices.


## [1.127.3] - 2017-08-04
### Fixed
- Fixes Ecuador Credit Note XML parser. Last update introduced a bug when
replacing the data structure used for item properties. In the previous version
a dictionary represented the properties, now the standard is to use a list of
dictionaries. Each property is represented by a dictionary with keys `name` and
`description`


## [1.127.2] - 2017-08-03
### Changed
- Improved error reporting on Exceptions for purchases_service, catalog_service
and sales_service.


## [1.127.1] - 2017-08-03
### Fixed
- Adds fallback value when no returns info is returned from the database.


## [1.127.0] - 2017-08-03
### Added
- Create a credit note from an Invoice. See `core.invoice.api`
- Added `outstanding_balance` field added to Core Invoice model.

### Changed
- Using keepachangelog.com conventions for changelog writing.

### Fixed
- Allow to send emails when a document is in draft status.
- Fixes payment date timezone issue.
- Invoice and Credit Note `save` functions now consider more information to get
or create Supplier (Business) information.
- Fixes bug in catalog_service.product.get function which was not
considering codigoauxiliar empty or NULL condition.
- Now take into account test session setting in Dashboard report.
- Improves Warehouse not found logging message in inventory service.
- Fixes waybill view template. Action buttons were being shown twice.

### Removed
- Removes unused product model from catalog app. The model logic and
store management was moved completely to the catalog_service app


## 1.126.3 - Jul 31, 2017

* Adds back email error log on unknown exceptions in import received documents
endpoints.
* File system safe XML and PDF names on download.


## 1.126.2 - Jul 21, 2017

* Fixes import received Withholdings and Credit Notes API bug

* Fixes accounts receivable report summary bug.


## 1.126.1 - Jul 20, 2017

* Fixes bug that caused a 503 response to be returned instead of a 400 error
with the error message when trying to import an already existing document.
* Adds casts to integer in XML parsers to ensure the right tax code is returned
from the parser.


## 1.126.0 - Jul 19, 2017

* Adds DELETE Category API endpoint
* Replaces base64 barcode image in RIDE with the image URL.
* Adds credit due date to the Printable document version (RIDE)
* Fixes bug in send email with PDF function.
* Fixes UI bug after approving a previously rejected document. The status name
changed to “Autorizado” but it remained in red.
* Improvements in Documents additional information component.
* Ignores payments information when importing Invoices which payments total is
greater than the Invoice pending balance.


## 1.125.2 - Jul 17, 2017

* Fixes environment filtering bug in Withholdings and Invoices.


## 1.125.1 - Jul 17, 2017

* Adds delete endpoint to Product REST API and fixes bugs

* Fixes Product API create/update function. SCT (ICE) tax was not being saved.
* Credit note create/edit forms rounding fix. The bug was evident when
specifying an item quantity of more than 2 decimal places.
* Removes subtotal and taxes columns from Credit note create/edit forms.


## 1.125.0 - Jul 15, 2017

* Makes Products and Categories list API endpoints return result set with links
to next and previous pages.


## 1.124.2 - Jul 15, 2017

* Fixes PDF rendering issues.


## 1.124.1 - Jul 15, 2017

* Fixes bugs in Withholdings list filter function and view PDF controller.
* Improved look of document viewer toolbar.
* Improves styling details about document printable view.


## 1.124.0 - Jul 14, 2017

* Adds the ability to save the Product Image via the REST API
* Bug fixes in Product create API
* Adds selective Product update. Now it’s just necessary to send the
information that needs to be updated.
* Replaces the old HTML to PDF service with the new API Gateway+Lambda


## 1.123.1 - Jul 12, 2017

* Fixes query filters used to get Invoice related Withholdings and Credit Notes.
* Removes VPOS invoice payment button from the actions toolbar


## 1.123.0 - Jul 12, 2017

* Adds related Credit notes and Withholding to the Invoice viewer

* Adds new Withholdings and Returns totals to the totals summary
section in the Invoice viewer.
* Improves document viewer. A new actions fixed toolbar was added. This
new bar is responsive and makes taking actions over a document faster
by improving actions visibility.
* Adds a new Document status label in the top section of the document.
Will be shown right next to the correct status labels: Pagada, Prueba
* Officially introduces the documents “draft” status. This status will
be shown in the documents list and viewer.
* Hides VAT and total from Invoice and Credit note line items.
* Simplifies Invoice and Credit notes subtotals and totals in document
viewer.
* Adds a new django custom template filter: format_currency.
* Adds new buttons class with icons: /dt-btn-icon.dt-btn-icon-text
* Fixes payment status filtering bug.
* Rollsback change to export invoices feature until further notice.


## 1.122.0 - Jul 4, 2017

* Changes in invoice view for report generation.
* Exporting invoices is now done through sales/services/report


## 1.121.1 - Jul 4, 2017

* Fixes a Catalog bug for customers with Inventory enabled.


## 1.121.0 - Jul 3, 2017

* Product get REST API.
* Category get REST API.
* catalog app is now using a product and category from catalog_service through
a client defined in catalog/services/product and catalog/services/category


## 1.120.0 - Jun 29, 2017

* Adds create Product API endpoint (next data spec).
* Improves flash message animation.
* Improves Invoice create copy feature.


## 1.119.0 - Jun 29, 2017

* Automatically populate the product catalog from new invoices
* Fixes bugs in sales invoice XML import
* Adds business settings query API endpoint


## 1.118.0 - Jun 27, 2017

* Adds sales invoice XML import API endpoint
* Adds business settings API endpoint (view only)


## 1.117.2 - Jun 27, 2017

* Fixes create invoice copy feature.
* Fixes create Invoice API to respond to export validations with 400 status.


## 1.117.1 - Jun 26, 2017

* The plan choice is now registered with the plan code.
* Add the personal plan with value $8,00 and 50 documents.
* Add the lite plan with value $16,00 and 100 documents.
* Add the pro plan with value $34,00 and 1000 documents.


## 1.117.0 - Jun 23, 2017

* New make a copy invoice feature.
* Fixes invoice parser after core invoice functions update.
* Fixes export sales function.
* Improvements to import catalog script.
* Adds payment and document status to received documents list.
* Attempts to fix bug that causes an authorized doc to be shown as not yet authorized.


## 1.116.5 - Jun 22, 2017

* Fixes bug in create POS on signup process.


## 1.116.4 - Jun 21, 2017

* Fixes payment terms customer validation.


## 1.116.3 - Jun 21, 2017

* Fixes 404 page by adding the request context to it.


## 1.116.2 - Jun 21, 2017

* Adds compress offline context variables to fix compress task
*
Improves product name line break cleaning to prevent the Invoice XML from
being rejected by the SRI.


## 1.116.1 - Jun 21, 2017

* Relocate bootstrap in app.html file.


## 1.116.0 - Jun 19, 2017

* Adds ability to toggle environment for the whole user session.

All the documents will be filtered by the environment type set for the current
session. Toggle environment also affects the create document options.
* Adds “description” field added to Point of sale entity.
* Adds a new Device entity to store information about a device
associated to a point of sale.
* Adds ability to edit customer email address when creating an Invoice.
* Fixes dashboard sales card calculations.


## 1.115.27 - Jun 19, 2017

* Validate on the adding and editing invoice form.
* If the user select credit payment has to select a saved customer.
* Change environment type in signup process.
* Save canonic number on purchase invoice import.


## 1.115.26 - Jun 16, 2017

* Fixes export sales report bug.
* Fixes Contacts list bug.


## 1.115.25 - Jun 16, 2017

* Urgent fix in authorization process.


## 1.115.24 - Jun 16, 2017

* Exclude the final customer identification in query report.
* Change the position of sort values invoice dataframe line.


## 1.115.23 - Jun 15, 2017

* Admin: Contracts are now searchable by Business name or Tax ID.
* Adds PFX token entity to the admin site.
* Changes how auth task deals with AutorizacionSRI related object
.
* Fixes regression bug in app recurring charges.


## 1.115.22 - Jun 12, 2017

* Fixes bug in accounts receivable report when there's any credit notes.

## 1.115.21 - Jun 12, 2017

* Improve the accounts receivable report.
* Refactor code in the export accounts receivable report to csv or excel.
* Improve login-logo css class for small devices.
* Define "numerodocumento" in credit invoices like a database index.
* Add bootstrap to catalog page.


## 1.115.20 - Jun 11, 2017

* Adds "Nota de Venta" to supported documents for withholdings.
* Fixes copy and URLs in the configuration panel.


## 1.115.19 - Jun 10, 2017

* Improvements for small screen devices.
* Adds "Received documents" section to the menu.
* Adds due date validation to import XML invoice dialog. Due date can only be
equal or greater to the issue date.
* The issue date of the Purchase Invoice that is being imported is now shown
below the invoice number.
* Removes extra spaces from info sent to the API when creating an Invoice.


## 1.115.18 - Jun 6, 2017

* Fixes a bug in register when a location address field in the datum response is empty.


## 1.115.17 - Jun 6, 2017

* Fixes a bug in import purchase Invoice from XML.
The import Invoice dialog allows the user to enter the email of its supplier. This email was being used to complete the business profile.
Most of the times customer specified an invalid email address which lead to a strange Business (EntidadTributaria) profile. Now the email address entered by the user is only used to create the new Contact record in their address book


## 1.115.16 - Jun 5, 2017

* Fixes Sales by items report. Not considering not authorized invoices or
credit notes and now considers the correct list of credit notes and considers
credit notes issued in a date outside the selected date range.
The date range should only apply to the Invoices.


## 1.115.15 - Jun 5, 2017

* Adds models to allow Businesses to be grouped.


## 1.115.14 - Jun 2, 2017

* Hide issuance type dropdown from issuance point creation form.
* Add validation rule to purchase invoice. If the supplier has an international
ID don't validate the format number.
* Fixes signup bugs with establishment address save.


## 1.115.13 - Jun 1, 2017

* Fixes a bug in invoice edit option. This bug appeared when the product had an
empty SKU (código principal).


## 1.115.12 - Jun 1, 2017

* Sign function raises a generic Exception for unrecognized exceptions
returned by the signer (factora).


## 1.115.11 - May 29, 2017

* Fixed bug on invoice payment
* Type field in create product form is now required. And the jquery code that
added css classes and removes the product type first line in create product form
was removed.
* Fixed document authorization status.


## 1.115.10 - May 29, 2017

* Fixes bug in edit category, when user click the cancel button reset the
dialog filters.
* Inventory adjustment fixed when quantity input is empty, on submit add error
message and remove it when the user define a valid quantity. Close #1008


## 1.115.9 - May 23, 2017

* Save the matriz information stored in SRI in the business details.
* Save the address of each establishment stored in the SRI.
* Add a 5 seconds timeout to the datum request in register section.


## 1.115.8 - May 25, 2017

* Fixes logging error.


## 1.115.7 - May 25, 2017

* Fixes API bug. Presence of 'total_impuestos' was not being checked.
* API: Adds more information to the general exception catch log.
* Updates Market section wording in product form.


## 1.115.6 - May 25, 2017

* Validates if country is null before getting the ISO code.


## 1.115.5 - May 23, 2017

* Updates EntidadTributaria model to make apikey field unique.
* Fixes send email task
.
* Fixes iOS Safari modal bug
. Closes #993 and Register payment dialog lay
over positioning placement fixed too.


## 1.115.4 - May 23, 2017

* Add overflow rule to table-responsive class for small devices
* Remove background image in the withholdings mail
* Fixes bug with size in the sales points dropdown filter


## 1.115.3 - May 23, 2017

* Fixes bug in api where duplet was not being returned when signing document.
* Fixes issue where emails did not send when using SMTP due to incorrect from address.


## 1.115.2 - May 20, 2017

* Fixes bug in catalog searching.
* Update style in the catalog edit dialog.
* Allow edit the fiscal period in withholding form.
* Save the description field in creation product form.


## 1.115.1 - May 20, 2017

* Optimizes digital certificate requirements list.


## 1.115.0 - May 20, 2017

* Add query API endpoints for purchase invoices, issued withholdings and received withholdings.


## 1.114.0 - May 19, 2017

* New Print option in the list of documents actions.
* Renames credit note field to homogenize names with Withholdings.
* Updates account activation requirements in Dashboard.


## 1.113.2 - May 19, 2017

* Fixes typo added in last commit.


## 1.113.1 - May 19, 2017

* Removes recently added fields to RepresentacionXML


## 1.113.0 - May 17, 2017

* Improves document query performed through RepresentacionXML using the nombre
field.
* Fixes stock check process that failed when any of the products in the invoice
had no stock record.
* Code optimization. Replaces the abusive use of
`representacion.comprobante()` with a variable `comprobante` that has already
assigned the result of the `comprobante` function.
* Adds validation to prevent a document from being signed more than once.
* Shows a expired certificate message when trying to sign a document with an
expired certificate.
* Displays the real status of the document while being processed.


## 1.112.2 - May 16, 2017

* Removes debug alert.


## 1.112.1 - May 15, 2017

* Fixes dialog window to mark a Waybill as cancelled.


## 1.112.0 - May 15, 2017

* Allow empty in the sku product input.(#981)
* Update the name in the report download file. (#990)
* Update tax period on witholding validation. (#988)
* Update balance in payment modal in invoice. (#992)
* Fixes bug when document detail was zero. (#1001)
* Adds missing properties field to Invoice list query REST endpoint.


## 1.111.1 - May 8, 2017

* Fixes a bug where email status was not being updated.
* Fixes status name calculation function.


## 1.111.0 - May 6, 2017

* Emits an event when an Invoice is authorized.


## 1.110.0 - May 5, 2017

* Adds support for custom SMTP configuration when sending attached document in
PDF format in email.
* Automatically send email when authorizing documents in bulk.
* Fixes REST API. Automatic rollback was broken in a previous release.
* Fixes bug in catalog when the sku product is empty.


## 1.109.2 - May 2, 2017

* Login screen fixes for small screen devices.


## 1.109.1 - May 2, 2017

* Fixes a bug in the edit product form
. When editing a product that was
configured with inventory enabled true and had no stock record caused the edit
validation to behave incorrectly. This commit fixes that behavior by adding a
previous is track inventory enabled field.
* Validates codigo_documento_sustento exists when creating a Withholding.


## 1.109.0 - May 1, 2017

* Login page face lift.


## 1.108.2 - Apr 28, 2017

* Since the UI is already displaying a document as Authorized before it has
been sent to the SRI the option to send the notification email should be
enabled. This update enables that option.


## 1.108.1 - Apr 28, 2017

* Adding extra validation to check if a document has an XML associated to it.


## 1.108.0 - Apr 28, 2017

* Fixes Product Viewer bug on accounts with inventory tracking disabled.
* Pre-authorized documents are shown as Authorized.
* Sign document dialog wording changed to Authorize document.
* The email is automatically sent to the customer after the document is
authorized.
* Removes hideous checks that indicated the issuance process.
* Adds a new email sent icon with a tooltip indicating the date the
first email was sent.
* Style improvements to the documents list toolbar for smaller screens.
* Adds support for submitting the Authorize document dialog form with
an enter keypress.


## 1.107.15 - Apr 25, 2017

* Query optimization.


## 1.107.14 - Apr 24, 2017

* Purchase Invoice API invoice with subsidy support fix and items taxes bug fix.


## 1.107.13 - Apr 22, 2017

* API create invoice optimization.


## 1.107.12 - Apr 20, 2017

* Get Invoice information API fixed.


## 1.107.11 - Apr 18, 2017

* Security fix in get invoice, get withholdings, get waybills, get credit notes,
get debit notes.
* Fixes the HTTP status response when an exception occurs.


## 1.107.10 - Apr 17, 2017

* Fixes inventory transaction bug that prevented from creating an inventory
transaction when selling concurrently from the same warehouse.
* Includes "ambiente" tag in authorization XML download.


## 1.107.9 - Apr 14, 2017

* Fixes timezone problems by downgrading the Ubuntu image


## 1.107.8 - Apr 13, 2017

* Available description in product details


## 1.107.7 - Apr 13, 2017

* Use older working Ubuntu image


## 1.107.6 - Apr 13, 2017

* Use older working Ubuntu image


## 1.107.5 - Apr 13, 2017

* Update Docker image to a newer version of Ubuntu
* Install locales modules in Ubuntu


## 1.107.4 - Apr 12, 2017

* Generate surnames correctly for document (invoices and credit notes) queries.


## 1.107.3 - Apr 11, 2017

* Increases the length of the authorization of the related document for Waybills.


## 1.107.2 - Apr 11, 2017

* Rolls back previous release.


## 1.107.1 - Apr 11, 2017

* Credit note API error log.


## 1.107.0 - Apr 11, 2017

* SRI Offline authorization support


## 1.106.1 - Apr 7, 2017

* Replacing "Payment methods" with "Payments" in New Invoice Payments section.


## 1.106.0 - Apr 7, 2017

* Ability to set rounding mode for Invoices and Credit Notes.


## 1.105.4 - Apr 6, 2017

* Inventory adjustment fixes.


## 1.105.3 - Apr 2, 2017

* Fixes some REST API error messages.


## 1.105.2 - Apr 2, 2017

* Fixes send email with PDF attachment feature.


## 1.105.1 - Apr 2, 2017

* Fix import in emails.py


## 1.105.0 - Apr 1, 2017

* Adds SQS message writing capability to email delivery service.


## 1.104.8 - Mar 31, 2017

* Extending the length of Invoice properties description field.


## 1.104.7 - Mar 30, 2017

* Signup fix, accounts should be owner by default.


## 1.104.6 - Mar 29, 2017

* Update market URL to .market TLD.


## 1.104.5 - Mar 29, 2017

* Fixes Credit Note Item property field serialization in REST API.


## 1.104.4 - Mar 28, 2017

* Adds customer information to GET Credit notes API response.


## 1.104.3 - Mar 28, 2017

* Adds credited document information to GET Credit notes API response.


## 1.104.2 - Mar 28, 2017

* This version extends the length of the email field for Credit Notes, Invoices
and Withholdings.

## 1.104.1 - Mar 27, 2017

* Inventory stock check bug fix.


## 1.104.0 - Mar 26, 2017

* Improves error messages in import contacts feature.
* Updates core documents dictionary attributes to match specs.
* Fixes add/edit Contact form validation bug.
* Adds missing environment attribute to Factura to invoice transformation.
* Inventory support for the issue invoice web service. This will enable POS
customers to use the inventory tracking feature.

## 1.103.1 - Mar 23, 2017

* Fixes bug that prevented from setting initial stock in zero.
* Using documents types catalog to validate related document type.


## 1.103.0 - Mar 21, 2017

* New API endpoints to get all sales invoices and credit notes.


## 1.102.3 - Mar 10, 2017

* Limit to 15 the amount of additional information added in the XML.


## 1.102.2 - Mar 10, 2017

* Business phone data received after parsing the XML could be longer that the
DB field max length.
* Increases max length of EntidadTributaria email address field.
* Fixes bug when deleting purchase invoice.
* XML parser improvement: Propina is an optional field.


## 1.102.1 - Mar 10, 2017

* Fixes to JS validation bug in tokenization form.


## 1.102.0 - Mar 9, 2017

* Product name length increases to 300.


## 1.101.0 - Mar 9, 2017

* Adds more strict form validations when creating tokens.
* Duplicate cards for the same merchant are not allowed.
* Improves template code by using tags.
* Filters tokens by the user who create them.
* Does not compress JS code for validations. It does not work when compressed.


## 1.100.1 - Mar 8, 2017

* Contifico integration bug fix


## 1.100.0 - Mar 7, 2017

* Extending the length of Credit Notes details (reason) field.
* Market activation form bug fix.
* Added ability to change issue date when creating invoices.
* Includes the number when editing an Invoice via API
* Explicitly sets timezone to SRI authorization information.
* Saves documents XML without spaces.
* Adds new fields to emails sent log table to be able to log the attempt to
send to invalid email addresses.


## 1.99.2 - Mar 6, 2017

* Added token creation date column.


## 1.99.1 - Mar 6, 2017

* Added scrolling to tokens list.
* Added back button after creating new token.


## 1.99.0 - Mar 6, 2017

* Added payment methods to Sales Invoices query API.
* Payment Methods can now be enabled or disabled.


## 1.98.0 - Mar 6, 2017

* Adds validations to recurring charges token creation form
* Adds token list


## 1.97.2 - Mar 2, 2017

* Fixes a bug that caused documents of customers who use their own SMTP server
to be marked as sent even when an error occurred.


## 1.97.1 - Mar 2, 2017

* Filter and split waybill addresses emails correctly, this time is for real.


## 1.97.0 - Mar 2, 2017

* New API endpoint to get Sales Credit Notes with the new Datil Next data format.
* Putting back "END CONSUMER" tax ID type as part of the available types.
* Waybill printable format bug fix.
* Invoice item now includes the Product UUID.


## 1.96.1 - Mar 1, 2017

* Public organizations tax ID validation bug fixes.


## 1.96.0 - Feb 28, 2017

* Gets barcodes service URL from environment variables.
* Old receipt HTML templates were deleted.

## 1.95.6 - Feb 27, 2017

* More tax ID validation bug fixes.


## 1.95.5 - Feb 25, 2017

* Tax ID validation bug fixes.


## 1.95.4 - Feb 25, 2017

* Considers EC tax id numbers which third digit is 6 as valid.
* API: Added missing discount fields to Invoice response.


## 1.95.3 - Feb 24, 2017

* Market page activated message update.


## 1.95.2 - Feb 24, 2017

* Filter and split waybill addresses emails correctly.


## 1.95.1 - Feb 22, 2017

* Validates a business association to an account


## 1.95.0 - Feb 22, 2017

* Market setting is necessary to display this menu option.


## 1.94.0 - Feb 21, 2017

* Add proof-of-concept recurring charge tokenization


## 1.93.1 - Feb 17, 2017

* This version removes the sendgrid backend.


## 1.93.0 - Feb 17, 2017

* Dashboard updated with the new UI language.


## 1.92.4 - Feb 15, 2017

* Fixes the duplicated creation of a business after the signup is completed.


## 1.92.3 - Feb 15, 2017

* Debit note field length fix.
* Waybill XML improvement. Replacing line breaks with empty spaces for `<campoAdicional>`


## 1.92.2 - Feb 14, 2017

* Fixes in core save document functions.


## 1.92.1 - Feb 13, 2017

* Removes additional info and additional details check from XML parser
* Fiscal period fields back in the game in Withholdings.
* Makes affected document number and date optional in withholdings.
* Fixes bug that caused a Withholding to be saved with no items when an error occurred while saving the withholdings’ items.
* Improves Withholding validation. Affected document is optional for
some types of documents.


## 1.92.0 - Feb 13, 2017

* This version removes the article section from the dashboard.


## 1.91.5 - Feb 11, 2017

* Fix in Credit Note item save function.
* Fixes Inventory error when not enough stock is available for some products
in a sale with multiple items.
* Waybill item Quantity now matches Invoice item quantity field size.


# 1.91.4 - Feb 9, 2017

* Returns an accurate error code (username or email already exists) to the
signup form in datil.co


## 1.91.3 - Feb 7, 2017

* Fixes NotaCredito to Credit Note (dict) transformation function.
Document URL fields were not placed correctly.


## 1.91.2 - Feb 6, 2017

* Existing username and email error handling for the signup.


## 1.91.1 - Feb 6, 2017

* Fixes an error in Contacts export to CSV feature.
* Catalog super users bug fixed.
* Register Payment dialog fixed.


## 1.91.0 - Feb 5, 2017

* The start of user groups and permissions for Datil User accounts :)
* The Dashboard is only visible to business owners.
* New upgrade hook management command.


## 1.90.9 - Feb 4, 2017

* Automatically adds a withholding tax to the catalog if it does not exist to
prevent the service from crashing.


## 1.90.8 - Feb 2, 2017

* Support for tag "moneda" being optional in Invoices and Credit Notes XMLs.
* Improved error reporting for import electronic documents APIs.


## 1.90.7 - Feb 2, 2017

* Fixes Ecuador XML date parsing function in Withholdings and Credit Notes.


## 1.90.6 - Feb 2, 2017

* Temporary measure to bypass a bug.


## 1.90.5 - Feb 2, 2017

* Fixes Ecuador XML date parsing function.


## 1.90.4 - Feb 2, 2017

* Increased size of Waybills' additional information fields.
* Automatically removing line breaks from some of the fields in the waybill XML
to prevent the document from being rejected by the IRS.


## 1.90.3 - Feb 1, 2017

* Fixes Invoice and Credit note XML parser.


## 1.90.2 - Feb 1, 2017

* Adds issue date to the response when importing e-docs.


## 1.90.1 - Feb 1, 2017

* Import APIs bug fixes.


## 1.90.0 - Jan 29, 2017

* New purchase Credit Note REST API to import electronic Credit Notes.
* New sales Withholding REST API to import electronic Withholdings.


## 1.89.0 - Jan 28, 2017

* New purchase invoice REST API to import electronic invoices.
* Accounts receivable report export fix.
* Catalog bug fix that prevented the product list from loading when some
product had no main code (codigo principal).
* Temporarily removed customer stats cards from the dashboard.
* Bug fix in Market activation option.


## 1.88.2 - Jan 24, 2017

* Fixes the logo field in the location api response.
* Fixes a market activation bug. It works like a charm again.


## 1.88.1 - Jan 23, 2017

* Fixes point of sale error in cash register


## 1.88.0 - Jan 22, 2017

* Adds locations information to the /api/v2/account response.


## 1.87.0 - Jan 20, 2017

* Market activation


## 1.86.7 - Jan 18, 2017

* Security fix.
* Fixes in Locations and Points of sale administration.


## 1.86.6 - Jan 18, 2017

* Email and appointment url changed in the requirements card.
* Fixes an bug in Purchase Invoice import feature. Nothing big, but important.


## 1.86.5 - Jan 16, 2017

* Purchase Invoice duplicated invoice validation error.


## 1.86.4 - Jan 16, 2017

* Removes shipper name from Waybills list.


## 1.86.3 - Jan 15, 2017

* Inventory adjustment exception handling fix.


## 1.86.2 - Jan 11, 2017

* Sales documents list UI fixes.


## 1.86.1 - Jan 11, 2017

* Fixes a location issue when a user signs up.


## 1.86.0 - Jan 11, 2017

* Batch invoicing use invoice pending reminder with invoice model now.
* Fixes in Purchase Invoice form.
* VAT Subtotal and VAT amount are now displayed correctly when exporting
Purchases to CSV or Excel.
* Fixes a bug that appears when a customer had inventory previously enabled
and then it is disabled. An additional check was added to only perform
Inventory transactions if track inventory setting is enabled.
* Style improvements to Purchases and Sales lists.
* Search by supplier in Purchase documents now supports case insensitive search
* This little update adds support for the number field in the api response for
a receipt.
* Adds location information to the documents view and printable (RIDE)
templates. Previously address, phone and email information was obtained from
the point of sale (efactura.models.Establecimiento).
* Fix on sign up file
* Tests for location updated.
* Document type added to Invoice table (efactura.models.Factura)
* Fixes in web pos, replaced deprecated function that queried a list of
points of sale.
* New API endpoint to get Sales Invoices with the new Datil Next data format.
* Fixes some saving issues related to a product image.
* The product image is shown in the product viewer.
* Adds missing column product SKU to exported file (CSV and Excel) of
sales by items report.
* Adds withheld values specified when creating an Invoice.


## 1.85.1 - Jan 5, 2017

* Fix in get product by SKU function.


## 1.85.0 - Jan 5, 2017

* New feature that will allow you to select a rounding method.
The rounding method could be set to round before tax calculation or after tax
calculation. This will give you the ability to play with unit price decimal
precision to get to the total price you expect to charge your customers.


## 1.84.5 - Jan 4, 2017

* Fix, schedule pending payment reminder only for authorized receipts and
deactivate reminders when the invoice is paid.


## 1.84.4 - Jan 4, 2017

* Fixes edit sales invoice when Inventory tracking is not enabled.
* Fixes tip calculation bug in Sales Invoice.


## 1.84.3 - Jan 4, 2017

* Fixes inventory stock check bug.
* Case insensitive search in Purchases.


## 1.84.2 - Jan 4, 2017

* Fixing Edit Sales Invoice that broke in previous release.


## 1.84.1 - Jan 4, 2017

* Displays stock information when editing an Invoice.
* Bug fixes in stock check validation when creating and authorising an Invoice.
* Issued documents list UX fix. Recipient column is highlighted in all other
documents, not just Invoices.


## 1.84.0 - Jan 3, 2017

* The 2017 came with a little surprise. The void receipt dialog has been
updated and now it doesn't present an error after setting a receipt as void.
* Fix, delete Purchase Invoice dialog was not being displayed correctly.
* Fix, Purchase Invoice Product search. Products with no unit cost information
were causing an error and the auto complete list.
* Year End Dashboard adapted for small screens.


## 1.83.0 - Dec 31, 2016

* Year end dashboard :tada: :smile:


## 1.82.0 - Dec 28, 2016

* Ability to register Purchase Invoice from foreign suppliers.
* New social media and business website information can now be specified for
every business Location.


## 1.81.0 - Dec 23, 2016

* Increased maximum password length for custom SMTP settings.
* Now SMTP settings can be specified using environment variables.


## 1.80.5 - Dec 22, 2016

* Store item unit of measurement received from the API.
* Make labelled export information available for the RIDE.


## 1.80.4 - Dec 22, 2016

* The link to see how to mark as void a receipt was broken. This update
fixes it.


## 1.80.3 - Dec 19, 2016

* Inventory service: Get all stock from warehouse fix.


## 1.80.2 - Dec 16, 2016

* View invoice API, add export invoice detail in view.
* Create and edit invoice API, make countries fields optional.
* Batch invoicing, no credit detail when invoice total is zero.


## 1.80.1 - Dec 16, 2016

* The latest version broke the catalog. This update fixes it.


## 1.80.0 - Dec 14, 2016

* New Checkout structure for the POS.
* Multiple payment methods in the POS.
* Value is automatically set in the selected payment method.
* The plans card style was broken. This update fixes it and the card is great again.


## 1.79.4 - Dec 13, 2016

* Fix issue that prevented Catalog Products with no SKU from displaying.
* Fixing broken links for production and test enviroments, and payment methods.
* Selecting the API Key is available again from the settings menu.


## 1.79.3 - Dec 9, 2016

* Loading indicator is displayed again in Accounts Receivable and Stock reports.


## 1.79.2 - Dec 7, 2016

* Catalog filter fix.
* Create Invoice style improvements.


## 1.79.1 - Dec 6, 2016

* Withholdings edit fixed.
* App wide style fixes and improvements.


## 1.79.0 - Dec 6, 2016

* All new Catalog section. Browser and search your products faster.
* Create categories to organise your catalog!
* App look and feel refresh.
* Accounts Receivable per Customer report now displays correct information.
* Sales by items report error fixed.
* Fixed UI bug in invoice payment reminders section.
* Now you can specify tip amount when registering a Purchase Invoice.


## 1.78.1 - Dec 2, 2016

* Trigger payment event synchronously (without using Celery).


## 1.78.0 - Dec 1, 2016

* Credit Note solidarity compensation.
* Debit Note solidarity compensation.


## 1.77.0 - Dec 1, 2016

* Add schedule reminders in massive invoicing.
* Sync payments via dispatcher when the invoice is created via API or Panel.
* Endpoint to sync invoice payments via dispatcher.


## 1.76.3 - Nov 30, 2016

* XML invoice Parser fixes


## 1.76.2 - Nov 30, 2016

* Locations and Points of Sale management fixes and improvements


## 1.76.1 - Nov 30, 2016

* Signup bug fix.


## 1.76.0 - Nov 29, 2016

* Added support for creating export Invoices via the API.
* Visual improvements in Locations list.
* Fix in xmlparser, now we validate that "contribuyenteEspecial" node exists first


## 1.75.4 - Nov 27, 2016

* Inventory error caused the change in Locations and Points of Sale was fixed.


## 1.75.3 - Nov 25, 2016

* Improvements and fixes in Locations management.


## 1.75.2 - Nov 25, 2016

* The plans shown inside the app were not the same as those shown in datil.co.


## 1.75.1 - Nov 24, 2016

* Customer phone number is now displayed in the invoice viewer and printable
invoice format.


## 1.75.0 - Nov 22, 2016

* Invoice solidarity compensation.
* Fix optional waybill fields validation before saving the receipt.


## 1.74.0 - Nov 22, 2016

* Logic of a location and a point of sale now is separated and they have different models
* A Location has zero or more points of sale (pos)
* You can't delete a location or pos if have any document associated to it
* You can't edit a location or pos *code*  if have any document associated to it


## 1.73.1 - Nov 22, 2016

* Prioritize retention tax percentage received via API
* Fixed delete Purchase Invoice. Inventory transaction result was no being
interpreted correctly and this was preventing the Invoice from being deleted.
* Format long emails in document viewer and print template to avoid a long
email to be displayed outside the print area.


## 1.73.0 - Nov 15, 2016

* Improvement, pending payment reminders is now implemented like a external service.


## 1.72.0 - Nov 14, 2016

* API, using semicolon as emails separator is also supported now.


## 1.71.1 - Nov 11, 2016

* Customers with Inventory tracking enabled were not able to edit Purchase
Invoices, this has been fixed.
* Improved error messages in Purchases.
* Selecting a product from the catalog while registering a Purchase Invoice,
now sets the product's cost correctly. Previously the unit sales price was used
instead of the unit cost.
* Bringing back Download dropdown button.


## 1.71.0 - Nov 10, 2016

* The field codigoPrincipal is not required anymore.
* Fix, allow edit only for manually entered purchase invoices.

* The Pay button is not displayed for void invoices anymore.
* Invoice current balance is set as the default pay amount when registering a
payment.
* Allow super users to delete the PFX file.
* Display if a supplier is a special taxpayer in the contact list search.


## 1.70.0 - Nov 8, 2016

* New custom document print templates! :tada:
* New document status filters.
* Manage Business settings in the administration application.


## 1.69.0 - Nov 7, 2016

* Bug fix in send notification email.
* Price with subsidy is not required anymore when creating a product.
* New edit button in document viewer.
* Upgraded credit note notification email template.


## 1.68.2 - Nov 7, 2016

* Fix, get email customer from customer list of issuer business when issue
invoices for plans


## 1.68.1 - Nov 7, 2016

* Print button is back. The document PDF is used for printing again.


## 1.68.0-beta2 - Nov 1, 2016

* Fix debit note xml structure and api response after issued.


## 1.68.0-beta1 - Nov 1, 2016

* Attach printable PDF version of the document to the notification email.
* Print is dead.


## 1.67.1 - Nov 1, 2016

* Increase user length  to 100 in email configuration.


## 1.67.0 - Oct 31, 2016

* Improved opening stock import script.


## 1.67.0-beta4 - Oct 30, 2016

* Fixed bug that prevented customers from adding or editing products.


## 1.67.0-beta3 - Oct 29, 2016

* Fixes in initial inventory form validation.


## 1.67.0-beta2 - Oct 28, 2016

* Fixes and improvements in initial inventory


## 1.67.0-beta1 - Oct 28, 2016

* Many of our customers had asked us for a long time for a way to
adjust their inventory with reality, and we have finally given life
to our new monster, please welcome to Frankenste-inventory Adjustment.
* Our new inventory feature is getting some more love, you can now set
your inventory in hand when adding a new product to the catalog.


## 1.66.3 - Oct 27, 2016

* Fixed bug that prevented products from being added to the POS sale


## 1.66.2 - Oct 27, 2016

* Fix, invoice with products with unit price of one million can now be saved.


## 1.66.1 - Oct 25, 2016

* The maximum number of products listed when creating an invoice has
changed to 50.


## 1.66.0 - Oct 21, 2016

* New additional information component for all receipts! Responsive, allows
commas and no enter required.


## 1.65.1 - Oct 19, 2016

* The maximum number of products listed when creating an invoice has
changed to 30.


## 1.65.0 - Oct 19, 2016

* Some of our customers required to preset additional information so that it
could be preload in all invoices. This new feature will be available in the
settings page. Also, every additional information can be deactivated for later
reuse.
* Improved ordering in API products endpoint.
* Display products sorted by name in stock report.
* Fixes: the information shown in the final card of the signup process, was not
shown in the dashboard if a business had no active contract.


## 1.64.0 - Oct 18, 2016

* Customers are now able to filter and export sales by items report by sales
representatives.


## 1.63.0 - Oct 17, 2016

* Inventory service create warehouse fix, validate that only one default
warehouse per location is saved.
* Inventory service create warehouse bug fix. The warehouse was created but the
service was returning a 500 response.
* New loading indicator for all the application.
* Payment methods got a bit smarter. The invoice balance is set as the default
amount for the first pament added to the list.


## 1.62.0 - Oct 13, 2016

* Units of measurement have arrived to Dátil! Now the customer has the option
to select a unit of measurement for a product. This unit will be visible in
the catalog, webPos, sale, product viewer and in the stock per item report
* The SignUp final card has been updated with relevant information.


## 1.61.1 - Oct 12, 2016

* Don't require payments information when the Invoice total is zero. This will
happen when granting a 100% discount on the sold products.


## 1.61.0 - Oct 11, 2016

* Api endpoint to sync authorized invoices via dispatcher
* Fix, reminder of payments gets back in invoice visualization.


## 1.60.9 - Oct 10, 2016

* Products export bug fix, export was not working when tags where null.


## 1.60.8 - Oct 10, 2016

* Products export bug fix to support non ASCII characters. The CSV now includes
purchase price, inventory enabled, and tags fields.


## 1.60.7 - Oct 10, 2016

* Bug fix in inventory_service that appeared after refactor.


## 1.60.6 - Oct 9, 2016

* Removed email log when not bein able to send email.


## 1.60.5 - Oct 7, 2016

* Inventory service improved validations and returned error messages.


## 1.60.4 - Oct 5, 2016

* Intercom integration bug fix for new account with no Contract.


## 1.60.3 - Oct 4, 2016

* Updates Intercom.io integration to the latest spec
* Fixes customer spend and billing periodicity data that is reported to intercom


## 1.60.2 - Oct 3, 2016

* Inventory validation fix when selling.
* Replacing old XML documents table.


## 1.60.1 - Oct 3, 2016

* Fix, delete "iva_compra" field of product correctly.


## 1.60.0 - Oct 3, 2016

* Script to allow import Products from a CSV file.
* UI Fix and speed improvements in stock by items report.
* Fix, check if the customer enters the authorization number before attempting
to save the authorization information for an invoice.
* Security fix in Purchase Invoice list.


## 1.59.0 - Sep 30, 2016

* To be, or not to be, that is the question... The Point of Sale was having some
existencial issues and Invoices where not being saved at all, but everything is
OK now. He's issuing Invoices as he is meant to be.
* Automatically remove line breaks from product name in XML to allow invoices
to be authorised and keep the line breaks in the product description for
presentation purposes.
* Just display businesses that are our customers when a Datil super user logs in
* Correctly edit Invoices with price with subsidy via the API.
* Adds OpenGraph Tags so we are more visible on THE FACEBOOK.
* The fields "channel", "owner_record" and "doc_type" are saved when issue
electronic receipts.
* Fix when try to save purchase invoice


## 1.58.0 - Sep 29, 2016

* Adds demo registration form linked to HubSpot
* Updates Kombu and Celery versions
* Purchase invoices can now be edited and deleted. Inventory is updated
accordingly too.
* Received receipts can now be seen in the demo app.


## 1.57.0 - Sep 29, 2016

* Point of sale picker bug fix in Sales by Item report.
* Inventory void transaction.


## 1.56.0 - Sep 28, 2016
* Inventory improvements and fixes.
* Dashboard point of sale filter fix.


## 1.55.3 - Sep 27, 2016

* Received receipts toolbar fix.


## 1.55.2 - Sep 25, 2016

* And the balance is restored to the datilverse! The long ago lost ability to
search contacts by tax ID, commercial name or email is back.
* What's past is past they say, but payment terms due dates are one misterious
time travelers. Payment terms due date can past dates now as long as it is a
date equal or greater than the Invoice issue date.


## 1.55.1 - Sep 23, 2016

* Tuning thing in the API and the market activation process.


## 1.55.0 - Sep 23, 2016

* Market is coming! Let's sell online :) (alpha)
* Products won't suffer from an identity anymore, the have a face now
(only available for beta testers)

## 1.54.0 - Sep 21, 2016

* Fixes: Locations can not be deleted if receipts are associated to it.
* Improvements: The catalog module is now responsive.


## 1.53.5 - Sep 20, 2016

* Allow invoice to be edited if the same sequence number is used
(common case scenario).
* Consider withholdings value for the payment status calculation.


## 1.53.4 - Sep 20, 2016

* API get Invoice response fixes.


## 1.53.3 - Sep 20, 2016

* API, allow to update invoice number when editing.


## 1.53.2 - Sep 20, 2016

* API fix.


## 1.53.1 - Sep 20, 2016

* Import Invoice from XML improvement.


## 1.53.0 - Sep 20, 2016

* Introducing the Web POS. This option will be available in the
main menu and for super users only. With this new selling experience
you will sell with Dátil like never before.
* Void receipt dialog improvement.


## 1.52.3 - Sep 19, 2016

* API withholdings value bug fix


## 1.52.2 - Sep 15, 2016

* Receipt print button working again :)


## 1.52.1 - Sep 14, 2016

* The search field was beign sent as undefined, and this was causing trouble.


## 1.52.0 - Sep 14, 2016

* Export to Excel & CSV options for purchases are now available.


## 1.51.0 - Sep 13, 2016

* Now we are able to filter Invoices by payment status


## 1.50.6 - Sep 12, 2016

* Fix discount format in invoice and credit note edition


## 1.50.5 - Sep 12, 2016

* Create/edit Invoice fix.


## 1.50.4 - Sep 12, 2016

* Create/edit Invoice fix.

## 1.50.3 - Sep 12, 2016

* Fix in Invoice item discount control.


## 1.50.2 - Sep 12, 2016

* Fixes in Invoice list and the New Sale dashboard button.


## 1.50.1 - Sep 11, 2016

* Show New Sale dashboard button as a dropdown for businesses with more than one
point of sale.


## 1.50.0 - Sep 11, 2016

* See the payment status in the list without having to view the Invoice!
* Sell faster! New Sale shortcut in the dashboard.
* Fixes and improvements in register payment.


## 1.49.0 - Sep 10, 2016

* Now you can specify payment methods when creating or editting an Invoice.


## 1.48.1 - Sep 9, 2016

* Minor style fixes and improvements.


## 1.48.0 - Sep 9, 2016

* Now customers can see how the Pending Payment Reminder email looks like before
sending it.
* Fix in register new Purchase Invoice.


## 1.47.4 - Sep 7, 2016

* Import Invoice from XML feature got a bit smarter.


## 1.47.3 - Sep 6, 2016

* changed button label from 'enviar' to 'activar' in pending payment reminder.
* Option 'Recordatorio de Pago' in 'Pagos' button disapear when receipt due date
has reached.


## 1.47.2 - Sep 6, 2016

* Fixing invalid credentials bug for super users.


## 1.47.1 - Sep 5, 2016

* Bug fix in XML for withheld values in Invoices.


## 1.47.0 - Sep 2, 2016

* Support SRI Invoice payments format in the API.


## 1.46.2 - Aug 29, 2016

* Fix bugs when invoicing plans.


## 1.46.1 - Aug 26, 2016

* Payment terms Invoice info bug fix.


## 1.46.0 - Aug 26, 2016

* Payment methods and received payments is now shown in the Invoice
printable format.
* Fixes, style improvements in printable format and viewer of all receipts.
* Always display two decimal places for product unit price.


## 1.45.3 - Aug 24, 2016

* Fixes, style improvements in printable format of all receipts.


## 1.45.2 - Aug 24, 2016

* Update IRS payments information when creating and updating an Invoice.
* Homogeneization of authorisation information in receipts viewer and printable
formats.


## 1.45.1 - Aug 22, 2016

* Preventing logos and certificates from being overwritten between customers.
* The requirements email after requesting a plan will no longer be sent.


## 1.45.0 - Aug 19, 2016

* API: Additional information in waybills can now be specified as in invoices.


## 1.44.0 - Aug 18, 2016

* Waybill Addressees can now receive the receipt email notification too.
* API bug fix.


## 1.43.1 - Aug 17, 2016

* API, Update Invoice bug fix. Payment terms information was not being updated.


## 1.43.0 - Aug 16, 2016

* API: Ability to specify payment date time.
* IRS payment terms payment code is now configurable. An Account level setting
could be established to override the default value used when reporting an
Invoice with payment terms to the IRS.
* Fixes, register payment and delete payment options.
* Fix, edit Invoice error.
* Excel and CSV exports in the accounts receivable report were not consistent
with the data shown. The max issue date was not being considered.


## 1.42.3 - Aug 13, 2016

* Bug fix in PDF RIDE.


## 1.42.2 - Aug 11, 2016

* Bug fix in waybill edit form.


## 1.42.1 - Aug 10, 2016

* Fix, accept null and blank in new invoice fields


## 1.42.0 - Aug 10, 2016

* New invoice fields: withheld values for IVA and income, and buyer address


## 1.41.0 - Aug 5, 2016

* Internal improvements.


## 1.40.5 - Aug 5, 2016

* Fix, api call to get waybill information with null optional fields


## 1.40.4 - Aug 5, 2016

* Fix, waybill addresee route as optional field


## 1.40.3 - Aug 4, 2016

* API fix, some Waybill fields should be optional.


## 1.40.2 - Aug 4, 2016

* Fixes in the void receipt option. It was not working with all receipt types.


## 1.40.1 - Aug 3, 2016

* API fix, SRI payment terms bug.


## 1.40.0 - Aug 2, 2016

* Display Intercom Acquire instead of Intercom Conversations in demo app.


## 1.39.0 - Aug 2, 2016

* Specify Invoice payment terms amount via the API.


## 1.38.0 - Aug 1, 2016

* New dialog for the "Set as void" option.
* Invoicing of plans, add column total and discount for plan item.


## 1.37.2 - Jul 29, 2016

* REST API, Invoice Update fix.


## 1.37.1 - Jul 27, 2016

* Display product SKU in the Sales by products report.


## 1.37.0 - Jul 27, 2016

* Specifiy Invoice payment information via the API. SRI compliant updated XML.
* Specifiy Invoice payment terms via the API.


## 1.36.3 - Jul 26, 2016

* Fixes a missing import in the accounts setup process.


## 1.36.2 - Jul 23, 2016

* Fixes and improvements when importing Purchase Invoices from XML files.


## 1.36.1 - Jul 22, 2016

* Receipts viewers improvements and homogenisation. Amounts with trailing zeros
in decimals are now removed.


## 1.36.0 - Jul 19, 2016

* Add custom line items (not stored in your catalog) when registering your
Purchase Invoices.
* Fix in Purchase Invoice Supplier autocomplete control.


## 1.35.2 - Jul 15, 2016

* Fixes in import Purchase Invoice from XML option.


## 1.35.1 - Jul 13, 2016

* Fix, Added back 'Marcar como anulada' in actions button on receipts list.


## 1.35.0 - Jul 13, 2016

* It's now possible to configure Pending Payment Reminders for authorized invoices.
* Accounts receivable headers renamed, and tooltips included for the amounts.
* Added two new columns to the Accounts receivable report by customers, overdue date
and overdue days. Also, these report is now responsive.
* Issue date added to the invoice viewer.
* Fixes a bug for the accounts payable report when exporting the content.
Some invoices had no due date specified, so now for this scenario the due date
is the same as the issue date.


## 1.34.0 - Jul 7, 2016

* Accounts receivable report by customer. Select a customer to view the list of
their pending invoices.
* New Invoice preview! This preview pops from the right side of the screen when an
invoice is selected.
* Invoice XML import fixes and improvements. Now the supplier is saved in your
Contacts list.


## 1.33.7 - Jul 6, 2016

* Allow entering a space between the comma and the email address when creating or editting a contact.


## 1.33.6 - Jul 6, 2016

* Fix, exported file (CSV and Excel) of Invoices now includes "Voided" column.


## 1.33.5 - Jul 5, 2016

* Fix in pending Invoices notification service.


## 1.33.4 - Jul 4, 2016

* Fix, creation of token accounts for users with multiple accounts
and token accont id assigned to the current account.


## 1.33.3 - Jul 4, 2016

* Fix, Import Purchase Invoice XML.
* Invalid credentials message bug fixed in login


## 1.33.2 - Jul 1, 2016

* Fix, export CSV and Excel download.


## 1.33.1 - Jun 30, 2016

* Removing flash messages in the invoices viewer.


## 1.33.0 - Jun 30, 2016

* Including Withholdings items as part of the export Excel and CSV to display
withheld values and types of retained taxes.


## 1.32.3 - Jun 27, 2016

* Waybill issue fix.


## 1.32.2 - Jun 25, 2016

* Now we can add items on a debit note. (issue 613).
* Corrected message that appear when we save a debit note (issue 539).
* Credit and Debit Note viewer improvements.


## 1.32.1 - Jun 25, 2016

* Added discount to Credit Note RIDE and viewer.
* Super users are now able to generate a Customer's API key.
* A label is now displayed in receipt viewer for receipts issued in test environment,
this will help identify test receipts during account setup.
* Fuel subsidy price is now sent with complete number of decimal places to SRI.
* Fix, showing again VAT subtotals and VAT values to Credit Note print view.
* Fix, displaying default value for Sales Representative when creating an Invoice.
* Fix, discount control in Invoices and Credit Notes now looks OK in smaller screens.
* Fix, a new Carrier could not be added when the list of Carriers was empty.
* Fix, business info is now displayed updated after its saved.
* API security fix.
* Fix, increased number of displayed taxes list in Withheld receipt. This in
hopes to make easier to look for taxes when using keywords that return many taxes.
* Fix, Contact tax ID will not be deleted when changing tax ID type.
* Fix, Withholdings sequence is taken from config when creating a new one.
Previously this overwrite only worked when no Withholdings where issued yet.


## 1.32.0 - Jun 23, 2016

* Send event to dispatcher when payment is registered or deleted.
* Extract buyer email from additional information when creating receipts from an XML file.
* Dashboard security fix, tweet profile pics are now loaded using HTTPS.


## 1.31.0 - Jun 20, 2016

* New API endpoint to create retentions from an XML.
* Changed appearance of Debit notes.


## 1.30.1 - Jun 20, 2016

* Updating contract as active or inactive when a user uploads or deletes a certificate.


## 1.30.0 - Jun 19, 2016

* Ability to specify sales representative when issuing an invoice.
* Fix, localized month in Purchases list was not correct. Purchases were grouped
by date instead of month.
* Fix, Withholdings (Retentions) and Credit Notes links in Purchases are now working.


## 1.29.0 - Jun 17, 2016

* Setup process improved with user feedback.
* Personal plan removal.
* Dialog improvements, all OK buttons are now placed on the right side for improved
interaction.
* Fix, sign receipt dialog now displays correctly in iOS devices.

## 1.28.0 - Jun 17, 2016

* Added filter by point of sale in sales report.


## 1.27.0 - Jun 15, 2016

* Improved error messages and more complete invoice information returned from
the new /api/invoices/xml endpoint.

## 1.26.0 - Jun 15, 2016

* Added filter by point of sale in Dashboard.


## 1.25.0 - Jun 14, 2016

* HubSpot integration for the SignUp process.


## 1.24.2 - Jun 14, 2016

* Bug fixes.


## 1.24.1 - Jun 13, 2016

* API fix, a global discount could be specified for any type of VAT, not just 12% VAT.


## 1.24.0 - Jun 13, 2016

* New API endpoint to create invoices from an XML.


## 1.23.7 - Jun 11, 2016

* Accounts receivable report fix.
* Fix, added missing field 'Payed' to invoices list export.


## 1.23.6 - Jun 10, 2016

* Receipt Viewer permissions fix.
* Contifico Integration bug fix.
* Signup process improvement.
* Basic plan changes.
* Facebook Pixel in the signup process.


## 1.23.5 - Jun 10, 2016

* Only display inventory related controls and information when track inventory
setting is enabled.
* Issued receipts filters layout improvements for smaller screens.
* Some bug fixes.
* Admin site improvements.


## 1.23.4 - Jun 9, 2016

* Bug fix for withholdings.


## 1.23.3 - Jun 9, 2016

* Fixes bug that prevented from authorizing receipts through the web app.


## 1.23.2 - Jun 9, 2016

* Fixes bug that prevent deleting item when issuing Invoice


## 1.23.1 - Jun 9, 2016

* Fixed bug that prevented from looking for products in the catalog.
* Fix, API race condition when getting authorized receipts information.


## 1.23.0 - Jun 7, 2016

* Register Purchase Invoice.
* Import Purchase Invoice from authorized XML Invoice files.
* Enable Inventory tracking for Products in Catalog.
* Increase Inventory when a Purchase Invoice is registered.
* Inventory is reduced when an invoice is issued.
* Decrease Inventory when issuing an Invoice.
* Accounts Receivables by Customers report.
* Accounts Payable by Invoices report.
* Send reminders to your customers outstanding invoices, enable this option
when issuing the invoice.
* Fix, unitary discount added to edit Credit Note form.
* Overall improved support for mobile devices.
* Ability to add multiple times the same Product as different line item.


## 1.22.0 - Jun 7, 2016

* Automatically add 'Compensación solidaria 2%' additional info to Invoices issued
by customers from Manabi and Esmeraldas.
* Fix, display waybills in received receipts.


## 1.21.0 - Jun 2, 2016

* Discount per unit in now available in Credit Notes too.

## 1.20.3 - Jun 2, 2016

* Fix bug caused when invoice or credit note subtotal was higher than 1,000.00
* Fix, removed 12% label to Invoice email template.


## 1.20.2 - Jun 2, 2016

* Fix, Products with VAT exempt tax (code 7) were not being added to the sale total


## 1.20.1 - Jun 1, 2016

* Fixes Token accounts password reset
* Fixes new product modal in Invoice issue.


## 1.20.0 - May 31, 2016

* Fix, use VAT percentage stored in the product configuration.
* Reset password for accounts using the new Dátil authentication service.


## 1.19.4 - May 31, 2016

* Import contacts dialog fixes


## 1.19.3 - May 26, 2016

* Fix, solved bug with the json showed in the browser when I was trying to
recover my password


## 1.19.2 - May 24, 2016

* Fix, use commercial name in email subject when available.
* Fix, show 404 page when receipt is not found.


## 1.19.1 - May 23, 2016

* Some API XML fixes.


## 1.19.0 - May 20, 2016

* Mark receipts as void


## 1.18.1 - May 18, 2016

* Fix, send to dispatcher the invoice and credit note additional information.
* Fix, add credit note modified document info in event sent to the dispatcher.


## 1.18.0 - May 18, 2016

* Dispatch event when a credit note is authorized
* Fix vat in product created via api


## 1.17.0 - May 12, 2016

* Dispatch event when invoice is authorized
* Create and get Products using the API (beta)
* Get VAT and SCT(ICE) taxes via the API


## 1.16.4 - May 10, 2016

* Mandrill Api Key bug fixed for plan requests with registered users.


## 1.16.3 - May 7, 2016

* Calculating VAT at the end, after adding all items subtotals.
* Creating a token account if the user does not have it on login.


## 1.16.2 - May 4, 2016

* Intercom business bug fixes when registering from beta.datil.co


## 1.16.1 - May 3, 2016

* Replacing Mandrill by Sendgrid when a user requests the service via datil.co


## 1.16.0 - May 2, 2016

* Adds intercom.io as customer service channel. This replaces the "Ayuda" button.
* Fixed: Includes missing build dependencies for react.


## 1.15.1 - April 26, 2016

* Fixes issue when editing invoice. Price with subsidy was displayed on Invoice
edit screen when it was not supposed to be displayed.
* Include discount per unit when editing invoice.


## 1.15.0 - April 22, 2016

* Mask for numero sustento field get back.
* Create and edit Retenciones with variable percentage.
* Same table columns for edition and creation.
* Removing leadalead integration.


## 1.14.2 - April 19, 2016

* Random message in the invoice visualizer page.


## 1.14.1 - April 15, 2016

* Related documents when issuing a retention was incomplete.
* Comprobante de pago de aportes added to the list.
* Dashboard reports ignoring canceled Invoices.
* Rounding totals in the end of invoice calculation.
* Invocing plans add salesman when is not empty.
* Fix loggin when contract must not issue invoice.


## 1.14.0 - April 14, 2016

* First card of the setup process removed.
* Setup process css and bug fixes.
* Notification styles improvements.
* Change password page with new style and working for all account types.


## 1.13.1 - April 13, 2016

* SMTP Email default backend fixes


## 1.13.0 - April 10, 2016
* News section available in Panel. Every card displays a tweet and entities
are actionable.


## 1.12.0 - April 10, 2016

* New Endpoints to get active businesses, and their stats in a period of time.
* New receivables by customer report.
* New endpoint to get receivables customer by expirition date of invoice.


## 1.11.1 - April 8, 2016

* Fix: Setting default value of zero for price with subsidy.
* Fix: Visual invoice viewer fix when business has the same commercial and legal names.
* Fix: When creating or editting contacts, blank spaces from the beginning or the end
of the email field are removed to prevent user accidentally saving emails addresses
with spaces.
* Fix: Ignoring cancelled invoices and credit notes when querying the db for sales
and returns totals.
* Fix: Added error message to the sales report should something unexpected happens
when generating the report.
* Fix: Add missing sample contacts file for the new import feature.

## 1.11.0 - April 8, 2016

* Ability to specify product price with subsidy for Fuel related businesses.
* Print receipt now shows a PDF instead of an HTML.
* RIDE and viewer style improvements.
* Using store address instead of business main address in RIDE and receipt viewer.


## 1.10.1 - April 6, 2016

* Fixed: Error when editing an invoice.
* Fixed: Retention totals shown in invoice viewer were incorrect
* Fixed: Export contacts in the format required by import contact. This will
enable customers to import contacts using the exported CSV.


## 1.10.0 - April 5, 2016

* Use the correct field for the product SKU when issuing recurring invoices from the admin.
* Import contacts option.


## 1.9.0 - April 1, 2016

* Adds fuel subsidy fields in invoice for API.


## 1.8.2 - March 31, 2016

* Delete mask on identification customer form.


## 1.8.1 - March 28, 2016

* Show correct customer phone in Nota de Crédito RIDE.
* Empty search messages improvement.


## 1.8.0 - March 24, 2016
* Settings access for accounts without entitiy bug fixed
* Help Scout ticket for potential customers without entity requesting a plan
* Help Scout ticket fields for business verification fixes
* Sending a email to a user once the owner of a business give access to them.


## 1.7.2 - March 24, 2016
* Current date for fecha_emision on invoicing plans
* Fix period translation on invoicing plans


## 1.7.1 - March 23, 2016

* Removing unused endpoints.
* Referral email url as a parameter.
* Add field billable on contract.
* Rename field periodicity on contract.
* Set first_name of user for salesman on contract.


## 1.7.0 - March 22, 2016

* Business address and mandatory accounting fields saved from the SRI request
in the setup process.
* Setup navigation improvement.
* Adds content improvement.
* Sender name and email support for SMTP email configurations.


## 1.6.6 - March 21, 2016

* Responsive pricing dialog.
* Adds bug fixed.


## 1.6.5 - March 20, 2016

* API fix: fixed look up of addressee ID type in create waybill endpoint.


## 1.6.4 - March 18, 2016

* Add validation when discount is greater than product price.


## 1.6.3 - March 18, 2016

* Referrals dialog UI improvements, including responsive behavior.
* Empty or not valid emails validation for referrals.


## 1.6.2 - March 17, 2016

* Fix rounding error when issuing invoices.


## 1.6.1 - March 16, 2016

* Contacts and products search bug fixes.
* Html email error bug fixed.
* Replacing the help options text. Options are more explicit and comprehensible.


## 1.6.0 - March 16, 2016

* Tributary Help request modal.
* Request sent via Tributary help request will add a tag in Help Scout.
* Flash message for Dátil super users bug fixed.


## 1.5.0 - March 16, 2016

* Help options available as a persisten option in the bottom of the page.
* Bug fix in public receipt viewer that prevented from scrolling content.
* Support dialog is now responsive.


## 1.4.0 - March 15, 2016

* New referrals flash message. Once closed, it will not appear again.


## 1.3.4 - March 14, 2016

* Optimised for small screens, e.g. mobile devices: Multi account select login,
Referrals dialog.
* Login and account setup (new register) menu bar only show logo and no menu
icon on small screens.


## 1.3.3 - March 14, 2016

* Bug fix in export to excel that prevented exporting when having an receipt with no XML
* Referral flash message visible and clickable.
* If the user closes the flash message, a flag is stored in the db with a key related to that message.


## 1.3.2 - March 14, 2016

* Moving referrals as a main option in the menu
* Text improvements in the modal
* Continue referring button
* Close option


## 1.3.1 - March 13, 2016

* Style fixes to remove excessive scroll bars.
* Updated referrals form text and menu link.


## 1.3.0 - March 12, 2016

* Better interaction with floating modals.
* Once the user request a plan, they can use the App if an Entity is associated. (For full use of it, documents must be submitted)
* Navigation bar selected item bug fixed.
* Error logging improvements in the signup process.
* Redeem referral from datil.co (static page with no automatic signup).
* Update in signup steps' titles and instructions.

## 1.2.1 - March 10, 2016

* Improvements on payments table for invoices.
* Register of payments for invoices available for all business.


## 1.2.0 - March 8, 2016

* Creating a referral.
* Sending an email to the referred person.
* Updating the referral once the referred user creates their account.

## 1.1.0 - March 8, 2016

* Inactive contracts for new customers requesting a Plan.
* Selected Plan Card in the account setup process.
* Requirements displayed at the end of the account setup process and in the panel page.
* New welcome email.
* Automatic invoicing of plans in customer contracts.


## 1.0.2 - March 3, 2016

* Add validations for "Guia de Remisión" creation and edition.


## 1.0.1 - March 2, 2016

* Fix bug in edit invoice when the additional data saved has a linefeed in the end of the text.


## 1.0.0 - March 1, 2016

* Add validation for "Numero documento sustento" field on retention creation.


[1.136.2]: https://github.com/datil/datil-py/compare/1.136.1...1.136.2
[1.136.1]: https://github.com/datil/datil-py/compare/1.136.0...1.136.1
[1.136.0]: https://github.com/datil/datil-py/compare/1.135.0...1.136.0
[1.127.3]: https://github.com/datil/datil-py/compare/1.127.2...1.127.3
[1.127.2]: https://github.com/datil/datil-py/compare/1.127.1...1.127.2
[1.127.1]: https://github.com/datil/datil-py/compare/1.127.0...1.127.1
[1.127.0]: https://github.com/datil/datil-py/compare/1.126.3...1.127.0
  