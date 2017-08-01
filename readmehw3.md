# Generating Email Addresses

In this activity, you will write a Python script to generate an email address using fields from a csv data file.

## Instructions

* Use csv.DictReader to read the contents of a csv file into a dictionary.

  * Use the first_name and last_name keys to create a new email dictionary consisting of the first initial and last name of the employee. `{"first_name": "John", "last_name": "Glenn"}` would generate the email dictionary: `{"email": "jglenn@example.com"}`.

  * Use update() or argument expansion `{**d1, **d2}` to update the row with the new email data.

  * Append the updated row to a list called `new_employee_data`.

* Use csv.DictWriter to output the new_employee_data to a csv file.

## Hints

* See the documentation for [DictReader](https://docs.python.org/3/library/csv.html#csv.DictReader).

* See the documentation for [update](https://docs.python.org/3/library/stdtypes.html#dict.update).

- - -

### Copyright

Coding Boot Camp © 2017. All Rights Reserved.
