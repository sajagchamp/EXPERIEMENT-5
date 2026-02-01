

# **AIM:**

To study dictionaries in Python and perform operations such as accessing, updating, adding, removing key–value pairs, searching, validating login, and finding highest values.

---

# THEORY 

* **Dictionary:** A dictionary stores data in *key–value pairs* using `{}`, where each key is unique.
* **Indexing with keys:** Values are accessed using keys like `dictname["key"]`.
* **Duplicate keys:** If the same key appears again, the latest value overwrites the previous one.
* **len():** Returns the number of key–value pairs in the dictionary.
* **type():** Shows the datatype of the dictionary.
* **Updating values:** You can change or add new entries using `dict[key] = value` or `update()` method.
* **pop():** Removes a key–value pair from the dictionary.
* **get():** Safely retrieves values and returns a default message if the key does not exist.
* **Membership (in):** Checks if a key exists in the dictionary.
* **max(dict, key=dict.get):** Returns the key with the highest value (useful for finding toppers).

---

# ALGORITHMS 

---

##  **ALGORITHM 1 – Update price of product**

1. Start the program and create a dictionary containing product names and their prices.
2. Display the original dictionary.
3. Update the price of a specific product using `dict[key] = new_value`.
4. Display the updated dictionary.
5. Stop.

---

##  **ALGORITHM 2 – Get student marks using get()**

1. Create a dictionary containing student names as keys and their marks as values.
2. Ask the user to enter a student’s name.
3. Use `get(name, "student not found")` to retrieve the marks safely.
4. Display the marks or show the “student not found” message.
5. Stop.

---

##  **ALGORITHM 3 – Get student marks using membership check**

1. Create a dictionary storing student marks.
2. Ask the user to input a name.
3. Check whether the name exists in the dictionary using the `in` operator.
4. If the name exists, print the marks; otherwise print “student not found”.
5. Stop.

---

##  **ALGORITHM 4 – Validate user login**

1. Start with a dictionary containing usernames as keys and passwords as values.
2. Ask the user to input a username and password.
3. Check if the username exists and the password matches the stored value.
4. If both match, print “login successful”.
5. Otherwise, print “invalid username or password”.
6. Stop.

---

## **ALGORITHM 5 – Find student who scored highest marks**

1. Create a dictionary containing student names as keys and their marks as values.
2. Use `max(marks, key=marks.get)` to get the key with the highest marks.
3. Store the returned key in a variable called topper.
4. Print the topper’s name and the corresponding marks using `marks[topper]`.
5. Stop.

---

# **CONCLUSION:**

In this experiment, we learned how dictionaries store values in key–value form and how they can be accessed, updated, modified, and searched. Concepts like retrieving values safely using `get()`, validating login credentials, and finding the highest marks were successfully implemented. Dictionaries provide fast, flexible, and powerful data handling in Python.

---

If you want, I can prepare **Experiment 5, 6, or combine all experiments into one PDF/DOCX** for submission.
