# LinkInNSTextField
Example of how to create a clickable link in a NSTextField

When you want to create a clickable Hyperlink inside an NSTextField all you need to do is the following. Turn your String to an NSAttributedString and add a [NSLinkAttributeName: "http://yoururl.example/"] over the range you want to have clickable. As soon as you add the attributedString to the attributedStringValue of the NSTextField, the text field will display the range as a clickable thing.

The only draw back in this. For the NSTextField it is impossible to change it's color. As far as I can tell.

