There are four ways to create objects.

1. Literal Notation (with the properties added after the object is created)

example:
var house = {}
house.rooms: 3;
house.yard: true;
house.baths: 2;


2. Literal Notation (with properties and methods contained in the object)

var house = {
    house.rooms: 3,
    house.yard: true,
    house.baths: 2
}

3. Object Constructor Notation (properties and methods added after creating the object)

var house = new Object()

house.rooms: 3;
house.yard: true;
house.baths: 2;

4. Object Constructor Notation  (Uses the 'this' statement. Able to create multiple objects quickly)

function House(rooms, yard, baths) {
    this.rooms: rooms;
    this.yard: yard;
    this.baths: baths;
}