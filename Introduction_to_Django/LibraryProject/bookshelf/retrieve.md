
---

### 📗 'retrieve.md`

```markdown
# Retrieve Operation

## Command
```python
from books.models import Book
Book.objects.all().values()

#output

<QuerySet [{'id': 1, 'title': '1984', 'author': 'George Orwell', 'publication_year': 1994}]>
# The book details are successfully retrieved from the database.
```
