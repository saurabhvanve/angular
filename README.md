# AngularJS Dynamic Form and Data Table  

This project is a simple dynamic form and data table application built using AngularJS (1.6.9). It allows users to:  
- Enter details (Name, Phone, ID Number, and Picture).  
- Display the data in a table below the form.  
- Edit or delete each entry.  

---

## Features  

- **Form Validation:** Ensures all fields are filled and phone input is numeric.  
- **Image Preview:** Displays a thumbnail of the uploaded image.  
- **Edit and Delete:** Edit existing entries or delete them from the table.  
- **No Backend Required:** Data is stored in memory, so it resets on page reload.  

---

## Technologies Used  

- AngularJS 1.6.9 (via CDN)  
- HTML  
- Inline CSS  

---

## Prerequisites  

- A modern web browser (Google Chrome, Firefox, Edge, Safari).  
- No installation required.  

---

## How to Run the Project  

1. **Clone or Download** the repository.  
2. Open the downloaded folder.  
3. Open the `index.html` file in your browser.  

That's it! The form and table will be displayed, ready for you to use.  

---

## Usage  

1. Fill out the form fields:  
   - **Name:** Text input for the user's name.  
   - **Phone:** Numeric input for the phone number.  
   - **ID Number:** Text or number input for an identifier.  
   - **Picture:** Upload an image file (JPEG or PNG).  

2. Click on the **Save** button to add the entry to the table below.  
3. The table displays all entries with the following options:  
   - **Edit:** Loads the entry back into the form for updating.  
   - **Delete:** Removes the entry from the table.  

---

## Demo  

- The table updates dynamically without reloading the page.  
- The picture is displayed as a thumbnail in the table.  

---
## Notes  

- The data is stored in memory using AngularJS, so all entries are lost upon refreshing the page.  
- This is a simple prototype and does not include a backend or database.  
