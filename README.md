# Form validation

Vanilla JS form validation with regular expressions.

Live preview - https://ragtimecat.github.io/form_validation/

## Validation rules

- **Name**: 2 to 10 characters

  - **Valid examples**:

    - Al

    - Alessandra

    - _i know there could be names with more than 10 characters, but i did it just for easier testing_

- **Zip-code**(USPS): 5 digits, optionally follows with "-" and 4 digits.

  - **Valid examples**:

    - "33333"

    - "21343-2313"

- **Email**: default email, unlimited amount of chars followed by "@" unlimited amount of chars again, followed by "." and finally 2 to 5 chars in teh end

  - **Valid examples**:

    - jonhdoe@gmail.com

    - james@mayers.io

- **Phone**: default phone number with optional "+%any_digit%" country code.

  - **Valid examples**:

    - 981 141 67 59

    - (981)1416752

    - (981) 141 67 52

    - (981)-141-67-52

    - and the same with country code
