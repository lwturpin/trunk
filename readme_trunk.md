#Trunk#

This service is a digital closet for users to record their articles of clothing. Article of clothing are added by users, assigned a unique identifier, and are then globally accessible by all other users. In order to add an item into the global and their personal collection, the user must identify, at a minimum, the title, designer, and color. Users will want to search the collection based on any number of factors that include the type of article, designer or color.

#ID Attribute Values#
* Add Article of Clothing: Add article of clothing to your collection. Applied to a FORM to create a new entry.
* Search The Inventory: Query the global inventory collection to locate an article. Applied to a FORM for search.
* Update Article of Clothing: Use a FORM to update an existing article in your closet.

#Class Attribute Values#
* SearchInventory: Search the global inventory collection; applied to a  FORM tag.
* brand: Name of the brand or designer
* color: Color of the article
* title: Title of the article
* description: Details of the article
* allitems: The list of all articles in the global inventory collection
* user: The list of all articles in the user's closet

#Name Attribute Values#
* item[ID]: Unique identifier for each article
* item[title]: Brief title for the article; applied to an INPUT[text] element
* item[designer]: The designer of the article; applied to an INPUT[text] element
* item[color]: The color of the article; applied to an INPUT[text] element
* item[description]: Description of the article; applied to a INPUT[text] element

#Rel Attribute Values#
* Article: Link to a particular article; applied to an 'a href' tag
* Designer: Link to a designer's home page; applied to an 'a href' tag
* Closet: Link to the personal closet home page; applied to an 'a href' tag
