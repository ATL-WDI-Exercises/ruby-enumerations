##Enumerable Exercises

### #2 - Wine Cellar

- Here is an array containing some wines:

```ruby
wine_cellar = [
  {:label => "Rutherford Hill", :type => "Chardonnay", :color => "white"},
  {:label => "Nina Veneto", :type => "Pinot Grigio", :color => "white"},
  {:label => "Wairau River", :type => "Sauvignon Blanc", :color => "white"},
  {:label => "Tangley Oaks", :type => "Merlot", :color => "red"},
  {:label => "Chimney Rock", :type => "Cabernet Sauvignon", :color => "red"},
  {:label => "Sanford", :type => "Pinot Noir", :color => "red"},
  {:label => "Alderbrook", :type => "Pinot Noir", :color => "red"},
  {:label => "Colavita", :type => "Pinot Noir", :color => "red"},
  {:label => "Markham", :type => "Chardonnay", :color => "white"},
  {:label => "Angeline", :type => "Pinot Noir", :color => "red"}
]
```

Write code that:
  
  - Adds a wine of your choice to the cellar

`wine_cellar.push({:label => "Kroger", :type => "Cab", :color => "red"})`

  - Returns a random wine from the cellar

`wine_cellar.sample`

  - Returns an array of just the white wines

`wine_cellar.select { |wine| wine[:color] == "white"}`

  - Returns an array listing the unique types of wine
  
```ruby
unique_wine_types = []

unique_wines.each do |wine_type|
	unique_wine_types << wine_type[:type]	
end

puts unique_wine_types
```
  - Returns an array with the all the wines that have 2-word labels
  - Returns an array with the labels of the wines that a type of Pinot Noir



### #3 - Students

```ruby
students = ["Adam Barrett", "Jacob Cain", "Mikael Davis", "Salil Doshi", "Jonathan Eva", "Elaine Fang", "Parker Hart", "Richard Hessler", "Mary Hipp", "Inhak Kim", "Yi-Hsiao Liu", "Randy Latz", "Alexi Phillipson", "Matt Rundo", "Gabe Snyder", "Stephen Stanwood", "Joella Straley", "Brett Wallace", "Thomas Weaver"]
```

- Write code that:
  - Prints a random student
  - Prints the index of "Randy Latz"
  - Prints the fifth person (In this case it's Jonathan)
  - Prints a list of all the student names on one line, with each name separated by a pipe: |
  - Prints a list of the all of the last names
  - Prints the full names of all of the students with M names (Mikael, Mary, Matt)


### #4 - Starting a band

```ruby
people = [
  {:name => "Peter", :money => 5, :plays_instrument => true},
  {:name => "Greg", :money => 10, :plays_instrument => false},
  {:name => "Travis", :money => 80, :plays_instrument => true},
  {:name => "Yi-Hsiao", :money => 20, :plays_instrument => false},
  {:name => "Parker", :money => 20, :plays_instrument => false},
  {:name => "Jake", :money => 90, :plays_instrument => false},
  {:name => "Matt", :money => 10, :plays_instrument => true},
  {:name => "Mary", :money => 15, :plays_instrument => false},
  {:name => "Alexi", :money => 8, :plays_instrument => false},
  {:name => "Salil", :money => 7, :plays_instrument => true},
  {:name => "Stephen", :money => 35, :plays_instrument => true},
  {:name => "Adam", :money => 12, :plays_instrument => true},
  {:name => "Joella", :money => 75, :plays_instrument => false}
]
```

* Who has the most money?
* If we have at least 5 people that play instruments we can start a band. Can we?
* If a new drum set costs $350, do we have enough money to buy one?
