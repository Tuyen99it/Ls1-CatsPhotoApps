1. HTML elements have an opening and closing tag with content in between.<openingTag>content</closingTag>
2. The h1 through h6 heading elements are used to signify the importance of content below them. The lower the number, the higher the importance, so h2 elements have less importance than h1 elements.
Example Code
<h1>most important heading element</h1>
<h2>second most important heading element</h2>
<h3>third most important heading element</h3>
<h4>fourth most important heading element</h4>
<h5>fifth most important heading element</h5>
<h6>least important heading element</h6>
Only use one h1 element per page and place lower importance headings below higher importance headings.
3. he p element is used to create a paragraph of text on websites.
4. Commenting allows you to leave messages without affecting the browser display. It also allows you to make code inactive. A comment in HTML starts with <!--, contains any number of lines of text, and ends with -->.
5. The main element is used to represent the main content of the body of an HTML document. Content inside the main element should be unique to the document and should not be repeated in other parts of the document.
Example Code
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
6. Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation and it is used to make HTML easier to read.
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
7. You can add images to your website by using the img element. img elements have an opening tag without a closing tag. An element without a closing tag is known as a void element.
8. HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).
Example Code
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
9. All img elements should have an alt attribute. The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.
Example Code
<img src="cat.jpg" alt="A cat">
11. A link's text must be placed between the opening and closing tags of an anchor (a) element.
12. You can turn any text into a link, such as the text inside of a p element.
13. To open links in a new tab, you can use the target attribute on the anchor (a) element.The target attribute specifies where to open the linked document. target="_blank" opens the linked document in a new tab or window.
14. The section element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.
15. To create an unordered list of items, you can use the ul element.
16. he li element is used to create a list item in an ordered or unordered list.
Example Code
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
17. The figure element represents self-contained content and will allow you to associate an image with a caption.
18. A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element.
Example Code
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
19. em element use to emphasize content
20. The code for an ordered list (ol) is similar to an unordered list, but list items in an ordered list are numbered when displayed.
21. The strong element is used to indicate that some text is of strong importance or urgent.
22. The form element is used to get information from a user like their name, email, and other details.
23. The action attribute indicates where form data should be sent.
Example Code
<form action="/submit-url"></form>
24.  There are many kinds of inputs you can create using the type attribute. You can easily create a password field, reset button, or a control to let users select a file from their computer.
25. Create a text field to get text input from a user by adding the type attribute with the value text to the input element. In order for a form's data to be accessed by the location specified in the action attribute, you must give the text field a name attribute and assign it a value to represent the data being submitted.
Example Code
<input type="text" name="name">
26. Placeholder text is used to give people a hint about what kind of information to enter into an input.
27. To prevent a user from submitting your form when required information is missing, you need to add the required attribute to an input element. There's no need to set a value to the required attribute. Instead, just add the word required to the input element, making sure there is space between it and other attributes.
28. The button element is used to create a clickable button.
29. both input and button elements are inline elements, which don't appear on new lines.
30. You can use radio buttons for questions where you want only one answer out of multiple options.
31. label elements are used to help associate the text for an input element with the input element itself (especially for assistive technologies like screen readers).
32. The id attribute is used to identify specific HTML elements. Each id attribute's value must be unique from all other id values for the entire page.
33. Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value.
Example Code
<input type="radio" name="meal"> Breakfast
<input type="radio" name="meal"> Lunch
34. The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line.
35. The legend element acts as a caption for the content in the fieldset element. It gives users context about what they should enter into that part of the form.
36. Forms commonly use checkboxes for questions that may have more than one answer. The input element with a type attribute set to checkbox creates a checkbox.
37. There's another way to associate an input element's text with the element itself. You can nest the text within a label element and add a for attribute with the same value as the input element's id attribute.

Here is an example of using the for attribute to associate a label with an input element:

Example Code
<label for="breakfast"> Breakfast </label>
<input id="breakfast" type="radio" name="meal" value="breakfast">
38. Like radio buttons, form data for selected checkboxes are name / value attribute pairs. While the value attribute is optional, it's best practice to include it with any checkboxes or radio buttons on the page.
39. In order to make a checkbox checked or radio button selected by default, you need to add the checked attribute to it.
40. The footer element is used to define a footer for a document or section. A footer typically contains information about the author of the document, copyright data, links to terms of use, contact information, and more.
41. Notice that everything you've added to the page so far is inside the body element. All page content elements that should be rendered to the page go inside the body element. However, other important information goes inside the head element.
42. The head element is used to contain metadata about the document, such as its title, links to stylesheets, and scripts. Metadata is information about the page that isn't displayed directly on the page.
43. The title element determines what browsers show in the title bar or tab for the page.
44. The html element is the root element of an HTML page and wraps all content on the page.
45. All pages should begin with <!DOCTYPE html>. This special string is known as a declaration and ensures the browser tries to meet industry-wide specifications.
46. a meta element with an attribute named charset. Set to the value to utf-8 which tells the browser how to encode characters for the page. Note that the meta element is a void element.