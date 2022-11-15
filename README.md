# Turkish Restaurant Project

## Summary
Client wants to have a website for his Turkish restaurant. Client has several stores of restaurant. He wants to put restaurant's food and drink menu onto the website, including their image and price.

Considering client's needs, website that has locations page will be made to include the all of the stores. Then we can put address, phone and photo from stores to complete the locations page.

Contact page will include forms that would be used by customers to contact the client.

About us page will have background information about the restaurant or/and its owner as well as images related to it.

Menu page will be necessary since client want to put menu inside website. Menu page can contain both food and drink items. If client wants to have separate pages for each of them, that can be done as well. 
  - Food items will include fields for name, description, image and price of the dish along with whether dish is vegetarian, halal, gluten-free, recommended by restaurant or not.
  - Drink items will include fields for name, description and price for the different quantity of the drink.

## Sitemap
![Sitemap](readme/sitemap.png)

## Extras
- There are many-to-one(many items goes to one category) relation between the menu-items / menu-categories as well as between drink-items / drink categories.
    - Both of them used for putting items under their respective categories.

- There are two re-usable component which are store name/address/phone component and drink price/quantity. 
    - Store component is used so that it'll be easy to add several stores to the location page.
    - Drink component is used so that it'll be easy to add price for different quantities.

## Notes
- I wanted to add photo to each store location that is taken in front of store but I couldn't find any suitable image.

## Attributions
- [Adana Kebab Image](https://www.pexels.com/photo/gida-plaka-yemek-fotografciligi-kebap-6089827/)
- [Baklava Image](https://www.pexels.com/photo/gida-tatli-lezzetli-mutfak-7803118/)
- [Contact Us Page Mixed Food Image](https://www.pexels.com/photo/gida-plaka-masa-et-7426866/)