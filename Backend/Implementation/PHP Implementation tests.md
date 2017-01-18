# Implementation test - PHP

- [1 - Collections](#1---collection)
 - [1.0 - Base Collection](#10---base-collection)
 - [1.1 - Sortable Collection](#11---sortable-collection)
 - [1.2 - Strict instance Collection](#12---strict-instance-collection)

***
## 1 - Collection
### 1.0 - Base Collection

To complete Collection test, solve all 4 tasks that are described below.

#### Task A - Create interface `ItemInterface` that will specify following methods:

- [ ] `getName() : string`
- [ ] `getPrice() : int`


#### Task B - Create interface `ItemFilterInterface`. Classes that will be implementing this interface will be used to filter collections. Interface needs to specify following method:

- [ ] `itemIsCompatibleWithFilter(ItemInterface $item) : bool`

#### Task C - Implement immutable collection class that will be capable of storing objects that implement `ItemInterface`. Objects that do not implement this interface cannot be added to the collection.



Collection class needs to meet following requirements: 

- [ ] Items stored in the Collection are considered identical when name and the price of the object that implements `ItemInterface` is the same in two different instances.
- [ ] Collection needs to be immutable
- [ ] Collection needs to return new instance upon modification of the collection (addition/deletion of items)
- [ ] Collection needs to return new instance of itself upon filtration. New instance needs to contain only the items that met filter requirements
- [ ] Collection needs to return new instance of itself when merged with another instance of Collection. New collection must not contain duplicates.
- [ ] Collection needs to return new instance of itself when intersected with another instance of Collection. New Collection needs to contain only items that are present in both Collections.
- [ ] Collection needs to return new instance of itself when differentiated with another instance of Collection. New Collection needs to contain only items that were not present in both Collections.
- [ ] Collection needs to be valid parameter for PHP `count()` function. `count()` function needs to return correct number of items that are stored in the Collection instance.
- [ ] Collection needs to be valid object to use for iteration via `foreach` loop. Collection needs to return all stored items upon iteration.
- [ ] Collection needs to be able to return all stored items as array.

#### Task D - Upload working code to GitHub repository and send link to the repository via email.
### 1.1 - Sortable Collection

#### Task A - Modify code from test 1.0 - Collection to comply with following requirements:

- [ ] Collection needs to return new instance of itself with all items sorted by price in ascending order when `sortByPrice()` method is invoked.
- [ ] Collection needs to return new instance of itself with all items sorted by name in ascending order when `sortByName()` method is invoked.

#### Task B - Upload working code separate to GitHub repository and send link to the repository via email.
### 1.2 - Strict instance Collection

#### Task A - Modify code from test 1.1 - Collection to comply with following requirements:

- [ ] Items stored in the Collection are considered identical when both reference the same instance.

#### Task B - Upload working code separate to GitHub repository and send link to the repository via email.




 


