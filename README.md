# SoftwareSS UI
This is a premade CSS package which includes all the nessacary styles to build a new SoftwareSS website. The CSS file may be updated over time and we may add more language supports (such as react native, flutter and unity).

# Licensing
This package may only and only be used in SoftwareSS products and nowhere else. As long as "© SoftwareSS" is mentioned the copyright is ok.

# Concept
This is the UI concept that we based this on

![SoftwareSS UI Concept](https://user-images.githubusercontent.com/69199901/187264539-399d4590-34c0-4e72-a97d-7156275974d0.jpg)

# Usage
Simply import the css file in html and you should be good to go (remeber to bring the fonts folder as well).
Here is a list of classes that can be used:
- "app-title" is used for the title of the app, often used in the sidebar
- "bordered-div" is the foundation for bordered divs and may be used for cards that include some information
- "bordered-div-movable" allows the movment of the div on hover
- "important-bordered-div" is used to give a bordered div a purple gradient and glow which shows focus on that div, such as the most recent project card (dependent on "bordered-div")
- "bordered-div-purple" is mostly used for sign up and sign in pages (the containers with the form inside). It is intended to use this class without "bordered-div" but you can use it with "bordred-div" for a different result.
- "primary-btn" is used for primary buttons, while a button with a "important-boredered-div" is mostly used for sign up and sign in screens, the "primary-btn" if often used as a download buttons on a sidebar (mostly in conditions where the "important-boredered-div" is already used)
  - If there is no need for an icon simple put the text inside the button
  - If there is need for an icon, use a "p" element for text and then put your image (could be img, svg, i, ...) with the class "primary-btn-icon"


**Warning: Updates to documention are coming soon.**<br />
© SoftwareSS
