🗓️ 7-Day Plan
Day 1 → Arrays (Store Contacts)

Learn how to use arrays to keep multiple contacts.

Practice storing contacts like a list.

Example:

let contacts = [
  {name: "Billy", phone: "078123"},
  {name: "Alice", phone: "078987"}
];
console.log(contacts);

Day 2 → Objects (Contact Details)

Learn how to use objects to store more details for each contact (name, phone, email, birthday).

Example:

let contact = {name: "Billy", phone: "078123", email: "billy@gmail.com"};
console.log(contact.email);

Day 3 → Functions (Add Contacts)

Create a function to add new contacts into the array.

Example:

function addContact(name, phone, email) {
  contacts.push({name, phone, email});
}

Day 4 → Loops (List Contacts)

Learn how to display all contacts using loops.

Example:

for (let c of contacts) {
  console.log(c.name + " - " + c.phone);
}

Day 5 → RegExp (Search Contacts)

Use regular expressions to search contacts by name or email.

Example:

let regex = /gmail/;
contacts.filter(c => regex.test(c.email));

Day 6 → Dates & Math (Extra Practice)

Add the date and time when each contact was created.

Example:

let addedAt = new Date();

Day 7 → Review & GitHub

Review all code and test the app.

Push final version to GitHub.

Document the project and what I learned in this README.
