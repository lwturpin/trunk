#Trunk#

This service is a virtual closet for users to record their articles of clothing. Articles of clothing are added by users, assigned a unique identifier, and are then globally accessible by all other users. In order to add an item into the global and their personal collection, the user must identify, at a minimum, the name, designer, and color. Users will have the ability to search the collection by brand and to search users by email.

#ID Attribute Values#
* Add Article of Clothing: Add article of clothing to your collection. Applied to a FORM to create a new entry.
* Search The Inventory by Brand: Query the global inventory collection to locate an article by Brand. Applied to a FORM for search.
* Update Article of Clothing: Use a FORM to update an existing article in your closet.

#Class Attribute Values#
* Control: Add articles to the inventory collection; Add users to the database; Update articles or users; applied to a  FORM tag.
* allitems: The list of all articles in the global inventory collection
* user: The list of all articles in the user's closet
* article: Individual article information and a list of users who have the article in their closet

#Name Attribute Values#
* item[id]: Unique identifier for each article
* item[name]: Brief title for the article; applied to an INPUT[text] element
* item[brand]: The brand or designer of the article; applied to an INPUT[text] element
* item[url]: The brand's URL; applied to an INPUT[text] element
* item[color]: The color of the article; applied to an INPUT[text] element
* item[description]: Description of the article; applied to a INPUT[textarea] element
* item[userid]: Unique identifier of the article for the user. Used to control the article within the user's closet without impacting the inventory.
* item[username]: Username
* item[name]: Full name of the user
* item[email]: Email of the user
* item[password]: User's password

#Rel Attribute Values#
* Article: Link to a particular article; applied to an 'a href' tag
* Closet: Link to the global inventory; applied to an 'a href' tag
* Users: Link to the list of all users; applied to an 'a href' tag
* User: Link to a user's information and closet; applied to an 'a href' tag
