# HTML-CSS
# INTRODUCTION TO HTML
HTML stands for Hyper Text Markup Language
HTML is the standard markup language for creating Web pages
HTML describes the structure of a Web page
It serves as a channel for different types of content like words, images, videos, audio, forms, and interactive experiences.
It allows us to structure our content and bridge the gap between human and computer languages.
# HTML FUNCTIONS
HTML has a straightforward structure without any programming logic, loops, or functions. It is known as a declarative language. 
The code simply declares instructions like "This is a paragraph!" or "Make this a link!" or "Put a form field here!". 
It is all about using the right vocabulary and making declarations.
# HTML BASICS
All HTML documents must start with a document type declaration. For example: Doctype html.
# HTML ELEMENTS
It is everything from the start tag to the end tag.
Elements can be nested, meaning that elements can contain other elements.
# HTML HEADINGS
Are titles or subtitles that you want to display on a webpages.
There are elements that are used for marking up headlines that come in a six different types that is head 1 to 6.
When viewed in a browser, each headlines has a distinct visual effect.
# HTML FORMATTING
HTML contains several elements for defining text with a special meaning.
There are several formatting elements, which are (bold,italic,subscript,superscript,important,emphazised,smallest, marked)texts.
# HTML WORKING WITH GRAPHICS AND IMAGES
When we want to add an image to a webpage, we use the image element, which is simply written as IMG. 
First, we have the source attribute (SRC), which tells the browser which image file to load. 
We also have the alt attribute (ALT), which provides a text description of the image. 
Lastly, we have the width and height attributes, which determine the size of the image. So, every image should have all four of these attributes.
The image's URL is pasted into the source, as can be seen in the example, and then the image starts loading.
There are four main file formats commonly used on the web these days, each with its own strengths and weaknesses when it comes to compressing images.And those four main file formats are: GIF, SVG, JPG, PNG.
CSS offers a solution for displaying images in different sizes to accommodate both large screens and small screens.
HTML allows us to deliver different image files to screens of different sizes.
# HTML WORKING WITH MEDIA
#WORKING WITH AUDIO- The audio element is different from the image element because it has both an opening and a closing tag. This makes it more modern and gives it more power and flexibility. Just like the image element, we use a source attribute to provide the URL of the audio file. 
here are different audio file formats to choose from. For example MP3.
MP3s are widely supported in modern browsers, while OGG had some advantages but did not gain much popularity. 
There may be a new format on the horizon, similar to the AV1 video file format, but not widely available yet. For this reason, there is no second audio format recommended at the moment. Nevertheless, it is important to understand the syntax for supporting multiple formats, as it was crucial in the past and will likely be useful again in the near future. 
Furthermore, it is possible to provide fallback text within the audio element, which will only be displayed if the browser does not understand the audio element at all. This demonstrates the resilience of HTML, where a single set of code can cater to a wide variety of browsers and provide a suitable user experience. The audio element is an excellent tool for embedding audio files and a player on a webpage.
#WORKING WITH VIDEO-The web has completely changed how we connect and share things, including movies, TV shows, and even teaching. Thanks to the power of the web, we can now easily put videos on web pages using the HTML video element. 
Just like the audio element, the video element has an opening and closing tag. To display a video, use the source attribute to specify the video file. And if the controls attribute is added, the browser will automatically create a video player. Sounds simple right? But there are a couple of issues that need to be addressed.
Just like with image formats like PNG, JPEG, GIF, or SVG, there are different codecs that can be used to encode video files. Video files contain a lot of data, and if not compressed, they become too large to be efficiently transmitted over the internet. Internet videos, therefore, use a mechanism to compress all the data into a smaller package. 
# HTML CONTENT IDENTIFICATION
The internet is worldwide, and people speak various languages. In HTML, there are tools to indicate the language of your content. By setting things up correctly, search engines will understand which language websites are in. Spell checkers will provide the appropriate dictionaries, and when a browser reads the content aloud,it will prounance the word correctly. It is important for computers to know the language of the content it is processing.
The lang attribute is used to specify the language of a webpage. If the whole page is in one language, it is quite simple. Set the language on the main element that wraps everything else, which is usually the HTML element. It may only be required to set it once, like in a template file that applies to the entire site but do not forget to do it.
# HTML INTEGRATION
HTML and all the elements, attributes, roles, and tools used to mark up content on websites or web apps have been covered. HTML plays a major role in explaining what these things are, but it is not just limited to that. HTML files are a vital part of the web. 
In the early days of the web, everything needed to display a webpage was contained in a single HTML file, along with images, but things have gotten more complex now. Text is often stored in databases, and multiple static files are combined in real-time, customized for each user. Visual styling is in CSS files, JavaScript is in separate JavaScript files, and there are additional files for images, video, audio, and ads.
Once the browser gets the file, it starts reading it immediately and follows the instructions one by one. The file has a bunch of other files listed in it, so the browser promptly requests those as well. Once it has all the required files, it begins executing the instructions inside them. And before you realize it, a web page is magically generated in a blink of an eye.
nce the HTML file is built, there are a few crucial parts that every web page needs(Firstly, the file should begin with a doctype statement, which indicates the era of this HTML file. In the past, there were different doctype declarations for older HTML versions. By including this one, we are saying, "Hey, this is a modern web page, so follow modern best practices and treat it accordingly"). (Next, we enclose everything else on the page within an HTML element, which means an element named HTML. It tells us that all the content within it is HTML. Place the opening HTML tag at the top and the closing HTML tag at the bottom).
