# concierge-marketing
Custom HTML for Concierge Marketing

Basic Guide For Custom HTML Marketo Landing Pages

Custom HTML template - All Marketo landing pages are based on existing templates. These templates have unique characteristics. In this short document we review the basic details of a “custom HTML” template called the “Clean Template”. This custom HTML template is a template that allows us to use a custom look-and-feel HTML file to provide a unique or custom look to a Marketo landing page.

Template structure – The basic structure of the custom HTML template includes everything that is required for the functionality of the Marketo landing pages. This include any and all basic HTML, default CSS styles, and functionality Javascript.

Providing custom HTML – In order to implement custom HTML code for a unique look on a Marketo landing page, several things/limitations need to be considered. Custom HTML elements (blocks of code) are “absolute positioned” within the HTML. This means that the code is not actually inserting in its logical place for display, but rather “floated” in place. Keeping that in mind, we must avoid using formats that would “push” content as more room is needed within a page. The code will be positioned using Marketo’s interface to designate its x/y coordinates.

Things to avoid in custom HTML designs – Here are the most critical items that need to be considered and/or avoided when working with custom designs.

CSS styles – The existing template uses CSS styles that already define the characteristics of the BODY element as well as default content and form styles. 
Page and content alignment – Based on the Citrix standard landing page format, all our templates will display the content centered within the page and have a maximum fixed width of 950px. This means that we must avoid making use of designs that would require the availability of any available width from the browser window. In other words, 100% width is NOT available. 
Form customization – The form element that will be displayed on the page cannot be modified with custom HTML. Any custom HTML designs should only have placeholder text for the placement of the form and have at least 800px height available for the form to be displayed. Something like “INSERT FORM HERE” is a good indicator of where the form should be inserted within the design. The fields that are displayed on the forms are only customizable by the Citrix internal teams and follow strict requirements and cannot be modified by one-off requests. These are critical for collecting and routing leads correctly.  
General HTML guidelines – The custom code provided by any team or agency must work within an existing BODY tag. Do not include all the HTML structure of a page. Only include the content piece. 
Sample code structure and placement: 

```<html>   
    <head>. . .</head> 
    <body> . . . <div id=”mktContent”>  
      CUSTOM CODE WILL BE INSERTED HERE AND GIVEN AN ABSOLUTE POSITION WITHIN THE PAGE DOCUMENT.   
    </div> . . . </body> 
    </html> 
```




If you have any questions please contact Rafael Santoni (rafael.santoni@citrix.com).
