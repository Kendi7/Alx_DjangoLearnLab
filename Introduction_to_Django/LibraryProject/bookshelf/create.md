# Create Operation

## Command
```python
from books.models import Book

book = Book(title = "1984", author = "George Orwell", publication_year = 1994)
book.save()




#expected output
<Book: 1984 by George Orwell (1949)>
```

# A new Book instance has been successfully created and saved to the database.


