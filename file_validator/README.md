# file_validator
Provides sourced functions to validate a given file.

## How to use
```shell
. file_validator
__file_validator _validator "file" "Success message" "Error message"
```

## Example
```shell
. file_validator
__file_validator _exists "foo.txt" "File exists." "File does not exist!"
```

## Available validation functions

`_validate`

Validate if the file exists

`_exists`

Validate if the file exists

`_is_regular`

Valid if the file is regular

`_is_readable`

Valid if the file is readable

`_has_content`

Validate if the file has content
