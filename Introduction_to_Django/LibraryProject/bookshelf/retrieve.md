
---


---

### 📗 `retrieve.md`


# Retrieve Operation

## Command
```python
from books.models import Book

book = Book.objects.get(title="1984")
book.title, book.author, book.published_date

#output

<QuerySet [{'id': 1, 'title': '1984', 'author': 'George Orwell', 'publication_year': 1994}]>
# The book details are successfully retrieved from the database.
```
