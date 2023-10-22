# wordpress Form Generator
We will introduce briefly a form generator that is designed and implemented in Wordpress.

This form generator is a plugin you can install and use on the WordPress. In order to develop this plugin various technologies are used including, WordPress, bootstrap, PHP, and MySQL.

In the following section, we describe how we developed this plugin and how this plugin can be used in a project.

# In the first step, we should install the plugin on WordPress
after installing the plugin on WordPress you can see the following information. This information is added to the header file. 


![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/a8ceef16-75d4-47d3-8101-11c7d098cebd)

# plugin menu
Our program has two sections and it can be accessible by menu. In the first section, the forms are shown, and in the last section, the information can be shown.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/9e237b9a-923d-4afb-9d4a-1d5af11de6e3)


# Different types of forms
In this section, you can see various types of forms

## Insert, Update, Delete Form item
In this section, you should write the name and description of the form after that press the insert button in order to register your request.
![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/d90dd8ac-f6e3-443a-9ba5-80ef7910ba90)

you can also use this form to <strong>Delete</strong> and <strong>Update</strong> form information.

## show previous forms
In order to show the previous forms, you can select the name of the form and click on "show forms" to see the form in detail.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/9b81cde9-3f59-4683-b101-20cf843323b3)


## Form structure
every form has many types of fields and each field can be edited or deleted. this form generator  also covered various types of form input including, text, number, email, phone, address, multi-select, and select input.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/d6aec908-9e6b-474c-a9d2-232cf9f62161)

various actions also can be done such as Insert, edit, and delete a form field.
you can save your form by pressing the "insert" button. As you can see, various input buttons are supported.
In the form, you can determine the label, placeholder, error message, and whether the form field is required or not. 
by pressing the "create table" button, the table related to the form will be created.


### Insert field form
you can see the form that we can use in order to add a form field.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/3d50905a-2036-4a75-a1f7-2a8ab151b65a)

#### The order of the field in the form
#### The name of the field in the form 
#### The type of the field in the form
#### The initial value of the field in the form
#### The placeholder of the field in the form
#### The regex for validation of the field in the form
#### Sample of proper value for the field in the form
#### Whether the field is required or not
#### Whether the value of the field in the database is unique or not. for example, email is unique in register form.
#### The description of the field in the form
#### You can determine the type of the source for the checkbox or select input to fill the input values.
#### The domain determines the name of the source for the checkbox or select input
#### The event run an event on your input field
#### javascript code for running on your field form

### Edit, and Delete field form
For changing the information in the Field form, you can use the following form.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/1267f535-c43f-4759-a66a-9896c08231df)



# Relation between forms
These forms provide users with unique features to build high-quality and generalized forms. we consider the relationship between forms. forms can have one-to-one or one-to-many relationships with each other.

## One-to-one relationship between forms
You can use a form with all fields in another form in order to reuse the form. In this way, the new form can use all fields in another form. So we can say that form inherit all feature of form.

In the following image, we use another form as a field in our form. As you can see we only have a "Delete" or "Edit" button in order to remove or alter this field.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/372f2688-5999-4e43-ab1d-da304c0b0055)

 ## One-to-many relationship between forms
 In this kind of relationship between forms, we can put countless a form in another form. In other words, we can get related information based on the need. For example, users are required to put family members' information and you also know that the numbers of the family members are varied, so users can use this kind of form to register their information.

 ![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/90a315ca-427f-4df2-8b56-06ae88e9eaac)

 In the following image, you can see one-to-one and one-to-many relationships between forms in the form.



![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/dfc2df85-7d9c-42a1-bbeb-56ea59fc3376)


# Show stored data in the table

In the following image, you can click on the show information to access to information.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/9e237b9a-923d-4afb-9d4a-1d5af11de6e3)

## show information in one-to-one relationship
By pressing the "show info" button on the table you can have access to the information related to one-to-one relationships between tables.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/fa950291-8efc-4bb8-9449-1bfa0d275e22)


## Show information in one-to-many relationship

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/f18b9ff5-f1ec-4001-91ed-ad6a8ce7af4e)


## Use the form in the WordPress page
You can use the form on the WordPress page by putting the shortcode on the page with the proper identity. For example, in order to show form 1, we use  "[mlk_fg_show_form id=1]"
to add form to the page.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/f6cee932-7d7b-4cbd-985b-cfa3b975490e)


In the following image, You can see the result of the page and you can also add more information or description to the form.

![image](https://github.com/masoudmlk/wordpress_formbuilder/assets/20550253/2e06be02-99d9-468f-ae58-991e8f0fe678)




 





