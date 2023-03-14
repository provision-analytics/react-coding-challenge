# Developer Interview Exercise

- Create the routes using any library
  - Home (path = /)
  - Detail (path = /:name)
- Create a custom table component that renders rows and columns based on an array of generic data and column keys, respectively.
    - Props:
        - data. Array of data
        - columnKeys. Array of strings. These strings should be one of the properties of the object inside the data array (extra: make this prop only accepts properties of the object inside the data array)
        - onSelectRow. A function that receives as parameter the data of the clicked row (extra: make the parameter be correctly typed based on the data type)
- Create a home page that make a request to https://swapi.dev/api/people and pass the results to the custom table that you just created to list the items.
    - Navigate to a detailed page when the user clicks on the table row using the name of the character as the slug and show the name in the page.
