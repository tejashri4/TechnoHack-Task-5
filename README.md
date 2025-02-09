* Name:TEJASHRI SOMNATH MANDLIK.
* Company:TechnoHacks Solutions Pvt.Ltd.
* Domain:Python Development Programming.
* Duration:1 month.
* Mentor:Sandip Gawali.

# Overview of the Project
# Project:Build a Simple Contact Book
Problem Statement: Create a command-line contact book application that allows users to add, search, and delete contacts.


**Core Functionalities:**

* **Adding Contacts:**  The application should allow users to add new contacts.  This typically involves collecting information like name, phone number, email address (and potentially other details).  The application needs to store this information in a structured way (e.g., using a dictionary or a class to represent a contact).

* **Searching Contacts:**  Users should be able to search for contacts based on some criteria (e.g., name, phone number). The application should efficiently search the stored contacts and display the matching entries.

* **Deleting Contacts:**  The application should enable users to remove contacts from the contact book.  This usually involves identifying the contact to be deleted (perhaps through a search) and then removing it from the storage.

**Technical Considerations:**

* **Data Storage:**  You'll need to decide how to store the contact information.  Options include:
    * **In-memory:**  Simplest for small contact lists, but data is lost when the application closes.  Suitable for learning the core logic.
    * **File-based storage (e.g., CSV, JSON, text file):**  Persists data between sessions.  Requires handling file reading and writing.
    * **Database (e.g., SQLite):**  More robust and scalable for larger contact lists.  Adds complexity in terms of database interaction.

* **User Interface:**  Since it's a command-line application, the user interface will be text-based.  You'll need to design how users interact with the application through commands or menus.

* **Input Validation:**  It's important to validate user input to ensure data integrity.  For example, check if phone numbers are in the correct format or if required fields are filled.

* **Error Handling:**  The application should handle potential errors gracefully, such as invalid input, file not found, or contact not found.  Provide informative error messages to the user.

**Example Workflow:**

1.  **Add Contact:** User enters a command like "add," followed by the contact details (name, phone, email).
2.  **Search Contact:** User enters a command like "search," followed by the search term (e.g., a name or part of a phone number).
3.  **Delete Contact:** User enters a command like "delete," possibly followed by a name or index to identify the contact to delete.

**Development Steps (Suggested):**

1.  **Design Data Structure:** Decide how to represent a contact (e.g., dictionary, class).
2.  **Implement Add Functionality:** Start with adding contacts and storing them in memory.
3.  **Implement Search Functionality:** Add the ability to search for contacts.
4.  **Implement Delete Functionality:** Implement contact deletion.
5.  **Implement Data Persistence:** Choose a storage method (file or database) and integrate it.
6.  **Refine User Interface:** Design the command structure and user prompts.
7.  **Add Input Validation and Error Handling:** Make the application robust.
8.  **Testing:** Thoroughly test all functionalities.

