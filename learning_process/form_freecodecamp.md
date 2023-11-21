
---
title: "realizar un formulario freecodecamp"
date: 2023-11-19T08:43:36-05:00
draft: true
---

# creacion de un formulario
## cuerpo de **HTML_5**

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Registration Form</title>
<link rel="stylesheet" href="style.css"> 
</head>
<body>
</body>
</html>
```


```
 <form action='https://register-demo.freecodecamp.org'></form>
```
## The Action Attribute
The action attribute defines the action to be performed when the form is submitted.

Usually, the form data is sent to a file on the server when the user clicks on the submit button.

the form data is sent to a file called "action_page.php". This file contains a server-side script that handles the form data:

## The Method Attribute

The method attribute specifies the HTTP method to be used when submitting the form data.

The form-data can be sent as URL variables (with method="get") or as HTTP post transaction (with method="post").

The default HTTP method when submitting form data is GET. 



List of All <form> Attributes
|Attribute|	Description|
|---------|------------|
| accept-charset	| Specifies the character encodings used for form submission |
|action	|Specifies where to send the form-data when a form is submitted|
|autocomplete	|Specifies whether a form should have autocomplete on or off|
|enctype	|Specifies how the form-data should be encoded when submitting it to the server (only for method="post")|
|method	|Specifies the HTTP method to use when sending form-data|
|name	|Specifies the name of the form|
|novalidate	|Specifies that the form should not be validated when submitted|
|rel	|Specifies the relationship between a linked resource and the current document|
|target	|Specifies where to display the response that is received after submitting the form|

```
 <form method="post" action='https://register-demo.freecodecamp.org'>
    
    </form>
```

The first fieldset will hold name, email, and password fields. Start by adding four label elements to the first fieldset.
```
<form method="post" action='https://register-demo.freecodecamp.org'>
      <fieldset>

      </fieldset>
      <fieldset></fieldset>
      <fieldset></fieldset>
    </form>
```

2023-11-19-10:38