Sencha-Touch-2-Signature-Pad-Field
==================================

The signature pad field is a formpanel element for drawing signatures. It is an extension of Ext.field.Text with a custom canvas component. The outputted value is a base64 encoded image (string). The extension also includes an Android work around for devices < 2.3. Specifically, the Android developers decided not to build the toDataURL function into android until version 2.3.

Utilizing the component is quite easy, it follows standard ST2 form field config options / parameters. sigWidth and sigHeight will set the dimensions of the overlay canvas object and are the only additional config items in this extension.

Learn more by reading my original blog post: http://morointeractive.com/sencha-touch-2-signature-field-with-android-todataurl-work-around/