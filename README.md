# Assignment_3.3
Test whether two vectors are exactly equal (element by element). ans:
vec1 = c(rownames(mtcars[1:15,]))

vec2 = c(rownames(mtcars[11:25,]))

isTRUE(all.equal(vec1,vec2)) # returns true/false

identical(vec1,vec2) # returns true/false

all.equal(vec1,vec2) # returns number of differences

Sort the character vector in ascending order and descending order. ans:
vec1 = c(rownames(mtcars[1:15,]))

vec2 = c(rownames(mtcars[11:25,]))

sort(vec1) # vec1 in ascending order

sort(vec1, decreasing = TRUE) # vec1 in descending order

sort(vec2)

sort(vec2, decreasing = TRUE)

What is the major difference between str() and paste() show an example. ans:
str(vec1)

#returns the value, class and number of elements

#chr [1:15] "Mazda RX4" "Mazda RX4 Wag" "Datsun 710" "Hornet 4 Drive" "Hornet Sportabout" ...

paste(vec1)

#returns the value only(or just prints)

#[1] "Mazda RX4" "Mazda RX4 Wag" "Datsun 710" "Hornet 4 Drive"

#[5] "Hornet Sportabout" "Valiant" "Duster 360" "Merc 240D"

#[9] "Merc 230" "Merc 280" "Merc 280C" "Merc 450SE"

#[13] "Merc 450SL" "Merc 450SLC" "Cadillac Fleetwood"

mode(str(vec1))

mode(paste(vec1))

class(str(vec1))

class(paste(vec1))

Introduce a separator when concatenating the strings. ans:
x<-c("a","b","c")

y<-c("A","B","C")

paste(x,y)

paste(x,y,sep = ",")

paste(x,y,sep = "-")
