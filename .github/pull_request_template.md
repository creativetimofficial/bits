# Description

To submit a new snippet you have to complete a JSON file. The snippet needs to be created using the [JSFiddle](https://jsfiddle.net/) platform.

The JSON file contains the following keys:

- h1
  - The title of your snippet that describes the main content
  - We recommend a maximum length of 60 characters
- h2
  - The subtitle of your snippet where you can give more details
- p
  - Full description of your snippet. Include as many details as you wish so people will clearly understand all the elements that your snippet contains
- meta_description:
  - SEO Description of your snippet
  - Include relevant keywords like the framework used and the component/page name
- meta_title
  - SEO Title of your snippet
- tags
  - Main tags of your snippet
- parent_url:
  - Link to the product that you used to make the snippet
- parent_name:
  - Product name that you used to make the snippet
- jsfiddle:
  - JSFiddle id of your component
  - The id can be found at the end of your snippet link
  - e.g.: https://jsfiddle.net/CreativeTim/**h6g0zx3c**/
- framework:
  - Framework used to create your snippet
  - e.g.: Bootstrap, TailwindCSS
- user_name:
  - Your name
- user_photo:
  - A photo with you
  - Recommended to have a size of 60 X 60 px
  - The default image is the Anonymus Creative Tim logo: https://s3.amazonaws.com/creativetim_bucket/anonymous_thumb.png


#JSON Structure

```json
[{
  "h1": "",
  "h2": "",
  "p" : "",
  "meta_description": "",
  "meta_title": "",
  "tags": "",
  "parent_url": "",
  "parent_name": "",
  "jsfiddle": "",
  "framework": "",
  "user_name": "",
  "user_photo": "",
}]
```

#JSON Example
```json
[{
  "h1": "Bootstrap Stats Card",
  "h2": "An useful code snippet that provides a ready to use Bootstrap Stats Card Template, no need to download an entire theme.",
  "p" : "This Bootstrap Stats Card snippet is a piece of reusable code that will help you avoid repetitive code typing. The code snippet is also shareable so that if you are working on a team project, your code will be more consistent and readable. Test here your HTML/CSS/Javascript code.",
  "meta_description": "Check out this free code snippet that provides ready to use Bootstrap Stats Cards, no need to download an entire theme!",
  "meta_title": "Bootstrap Stats Card Snippet for Easier Coding",
  "tags": "html, css, bootstrap, argon",
  "parent_url": "https://www.creative-tim.com/product/argon-dashboard",
  "parent_name": "Argon Dashboard",
  "jsfiddle": "m47bhref",
  "framework": "bootstrap",
  "user_name": "Creative Tim",
  "user_photo": "https://s3.amazonaws.com/creativetim_bucket/new_logo.png",
}
```

# Checklist:

- [ ] I completed all the information needed in my JSON file
- [ ] I verified that my snippet is working correctly in jsfiddle
