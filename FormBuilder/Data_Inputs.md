---
layout: default
title: Data Input Fields
nav_order: 13
parent: MrQR Form Builder
---
<html>
<head>
<style>
.button {
  padding: 5px 12px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 12px;
  margin: 4px 2px;
  cursor: pointer; }
.button1 {background-color: #555555;} /* Black */
.button2 {background-color: white;}
.button3 {background-color: red;}
.button1 {color: white;}
.button2 {color: grey;}
.button3 {color: white;}
.button1 {border: none;}
.button2 {border: 1px solid grey}
.button3 {border: none;}
.button1 {border-radius: 5px;}
.button2 {border-radius: 5px;}
.button3 {border-radius: 5px;} 
</style>
</head>
</html>

# **Inputs**{: .text-purple-000 }
{: .no_toc }

{:toc }
- .TOC
  
![MrQR Form Builder](/assets/images/Forms/MrQR_Forms_Header.png "Header")

Once your new section is created, you can continue building your Form by adding [inputs](https://docs.mrqr.me/FormBuilder/Data_Inputs). These can be added by selecting the <button class="button button2">ADD INPUT</button> button, which will open the 'new field' panel.

![MrQR Form Builder](/assets/images/Forms/MrQR_Form_New_Section_Created.png "Created")

## Adding Inputs
{: .text-purple-000 }

There are five types of inputs:

* Text
* Date
* Photo upload
* Relationship
* User

The default content type is text but you can select whichever one you need with the drop down box that appears.

Each input requires a label, which can be a question, instruction, or statement that you want the User to address.

## Text
{: .text-purple-000 }
### Single & Multiple Line Text Inputs
{: .text-purple-000 }

Select `Text` from the 'type' drop down box. This input allows the user to enter a single line of text. Ticking the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Long Answer box allows the User to enter multiple lines of text where necessary.

![MrQR Inputs](/assets/images/Forms/MrQR_Form_New_Field_Text.png "Text")

Tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Required box if the input is required, and then press the <button class="button button1">SAVE</button> button to save your input.

### Single Tick Box
{: .text-purple-000 }

Selecting the <button class="button button2">ADD VALUE</button> button once creates a single option tick box answer. This is useful if you want the User who is submitting the Form to agree to a particular statement.

![MrQR Inputs](/assets/images/Forms/MrQR_Text_Single_Option.png "Single Line Text")

Tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Required box if the input is required, and then press the <button class="button button1">SAVE</button> button to save your input.

### Multiple Tick Boxes
{: .text-purple-000 }

Selecting the <button class="button button2">ADD VALUE</button> button multiple times will create several tick box answers. This is useful if you want the User submitting the Form to select a particular statement from a range of options.

![MrQR Inputs](/assets/images/Forms/MrQR_Text_Multiple_Option.png "Mutltiple Check Box")

Tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Required box if the input is required, and then press the <button class="button button1">SAVE</button> button to save your input.

If you want to allow the User to select multiple answers, tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Allow Multiple box.

Adding up to three values creates a checkbox list.
![MrQR Inputs](/assets/images/Forms/MrQR_Text_CheckBox_Form.png "Mutltiple Check Box")

Adding four or more values creates a dropdown box during Form entry.

![MrQR Inputs](/assets/images/Forms/MrQR_Text_Dropdown_Form.png "Mutltiple Dropdown Box")

[Back to Top](https://docs.mrqr.me/FormBuilder/Data_Inputs/)
{: .text-right }

## Date Inputs
{: .text-purple-000 }

Select `Date` from the 'type' drop down box. This input opens a calendar to enable the User who is submitting the Form to select a specific date.

![MrQR Inputs](/assets/images/Forms/MrQR_Form__New_Field_Date.png "Date")
Tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Required box if the input is required, and then press the <button class="button button1">SAVE</button> button to save your input.


[Back to Top](https://docs.mrqr.me/FormBuilder/Data_Inputs/)
{: .text-right }

## Photo Upload Inputs
{: .text-purple-000 }

Select `Photo Upload` from the 'type' drop down box. This input allows the User who is submitting the Form to upload images from their device.

![MrQR Inputs](/assets/images/Forms/MrQR_Form_New_Field_Image.png "Media")

Tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Required box if this input is required, and then press the <button class="button button1">SAVE</button> button to save your input.

If you want to allow the User to upload multiple photos, tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Allow Multiple box.

[Back to Top](https://docs.mrqr.me/FormBuilder/Data_Inputs/)
{: .text-right }

## Relationship Input
{: .text-purple-000 }

If you have additional Registers and Forms, you can link previously submitted Forms as an input on your new Form. This allows the User to select a previously submitted Form.

Select `Form Submission` from the 'type' drop down box and select the Register and Form you wish to link to your new Form.

![MrQR Inputs](/assets/images/Forms/MrQR_Form_New_Field_Form.png "Text")

Tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Required box if the input is required, and then press the <button class="button button1">SAVE</button> button to save your input.

[Back to Top](https://docs.mrqr.me/FormBuilder/Data_Inputs/)
{: .text-right }

## User Inputs
{: .text-purple-000 }

User inputs take the information entered into the User profile page. The User profile data is automatically entered onto a form when the User who is completing the form subscribes to the **MrQR**{: .text-purple-000 } Pro User Account.

User inputs include:
* Profile photo
* Full name
* Phone number
* National Insurance Number
* Date of birth
* Occupation
* Employer
* Employment status
* Medical information
* Next of kin - name
* Next of kin - contact number
* Address inputs
* Training record inputs
* Equipment inputs

Select the required User input from the 'type' drop down box.

![MrQR Inputs](/assets/images/Forms/MrQR_Inputs_User.png "User Inputs")

Tick the <img width="15" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Empty_Box.png"> Required box if the input is required, and then press the <button class="button button1">SAVE</button> button to save your input.

[Back to Top](https://docs.mrqr.me/FormBuilder/Data_Inputs/)
{: .text-right }

## Editing Inputs 
{: .text-purple-000 }

Once your inputs are saved, you can **Edit**{: .text-grey-lt-300 } or **Remove**{: .text-red-000 } them at any time. Alterations to Forms will not affect previous submissions. You can rearrange the order of inputs and contents by selecting and moving the <img width="20" alt="image" src="https://docs.mrqr.me/assets/images/Forms/MrQR_Form_Move_Field.png"> icon.

![Content](/assets/images/Forms/MrQR_Forms_Content_Text_Media.png "Text & Media")

Selecting **Remove**{: .text-red-000 } will open the 'remove field' panel. Select the <button class="button button3">REMOVE</button> button to confirm the field removal or the <button class="button button2">CANCEL</button> button to go back.

![Content](/assets/images/Forms/MrQR_Form_Remove_field.png "Remove Field")

[Back to Top](https://docs.mrqr.me/FormBuilder/Data_Inputs/)
{: .text-right }


