{PHP Brand Store}
https://jontoler.github.io/phpShoes/


{An application for manage the many to many relationships in a shoe store}

By Jon Toler

Description

{An application for a Brand inventory management. The owner can add Brand brands, and store, which carry each brand.}

Setup/Installation Requirements

Clone this repository to your desktop
Run composer install in Terminal
start a server in web directory (php -S localhost:8000)
change name of src file
change name of tests file
change name of src file
change sourcing to tests
You must host this webpage locally

Behavior Driven Development SPECS

Specifications

Able to retrieve Brand name

Input: database record for Brand named "Doc Martens"
Output: "Doc Martens"
Able to retrieve Brand ID Number

Input: database record for Brand named "Doc Martens", ID Number of 1
Output: 1
Can record Brand information into database

Input: Brand named "Doc Martens"
Output: create and retrieve "Doc Martens" from database
Can replace Brand name with new name

Input: new name for "Doc Martens" - "Dr Martens Boots"
Output: updated name - "Dr Martens Boots"
Able to retrieve all Brands

Input: database with the Brands "Doc Martens", "John fluevog", "Birkenstock"
Output: retrieved the list "Doc Martens", "John fluevog", "Birkenstock"
Can remove all Brands from database

Input: database with the Brands "Doc Martens", "John fluevog", "Birkenstock"
Output: retrieved an empty list
Can find Brand based on ID Number

Input: database record for Brand named "Doc Martens", ID Number of 1, finding Brand with ID Number of 1
Output: "Doc Martens"'s database record
Can update Brand record with new name

Input: new name for "Doc Martens" saved in database - "Dr Martens Boots"
Output: retrieved "Dr Martens Boots" from database
Can remove Brand record from database

Input: remove "Doc Martens" from database containing "Doc Martens", "John fluevog", "Birkenstock"
Output: only "John fluevog" and "Birkenstock" remain in database
Able to retrieve Title name

Input: database record for Title named "Doc Martens"
Output: "Doc Martens"
Able to retrieve Title ID Number

Input: database record for Title named "Doc Martens", ID Number of 1
Output: 1
Can record Title information into database

Input: Title named "Doc Martens"
Output: create and retrieve "Doc Martens" from database
Can replace Title name with new name

Input: new name for "Doc Martens" - "Dr Martens Boots"
Output: updated name - "Dr Martens Boots"
Able to retrieve all shoes

Input: new name for "Doc Martens" saved in database - "Dr Martens Boots"
Output: retrieved "Dr Martens Boots" from database


Input: remove "Doc Martens" from database containing "Doc Martens", "John fluevog", "Birkenstock"
Output: only "John fluevog" and "Birkenstock" remain in database
Able to retrieve Store name

Input: database record for Store named "Doc Martens"
Output: "Doc Martens"
Able to retrieve Store ID Number

Input: database record for Store named "Doc Martens", ID Number of 1
Output: 1
Can record Store information into database

Input: Store named "Doc Martens"
Output: create and retrieve "Doc Martens" from database
Can replace Store name with new name

Input: new name for "Doc Martens" - "Dr Martens Boots"
Output: updated name - "Dr Martens Boots"
Able to retrieve all Stores

Input: database with the Stores "Doc Martens", "John fluevog", "Birkenstock"
Output: retrieved the list "Doc Martens", "John fluevog", "Birkenstock"
Can remove all Stores from database

Input: database with the Stores "Doc Martens", "John fluevog", "Birkenstock"
Output: retrieved an empty list
Can find Store based on ID Number

Input: database record for Store named "Doc Martens", ID Number of 1, finding Store with ID Number of 1
Output: "Doc Martens"'s database record
Can update Store record with new name

Input: new name for "Doc Martens" saved in database - "Dr Martens Boots"
Output: retrieved "Dr Martens Boots" from database

Input: remove "Doc Martens" from database containing "Doc Martens", "John fluevog", "Birkenstock"
Output: only "John fluevog" and "Birkenstock" remain in database

Input: Brand "Doc Martens", find by Brand ID
Output: Returns "The Milkman of Dune"
Retrieve Store from a Loan

Known Bugs

isn't passing yet will continue to work on functionality

Support and contact details

Jon Toler: tolerjonathan@gmail.com.

Technologies Used

HTML, PHP, TWIG 1.0, SILEX 1.1

License

This webpage is licensed under the GPL license.

Copyright (c) 2016 Jon Toler
