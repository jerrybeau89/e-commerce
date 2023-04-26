# e-commerce
This is a repo that contains code for the back-end of an e-commerce website

## Description
E-commerce is an application that will accept a users input in Insomnia to manipulate a database, allowing the user to create new, update, or delete categories, products, and tags. The user also has the ability to view all categories, products and tags, or individual categories, products and tags by id.

https://github.com/jerrybeau89/e-commerce


 ## Table of Contents
  
  1. [Installation](#installation)
  2. [Usage](#usage)
  3. [License](#license)
  4. [Tests](#tests)
  5. [Video](#video)
  6. [Questions](#questions)

## Installation
npm install e-commerce

## Usage
Navigate to the integrated terminal associated with the server.js file. 

 Then you must source the schema.sql, as well as seed the file. Ensure your MySQL server is started. 

    You can run the following commands:

  `mysql.server start`

  `mysql -u root -p`

    Enter your password, then enter:

  `source db/schema.sql`

    Then to exit MySQL:

  `quit;`

    Then, enter:

  `npm i`

  `npm seed`

  `npm start`

    And the application will start!

From there you will transition to Insomnia and use the GET, POST, PUT, and DELETE routes available to interact with the database. You will be able to create new, update, or delete categories, products, and tags. You will have to set up a .env file. an example is located in the repo. 

## License

MIT License

Copyright (c) 2023 Jerry Beau Baggett

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Tests
Backend testing can be done through Insomnia using JSON data. 

## Video
Here is a video of the program being used: https://drive.google.com/file/d/1qZ4J3CFbojvTv3QKSfov1uGNFIzjWxd6/view

## Questions

  Please contact me at jerrybeau89@gmail.com with any questions you may have. You can also find my GitHub at https://github.com/jerrybeau89. Thank you! 


​


