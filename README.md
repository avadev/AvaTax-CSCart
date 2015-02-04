# AvaTax-CSCart
AvaTax for CS Cart integration source code and release notes.

This integration is compatible with CS Cart versions:
CS Cart 4.2.3, CS Cart 4.2.2, CS Cart 4.2.1, CS Cart 4.1.3, CS Cart 4.1.4, CS Cart 4.1.5, CS Cart 4.0.2

Release notes can be accessed from :
https://help.avalara.com/004_AvaTax_Integrations/CS-Cart/Avalara_AvaTax_for_CS-Cart_Release_Guides/Avalara_AvaTax_for_CS-Cart_Release_Guide

For user guide and exploring how this integration works, please visit Avalara Help Center at
https://help.avalara.com/004_AvaTax_Integrations/CS-Cart

Contents:
----------
 
<table>
<th colspan="2" align=left>Folders</th>
<tr><td>CancelTaxTest.php</td><td>Demonstrates the <a href="http://developer.avalara.com/api-docs/rest/tax/cancel">CancelTax</a> method used to <a href="http://developer.avalara.com/api-docs/api-reference/canceltax">void a document</a>.</td></tr>
<tr><td>EstimateTaxTest.php</td><td>Demonstrates the <a href="http://developer.avalara.com/api-docs/rest/tax/get">EstimateTax</a> method used for product- and line- indifferent tax estimates.</td></tr>
<tr><td>GetTaxTest.php</td><td>Demonstrates the <a href="http://developer.avalara.com/api-docs/rest/tax/post">GetTax</a> method used for product- and line- specific <a href="http://developer.avalara.com/api-docs/api-reference/gettax">calculation</a>.</td></tr>
<tr><td>PingTest.php</td><td>Uses a hardcoded EstimateTax call to test connectivity and credential information.</td></tr>
<tr><td>ValidateAddressTest.php</td><td>Demonstrates the <a href="http://developer.avalara.com/api-docs/rest/address-validation">ValidateAddress</a> method to <a href="http://developer.avalara.com/api-docs/api-reference/address-validation">normalize an address</a>.</td></tr>
<th colspan="2" align=left>Other Files</th>
<tr><td>AvaTaxClasses/</td><td>Contains the core classes that make the service calls.</td></tr>
<tr><td>.gitattributes</td><td>-</td></tr>
<tr><td>.gitignore</td><td>-</td></tr>
<tr><td>LICENSE.md</td><td>-</td></tr>
<tr><td>README.md</td><td>-</td></tr>
