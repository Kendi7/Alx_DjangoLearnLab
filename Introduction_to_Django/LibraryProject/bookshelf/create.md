# Create Operation

## Command

```python
from books.models import Book

book = Book.objects.create(
    title="1984",
    author="George Orwell",
    published_date=1949
)
book





#expected output
<Book: 1984 by George Orwell (1949)>
```

# A new Book instance has been successfully created and saved to the database.


