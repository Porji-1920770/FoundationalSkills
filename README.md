# FoundationalSkills

my_name <- "Praises"
my_age <- 21

minutes_in_a_day <- functions(24,60){
  min <- 24*60
  
  return(min)
}

hours_in_a_year <- functions(40,52){
  hours <- 40*52
  
  return(hours)
}

name <- "Praises"
age <- "21"

make_introduction <- function('name','age'){
  return(paste("Hello, my name is", name, "and I'm", age, "years old."))
}


my_intro <- my_introduction(my_name, my_age)

occurrences <- str_count(myIntro, "e")

inches_to_cm <- function(centimeters){
  return(centimeters * 2.54)
}

inches_tall <- 66

cm_tall <- inches_to_cm(inches_tall)


has_more_zs <- function(string1, string2){
  stringone <- str_count(string1, "z")
  stringtwo <- str_count(string2, "z")
  if(stringone == 0 && stringtwo == 0){
    return("Neither string contains the letter z.")
  }
  else if (stringone == stringtwo) {
    return("The strings have the same number of zs.")
  }
  else if(stringone > stringtwo){
    return(string1)
  }
  else if (stringone < stringtwo) {
    
  }
}


more_zs <- has_more_zs("zombie", "amazing")


remove_digits <- function(vectorstrings){
  x <- "0123456789"
  gsub("[0-9]", replacement = "", x = vectorstrings)
}

remove_digits(c("INFO 201","CSE 142"))


fluidconversion <- function('fluid_oz', a){
  if(b == 1){
    return (0.0625 * a)
  }
  else if(b == 2){
    return(0.0295735 * a)
  }
  else if(b == 3){
    return (0.0078125 * a)
  }
}


# Write a function `parks_and_rec()` that takes in two args (`weeks`, `hrs`) to 
# calculate how many episodes of the show "Parks and Rec" you can watch within a
# given time frame. The weeks arg is how many weeks they have to watch and the
# hrs arg is how many hours of TV they watch a day. Assuming that each episode 
# is 21 minutes long, how many episodes can the user watch? 
# Return the number of episodes as an numeric type.

parks_and_rec <- function('weeks', 'hrs'){
  
}


movies <- c("Black Panther", "Boyz N the Hood", "Hunger Games", "Get Out", "Girls Trip", "Think Like a Man")
top_three = movies[c(1:3)]


excited <- paste(movies, "is great movie!", sep="")


without_four <- movies[-4]
