# Pseudocode
Here is a selection of operations that user's will be able to perform. I have written some pseudocode to assist me when it comes to implementation. These represent a high-level overview of how each operation will be carried out.

### Creating a new collection
```
collections = []

newCollection = Collection(name)
collections.add(newCollection)
```

### Getting a collection
```
collections = [...]

if (collections.has("wishlist")) then
    return collections["wishlist"]
else
    return error
```

### Creating a new set
```
newSet = LegoSet(
    setNumber,
    name,
    pieces,
    price,
    status,
    theme,
    minifigures
)

collection["wishlist"].addSet(newSet)
```