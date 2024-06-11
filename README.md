# Telford Lounge Chair Webpage

Project Overview
This project showcases a product page for the Telford Lounge chair, designed to be responsive and visually appealing with animations. The webpage includes features such as color selection, a detailed description, and an add-to-cart functionality.

# Features
• Responsive Design: The webpage adjusts smoothly to various screen sizes, ensuring a seamless experience across devices.

• Animations: Subtle animations enhance the user experience, making interactions more engaging.

• Color Selection: Users can choose from different color options for the chair.

• Pricing Display: Displays original and discounted prices.

• Selectors:
   • Adjacent Sibling Selector: Used for styling elements immediately following a specified element.
   • General Sibling Selector: Used for styling elements that follow a specified element, not necessarily immediately.
   
# Technologies Used
• HTML5: For the basic structure of the webpage.
• CSS3: For styling, animations, and responsive design   

# File Structure
• index.html: The main HTML file that contains the structure of the webpage.
• styles.css: The CSS file that includes styles and animations.

# Detailed Explanation
• HTML
   • The main structure includes sections for the product image, product name, pricing, description, and color selection.
   • An Add to Cart button is provided for users to make a purchase.
• CSS
   • Responsive Design:
       • Media queries are used to adjust the layout for different screen sizes.
       • Flexbox is utilized for flexible layout structures.
• Animations:
    CSS animations and transitions are applied to elements to enhance user interaction.
       •Selectors:
       
          •Adjacent Sibling Selector (+):
            .description + .details {
               display: none;
              }
              
          •General Sibling Selector (~):  
             .color-option:hover ~ .color-name {
                color: red;
               }

