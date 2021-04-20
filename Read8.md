# CSS Layout

**A website is often divided into headers, menus, content and a footer:**

![imageOfCssLayout](https://media.geeksforgeeks.org/wp-content/uploads/website_layout-300x268.png)

## Header

**A header is usually located at the top of the website (or right below a top navigation menu). It often contains a logo or the website name:**

`.header {`
`  background-color: #F1F1F1;`
`  text-align: center;`
`  padding: 20px;`
`}`

## Navigation Bar

**A navigation bar contains a list of links to help visitors navigating through your website:**

* The navbar container, Like:

     `.topnav {`

     `  overflow: hidden;`

     `  background-color: #333;`

     `}`
* Navbar links, Like:

     `.topnav a {`

     `  float: left;` 

     `  display: block;`

     `  color: #f2f2f2;`

     `  text-align: center;`

     `  padding: 14px 16px;`

     `  text-decoration: none;`

     `}`
* Links - change color on hover

     `.topnav a:hover {`

     `  background-color: #ddd;`

     `  color: black;`

     `}`

## Content

**The layout in this section, often depends on the target users. The most common layout is one (or combining them) of the following:**

1. `column (often used for mobile browsers)`
2. **column (often used for tablets and laptops)**
3. *column layout (only used for desktops)*



## Footer

**The footer is placed at the bottom of your page. It often contains information like copyright and contact info:**

>Example:

`.footer {`

`  background-color: #F1F1F1;`

`  text-align: center;`

`  padding: 10px;`

`}`

