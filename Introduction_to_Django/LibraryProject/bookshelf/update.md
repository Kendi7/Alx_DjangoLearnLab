
---

### 📙 `update.md`

```markdown
# Update Operation

## Command
```python
from books.models import Book

book = Book.objects.get(title="1984")
book.title = "Nineteen Eighty-Four"
book.save()
book.title

#method 2
book = Book.objects.all()[0]      
book.title = 'Nineteen Eighty-Four'
book.save() 

Book.objects.all().values()

<QuerySet [{'id': 1, 'title': 'Nineteen Eighty-Four', 'author': 'George Orwell', 'publication_year': 1994}]>

#ouput
'Nineteen Eighty-Four'
# The book title has been successfully updated.
