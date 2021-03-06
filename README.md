# _Restaurants_

#### _Allows users to create and sort restaurants by their cuisine type_

#### By _**Ryan Loos**_


## Setup/Installation Requirements

* _Clone this repository to your desktop_
* _Run composer install in Terminal_
* _start a server in web directory (php -S localhost:8000)_
* _change name of src file_
* _change name of tests file_
* _change name of src file_
* _change sourcing to tests_

_You must host this webpage locally_

## Behavior Driven Development

| Behavior      | Input       |Output|
| ------------- |-------------| -----|
| Create a cuisine category | "Italian" | "Italian" |
| list all cuisine categories | click | "Italian","thai" |
| Update a cuisine category | "Italian" | "Sicilian" |
| Delete a cuisine category | "Italian" | "" |
| find a cuisine using its individual ID | 1 | "Italian" |

| Create a restaurant category | "Olive Garden" | "Olive Garden" |
| list all restaurants | click | "Olive Garden","Thai orchid" |
| Update a restaurant name | "Olive Garden" | "Sicilian Garden" |
| Delete a restaurant | "Olive Garden" | "" |
| find a restaurant using its individual ID | 1 | "Olive Garden" |
| add unique descriptors to each restaurant | "Olive Garden" | "lots of breadsticks" |
| add cuisine id to each restaurant | "Olive Garden" | 1 |
| list all restaurants in a category | Italian | "Olive Garden", "Sicilian Garden" |

| Create a review category for text | "I liked it" | "I liked it" |
| Create a review category for rating (out of five) | "3" | "3" |
| List all reviews | click | "I liked it","I hated it" |
| Save review | "I liked it" | "I liked it" |
| delete all reviews | "I liked it" | "" |


## Known Bugs

_None yet_

## Support and contact details

_Ryan Loos: Rloos289@gmail.com_

## Technologies Used

_HTML,
PHP,
TWIG 1.0,
SILEX 1.1_

### License

*This webpage is licensed under the GPL license.*

Copyright (c) 2016 **_Ryan Loos_**
