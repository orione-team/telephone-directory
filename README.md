# Telephone Directory Versione Web Application

You are to build a web application that provides a simple telephone directory.
Technicalities

## Entries

The application handles a set of entries, that contain a first name, last name, and a telephone number.
The entries should be validated, so that it's not possible to enter an empty first or last name; and the phone number should be of the form
```
+39 02 1234567
```

That is a "+" followed by a nonempty group of digits, a space, a nonempty group of digits, a space, a group of digits with at least 6 digits.

The application consists of the following pages:
* **Home page**
 * Contains a text field that allows to search through all the entries by name or number. When I enter text in the field, the page will be reloaded with a table containing all the entries that match the text I entered.
 * The page contains a link to the "add new entry" page.
 * When an entry is displayed, it contains a link to the "edit this entry" page.
* **Add new entry page**
 * Contains a form for entering a new entry.
* **Edit entry page**
 * Contains a form for modifying an existing entry.

### Extra activities (not mandatory)

* Deploy your webapp on heroku.

## General requirements

- You may use whatever programming language/platform you prefer. Use something that you know well.
- You may commit your code on Github or any other SCM repository you prefer (e.g. bitbucket, gitlab, etc) and send us the link.
- You must release your work with an OSI-approved open source license of your choice.
- You must deliver the sources of your application, with a README that explains how to compile and run it.

**IMPORTANT:**  Implement the requirements focusing on **writing the best code** you can produce.
