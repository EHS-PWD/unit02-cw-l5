### **Lesson 5: Forms and Form Elements - Classwork Assignment**

#### **Objective:**

In this lesson, students will start by creating the **basic structure of a user registration form**. They will only add the form itself, along with the `method` and `action` attributes, without including any input fields yet. This is the first step in building the complete registration form across Lessons 6-9.

---

### **Step-by-Step Guide:**

1. **Set Up Your HTML File**:

   - Create a new folder called `user-registration-form` inside of your `unit02` - `cw` folder.
   - Drag and drop the `user-registration-form` folder on VSCode to open it up.
   - Inside this folder, create a new file named `index.html`.
   - Add the basic HTML document structure:
     ```html
     <!DOCTYPE html>
     <html lang="en">
       <head>
         <meta charset="UTF-8" />
         <meta
           name="viewport"
           content="width=device-width, initial-scale=1.0"
         />
         <title>User Registration Form</title>
       </head>
       <body></body>
     </html>
     ```

2. **Create the Registration Form**:

   - Inside the `<body>`, start by creating a basic form structure with the `<form>` tag.
   - Set the form’s `method` to `"POST"` so that form data will be submitted to the server via POST (even though no server is involved yet).
   - Set the `action` attribute to `"#"` as a placeholder, which indicates that the form won’t yet send data to any server:
     ```html
     <form action="#" method="POST"></form>
     ```

3. **Add a Form Heading**:

   - Add a heading (`<h2>`) inside the form to indicate the purpose of the form:
     ```html
     <form action="#" method="POST">
       <h2>User Registration Form</h2>
     </form>
     ```

4. **Save and Preview Your Form**:

   - Save your `index.html` file.
   - Open it in a browser. You won’t see much yet, but you should see the heading: "User Registration Form".

5. **Submit Your Work**:
   - Once you've confirmed that the basic form structure is in place, submit the following:
     - The zipped `user-registration-form` folder with the `index.html` file.
   - Upload it to the classwork assignment on Google Classroom

---

### **Assessment Criteria**:

1. **Correct Use of Form Structure**:

   - The form includes the correct use of the `<form>` tag with `action="#"` and `method="POST"` attributes.
   - There are no additional form elements or fields at this stage.

2. **File Structure and Submission**:
   - The HTML file is correctly formatted and submitted properly along with the rest of the `user-registration-form` folder.
