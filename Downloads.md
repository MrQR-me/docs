---
layout: default
title: Downloads
nav_order: 16
---

<html>
<head>
<style>
.button {
  padding: 5px 12px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 9px;
  margin: 4px 2px;
  cursor: pointer; }
.button1 {background-color: #555555;} /* Black */
.button2 {background-color: white;}
.button1 {color: white;}
.button2 {color: grey;}
.button1 {border: none;}
.button2 {border: 1px solid grey}
.button1 {border-radius: 5px;}
.button2 {border-radius: 5px;}
</style>
</head>
</html>

# **Mr QR**{: .text-purple-000 } **Downloads**
{: .no_toc }
please select the file you wish to view or download.

{:toc }
- .TOC

## Label 1
{: .text-purple-000 }
___

<div style="text-align: center;">
<a href="https://docs.mrqr.me/assets/images/Forms/stickers/MrQR_DB_Label.png" download="MrQR-Download">
  <img width="400" alt="image" src="https://docs.mrqr.me/assets/images/Forms/stickers/MrQR_DB_Label.png" /></a>
</div>

## Label 2
{: .text-purple-000 }
___

<div style="text-align: center;">
<a href="https://docs.mrqr.me/assets/images/Forms/stickers/MrQR_DB_Label.png" download="MrQR-Download">
  <img width="400" alt="image" src="https://docs.mrqr.me/assets/images/Forms/stickers/MrQR_DB_Label.png" /></a>
</div>

___


<!DOCTYPE html>

<html>
<head>
  <meta charset="utf-8">
  <title>Contact form submission</title>
</head>
<body>
  <form method="post" id="contact-form">
    <h2>Contact us</h2>
    <?php
      $errorMessage = ''; // Define $errorMessage
      echo(!empty($errorMessage) ? $errorMessage : '');
    ?>
    <p>
      <label>First Name:</label>
      <input name="name" type="text"/>
    </p>
    <p>
      <label>Email Address:</label>
      <input style="cursor: pointer;" name="email" type="text"/>
    </p>
    <p>
      <label>Message:</label>
      <textarea name="message"></textarea>
    </p>
    <p>
      <input type="submit" value="Send"/>
    </p>
  </form>

  <script src="//cdnjs.cloudflare.com/ajax/libs/validate.js/0.13.1/validate.min.js"></script>
  <script>
    const constraints = {
      name: {
        presence: { allowEmpty: false }
      },
      email: {
        presence: { allowEmpty: false },
        email: true
      },
      message: {
        presence: { allowEmpty: false }
      }
    };

    const form = document.getElementById('contact-form');
    form.addEventListener('submit', function(event) {
      const formValues = {
        name: form.elements.name.value,
        email: form.elements.email.value,
        message: form.elements.message.value
      };

      const errors = validate(formValues, constraints);
      if (errors) {
        event.preventDefault();
        const errorMessage = Object.values(errors)
          .map(function(fieldValues) {
            return fieldValues.join(', ');
          })
          .join("\n");

        alert(errorMessage);
      }
    }, false);
  </script>
</body>
</html>
