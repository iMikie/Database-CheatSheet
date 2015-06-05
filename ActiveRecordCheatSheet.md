#Active Record Cheatsheet

Active Record is based on the notion that Ruby is better than SQL.  
And...
``` Ruby
mike = Band.new(name: "Yes")
mike.most_popular_album = "Close to the Edge"
```
is more fun to write than:
```SQL
INSERT INTO Bands 
    (band_name, label, founding_city)
VALUES 
    ('Yes','Atlantic','United Kingdom');            
UPDATE "bands" 
SET most_popular_album='Close to the Edge'
WHERE name='Yes'
```
You define and minipulate your data using Ruby classes and the SQL gets all done behind the scenes.  
It's also a framework for safely managing your database.

