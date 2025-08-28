
---

### 📕 `delete.md`

```markdown
# Delete Operation

## Command
```python
from bookshelf.models import Book

book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()

# Try retrieving all books again
Book.objects.all()

#output

(1, {'books.Book': 1})
# The book has been deleted successfully.

<QuerySet []>
# No books remain in the database.

