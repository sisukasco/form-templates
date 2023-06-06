# Free HTML Form Templates Collection
This is a set of free HTML form templates. You can copy and paste the form code to your website. See the instructions below for more details

## How to use the form

This forms is ready to be used as-is. You just need to embed the provided HTML code in your webpage where you want the form to appear. 

However, the forms are only a frontend form (HTML only). This means it has no backend logic to process the data the users submit. To make it functional, you need to connect to a back-end form processing service. Here are the steps to connect your form to back-end.

1. Go to [Ratufa.io](https://www.ratufa.io)

2. Press the "Connect Your form" button. Ratufa.io will provide a code to connect your form to the back-end. Copy the code and paste just above the closing `</body>` tag of your form page.

Test your form and see that you can receive form submissions at Ratufa.io.

Now customise the back-end in Ratufa.io to receive form submission notifications in your email. You can also add advanced form handling like sending an auto-response to the user who submitted the form.


## How to customize the form
Customizing the form involves changing the HTML code to better suit your needs. Here are a few basic ways you can do this.

### Forms that use Bootstrap framework

#### Add/Remove Fields: 
You can add new input fields by copying an existing `<div class="form-group">...</div>` block and modifying it. Conversely, you can remove any existing fields by simply deleting their corresponding `<div class="form-group">...</div>` block.

#### Modify Options: 
If you want to add more options to the "Position" dropdown, you can add more `<option>...</option>` tags inside the `<select class="form-control" id="position">...</select>` tag.

#### Modify Labels: 
To change the text of the labels (e.g., "Name", "Email"), just modify the text inside the `<label>...</label>` tags.

#### Modify Placeholders: 
The placeholder text for the input fields can be modified by changing the text inside the placeholder attribute in the `<input>` tags.

#### Add Description: 
If you want to add more information about the job position, you can edit the text inside the `<div class="jumbotron">...</div>` block.

#### Change Styling: 
To modify the form's appearance, you can overwrite Bootstrap styles with your own CSS. You can either modify the Bootstrap CSS file directly or write your own CSS rules in a separate file or in a `<style>...</style>` block in the HTML head.

Remember, any changes you make should not only align with your needs, but also follow best practices for user experience and accessibility. Also, always add validations as required to the HTML code.