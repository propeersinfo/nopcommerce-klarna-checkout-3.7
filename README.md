<h2>Klanra Checkout plugin(developed by Motillo) upgraded to nop commerce 3.70 by Professionals Peers Info Services Pvt. Ltd.</h2>

Original Code of https://github.com/Motillo/klarna-checkout-nopcommerce was developed by Motillo.

After installation, make sure to edit the Checkout/Completed.cshtml view so that the Klarna confirmation snippet is shown.
@Html.Action("ConfirmationSnippet", "KlarnaCheckout", new { orderId = Model.OrderId })

<h3>Support:</h3>
Our Support team can help you at any time. You can contact us for more information by dropping an email to sales@propeersinfo.com.

To Support Nop Commerce 3.7 version following changes are done:

1) References are updated to latest version. 2) Changes are done in KlarnaCheckoutContext.cs

This plugin is inspired by Klarna Checkout by Motillo. The Upgradation features are implemented by Professionals Peers Info Services Pvt. Ltd. http://www.propeersinfo.com
