# Meta Information
Meta information, in the context of HTML, refers to additional information about a web page that is not directly visible to users but provides essential details for browsers, search engines, and other applications. It helps these systems understand and process the webpage effectively.
Some common types of meta information include:

- 1. Character Encoding: The meta information specifies the character encoding used in the HTML document. It ensures that the browser interprets the text correctly and displays special characters, symbols, and non-English characters accurately.

- 2. Viewport Settings: The viewport meta tag defines how the webpage should be displayed on different devices and screen sizes. It helps make the webpage responsive and mobile-friendly by adjusting the layout and scaling according to the device's screen dimensions.

- 3. Page Description: The meta description provides a concise summary or brief description of the webpage's content. It often appears in search engine results below the page title and can influence users' decision to click on the link. A well-crafted meta description can attract more visitors to the webpage.

- 4. Keywords: Keywords meta tags used to be more relevant in the past for search engine optimization (SEO). However, their impact has diminished over time. They were intended to include relevant keywords that reflect the content of the webpage. Nowadays, search engines rely more on the actual page content and context rather than the keywords meta tag.

- 5. Robots Directives: The meta robots tag instructs search engine crawlers on how to interact with the webpage. It can specify whether to index the page, follow links on the page, or prevent search engines from accessing the page altogether.

- 6. Author Information: The meta information can include details about the author or creator of the webpage. It can provide information such as the author's name, email address, or other relevant contact details.

These are just a few examples of meta information commonly used in HTML. The purpose of meta information is to provide additional context, instructions, and data about the webpage, helping browsers, search engines, and other systems understand and handle the page appropriately.


# Encoding
Encoding refers to the process of representing characters and symbols in a digital format that can be understood by computers. Since computers work with binary data (0s and 1s), character encoding allows the conversion of human-readable characters into a corresponding binary representation.

In the context of HTML files, encoding determines how the characters within the file are encoded and interpreted by web browsers and other software. HTML files can contain text content in different languages, symbols, special characters, and various scripts. Therefore, it's important to specify the correct encoding to ensure that the characters are accurately displayed and interpreted by the browser.

UTF-8 (Unicode Transformation Format 8-bit) is one of the widely used character encodings. It is a variable-length encoding scheme that can represent almost all characters and symbols in the Unicode standard. UTF-8 provides backward compatibility with ASCII (American Standard Code for Information Interchange) and supports characters from various scripts, including Latin, Cyrillic, Greek, Chinese, Japanese, and many others.

Setting the encoding to UTF-8 in HTML files is considered the preferred approach because:

- 1. Versatility: UTF-8 can represent a vast range of characters and symbols from different languages and scripts, making it suitable for internationalization and multilingual web content.

- 2. Compatibility: UTF-8 is widely supported by modern web browsers, operating systems, and software applications. By using UTF-8 encoding, you ensure that your HTML files can be correctly interpreted and displayed across different platforms and devices.

- 3. Future-proofing: UTF-8 is the recommended encoding for HTML5, the latest version of the HTML standard. By using UTF-8, you ensure compatibility with the latest web standards and future-proof your HTML files.

To set the encoding to UTF-8 in HTML files, you include a <meta> tag within the <head> section of the HTML document. The <meta> tag with the charset attribute specifies the character encoding. The value "UTF-8" is assigned to the charset attribute to indicate that the HTML file is encoded using UTF-8. This allows the browser to correctly interpret and render the characters within the HTML file.

By setting the encoding to UTF-8, you ensure that your HTML files can handle a wide range of characters and symbols, promoting compatibility, interoperability, and proper rendering across different systems and languages.


# document type declaration: <!DOCTYPE html>
The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.
It must only appear once, at the top of the page (before any HTML tags).
The <!DOCTYPE> declaration is not case sensitive.
The <!DOCTYPE> declaration for HTML5 is:
<!DOCTYPE html>


# TIPs: 
# HTML tags are not case sensitive: <P> means the same as <p>. lowercase is needed only for XHTML so itsa a good practice.
# There are two ways to specify the URL in the src attribute:
- Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".
Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.
- Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".
# Here,the first two characters define the language of the HTML page, and the last two characters define the country. <html lang="en-US">
# In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes, <p title='John "ShotGun" Nelson'>
# pre tag is used when we want 

