
# CSV-Based Goods Location Manager
A simple C++ utility to track location of goods and perform a variety of operations including search, insertion, updation & deletion of data stored in a *.csv file

(portable standalone .exe file | Windows)
written in c++ (Imgui)

Theme: Asteroid

![Homepage](snap3.png)

Theme: Lollipop

![Homepage](home.png)

Theme: SpringHeart

![Homepage](snap1.png)

### Instructions For usage :-

This software supports the usage of *.csv* files as input and performs operations such as search, insertion, updation and deletion on the supplied *.csv* file.

Note:- Target file must be renamed as *'input.csv'* for the software to recognise the file.
If no file is available use Insert menu to create a new *'input.csv'* file.

## Working :-

![working](snap2.png)


The utility recognises the shelf no./rack/location of the item by reading the text followed by *$* symbol.
If no *$* is present, it indicates that no shelf/location is assigned to that item.

### Features:-

1. Searching items by shelf No./rack No./location.
2. Viewing all items that have location/Shelf assigned to it (by using *$* As keyword).
3. Inserting New item.
4. Updating item's location/shelf No.
5. Deleting item from *input.csv* file permanently.

## License:-

MIT License
