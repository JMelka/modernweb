# Chapter 3: Practice with a table

## Objectives
* Add a table to your document

1. Copy the `table.css` from the `/Demos/Chapter03-HTML/tables` directory into your project directory - for some better styling with standard table tags
 
1. In your project create a file called `table.html`. Start `table.html` using the  the html:5 emmet abreviation.

1. Copy the `table.css` file from the solution of this lab into your project. 

1. In the `<head>` of `table.html`, add the following line:
   
   ```CSS
   <link rel="stylesheet" type="text/css" media="screen" href="table.css" />
   ```

1. You will create the table structure using EMMET abbreviations with a caption and <th> for headers.

    In the body area of your html file, copy the following line. It really activates when you are typing so, after you paste the following, hit the backspace and recreate the last character 3:

    ```
    table>tr*3>td*3
    ```

1. Change the first row to use th instead of td. For the values use: name, email, phone. 

1. For the other two rows add some sample data.

1. Add a caption element which is an immediate child of the table element. (Right after the opening `<table>` tag)

1. In caption add the text `Contact Info`

1. Mark your work as complete

## Bonus

1. Create a table for the recipe data with columns for serving sizes, calories, etc. 