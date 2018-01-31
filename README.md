fog-creek-challenge-remix

A Java reiteration implementation of the previous fog-creek-challenge. Rather than implement the sorting in another static method, I streamlined the sorting into one statement. This is made possible by using an ArrayList data structure in which the sorted Key-Value entries not only retain its sorting, but also easily iterate through when printing the
hidden word. In addition, I used the Optional static class, which is a better practice of checking if an object is
null/not null using the isPresent() method call.