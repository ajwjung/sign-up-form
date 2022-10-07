# Sign-up Form

## Objective

To demonstrate understanding of the basics of forms by creating a mock sign-up form using HTML and CSS. Full details can be found on [The Odin Project's project page](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-sign-up-form).

### Specifications

The image file in this repository called `example-design.png` is the sample design layout provided by TOP. We do not need to copy the design exactly, but our form should at least have the same basic elements.

**Requirements**

1. There should be a left sidebar with a background image that has a logo plus text layered on top. The logo should have some kind of contrasting background to improve the readability of the text against the background image.

2. Use an external font for the "logo" section

3. Add form controls for supplying a first and last name, email, phone number, password, and password confirmation. The inputs should have a light border by default but can have two variations:
    * The password inputs should be given an error class (and thus some styling for invalid input)
    * Selected input should have a blue border and subtle box-shadow

4. A button to submit the form and "create an account". Use a color similar to tones found in the background image.

5. Include photo credits in the sidebar

**Optional**

1. Use JavaScript to validate that the password fields match each other

### Image Credits

* The sidebar image is by [alevision.co](https://unsplash.com/@alevisionco) from [unsplash.com](https://unsplash.com/)
* The camera icon is from [flaticon.com](https://www.flaticon.com/free-icon/camera_1998342)

## Author's Notes

Overall, I enjoyed learning about forms and seeing how you could play around with the built-in validation features. One thing I struggled with slightly was properly formatting the input fields. I originally tried to keep the html code cleaner by reducing the number of div containers used, which worked in terms of formatting them visually. But when I used `tab` to move to the next box, it would work vertically instead of horizontally (i.e., jump from "first name" to "email" then "password"). Since that would be an unusual way to fill out a form, I switched to using more divs around each input field alone.

In terms of the design, I am mostly satisfied with the simple look but there are some aspects I am still thinking about how to redesign. I particularly want to change the photo credits to look nicer but because of the background image I chose for the sidebar, it's hard to see the text without the transparent overlay.

**Next Steps**

I'm aware this mock sign-up form is not responsive and distorts on different devices. When zooming in, the contents also spill out of their respective divs. I plan to revisit this project in the future when I have learned more about making responsive websites to hopefully enhance this sample form.