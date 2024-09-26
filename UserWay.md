**UserWay Integration Documentation**

**Overview**

UserWay is a powerful web accessibility solution designed to help websites comply with accessibility standards such as WCAG (Web Content Accessibility Guidelines), ADA (Americans with Disabilities Act), and other regulations. The UserWay widget enhances website accessibility by offering features like keyboard navigation, screen reader compatibility, color contrast adjustments, and more.

This documentation outlines how to integrate the UserWay widget into your website, use its key features, and customize the widget according to your preferences.

**1. Integration of UserWay Widget**

**Step 1: Obtain UserWay Code**

1. **Create a UserWay account**:
   1. Visit the [UserWay website](https://userway.org/) and sign up for an account.
1. **Configure the widget**:
   1. In your UserWay account, choose your desired settings (e.g., languages, widget icon, position on the screen).
   1. After completing the widget setup, UserWay will generate a snippet of JavaScript code for you to integrate into your site.

**Step 2: Embed the Widget**

To integrate the UserWay widget into your website, follow these steps:

1. **Copy the generated script**:
   1. After configuring the widget in your UserWay dashboard, copy the provided JavaScript code snippet.
1. **Paste it into your website’s HTML**:
   1. Add the script right before the closing </body> tag of your website’s HTML file.

<script>

`    `(function(d){

`        `var s = d.createElement("script");

`        `s.setAttribute("data-account", "456Mp8fK3f "); 

`        `s.setAttribute("src", "https://cdn.userway.org/widget.js");

`        `(d.body || d.head).appendChild(s);

`    `})(document)

</script>

1. Replace YOUR\_ACCOUNT\_ID with the account ID provided during the configuration process.
1. **Save and publish**:
   1. After adding the script, save the changes and deploy or publish your website.

**Step 3: Verify the Widget Installation**

Once the widget is installed, navigate to your website to verify that the accessibility widget appears in the corner of the screen. If everything is set up correctly, the widget will be fully functional, and visitors will be able to interact with the accessibility features.

**2. Using the UserWay Widget**

Once integrated, the UserWay widget provides a variety of tools for improving website accessibility:

1. **Keyboard Navigation**:
   1. Allows users to navigate the website using only the keyboard, improving accessibility for those with mobility impairments.
1. **Screen Reader Compatibility**:
   1. Ensures compatibility with screen readers for visually impaired users.
1. **Color Contrast Adjustments**:
   1. Users can adjust the website’s contrast to make content more readable for those with visual impairments (e.g., color blindness).
1. **Text Sizing**:
   1. Provides options for increasing or decreasing text size.
1. **Highlight Links**:
   1. Highlights all clickable links, helping users with cognitive disabilities to easily identify links.
1. **Pause Animations**:
   1. Stops any animations that may cause distractions or trigger seizures in photosensitive individuals.
1. **Tooltips**:
   1. Adds tooltips to UI elements for users who may struggle with navigating the interface.

**3. Customizing the UserWay Widget**

UserWay allows for several customizations to match your website's design and accessibility needs. Customization is managed through the UserWay dashboard or by modifying the code snippet.

**Customizable Options:**

1. **Widget Position**:
   1. The widget can be positioned on any corner of the screen (default is the bottom right corner).
   1. Modify the position via the dashboard or by adding CSS to your website.

Example of custom CSS:

#userwayAccessibilityWidget {

`    `position: fixed;

`    `top: 10px;

`    `right: 10px;

}

1. **Icon Customization**:
   1. You can change the widget icon to better align with your brand.
   1. Select a different icon from the dashboard or upload your own custom icon.
1. **Language Settings**:
   1. UserWay supports multiple languages. Configure the default language and allow users to select their preferred language through the widget.
   1. Go to the language settings in the dashboard to customize this.
1. **Color and Styling**:
   1. The color scheme of the widget can be customized to match your website’s design. Set primary and secondary colors via the dashboard.
1. **Accessibility Statement**:
   1. You can link your own accessibility statement or use UserWay’s default accessibility policy to enhance transparency.
   1. Set this up under the "Accessibility Statement" section in the dashboard.
1. **Custom JavaScript**:
   1. You can further customize the behavior of the widget by including additional JavaScript. For example, to show/hide the widget based on user actions or add analytics tracking.

Example:

// Hide the widget on certain pages

if (window.location.pathname === "/hidden-page") {

`    `document.getElementById("userwayAccessibilityWidget").style.display = "none";

}

**4. Advanced Features**

**4.1 Integrating with Google Analytics**

UserWay provides integration with Google Analytics to track how users interact with the accessibility widget. This helps you measure the effectiveness of the accessibility tools on your website.

1. Enable Google Analytics tracking via the UserWay dashboard under the "Analytics" section.
1. Provide your Google Analytics ID for UserWay to start sending data to your analytics dashboard.

**4.2 Accessibility Reviews**

UserWay also offers periodic accessibility reviews for a more comprehensive audit of your website’s compliance with accessibility standards. This service is available at an additional cost and can be activated via the dashboard.

**5. Troubleshooting**

**Common Issues:**

1. **Widget Not Appearing**:
   1. Ensure that the script is correctly placed before the closing </body> tag.
   1. Verify that your account ID is correct.
1. **Script Conflict**:
   1. If there are other JavaScript libraries, there could be conflicts. Try placing the UserWay script at the bottom of your script tags.
1. **Customization Not Reflecting**:
   1. Double-check your custom settings in the UserWay dashboard and ensure that the browser cache is cleared after changes are made.

**6. Compliance and Best Practices**

**Compliance with WCAG 2.1:**

UserWay helps your site meet the requirements of WCAG 2.1 guidelines. It ensures:

- **Perceivable**: Content can be perceived by all users.
- **Operable**: The interface can be navigated via keyboard and other assistive technologies.
- **Understandable**: The content and interface are clear and easy to understand.
- **Robust**: Ensures compatibility with various assistive technologies.

**Ongoing Audits:**

It’s recommended to run regular accessibility audits using tools like the UserWay Accessibility Scanner to ensure continued compliance as you update or redesign your website.

**7. Conclusion**

UserWay is a versatile solution that improves the accessibility of your website. Whether you run a small blog or a large corporate website, this widget ensures that you meet global accessibility standards while offering a customizable, user-friendly experience for your visitors.

For more detailed information, visit the [UserWay documentation](https://userway.org/).

4o


