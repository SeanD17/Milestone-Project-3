Access the Python Interpreter:
python3

Import the 'mongo' instance from app.py:
from app import mongo

Create Index on the 'books' collection, using 'book_name' and 'author' keys:
NOTE: You can only have a maximum of ONE Index on the collection, but multiple keys permitted on that Index.
mongo.db.books.create_index([("book_name", "text"), ("author", "text")])

See all Index information:
mongo.db.books.index_information()

Drop/Delete a single Index:
mongo.db.books.drop_index('bookk_name_text_author_text')

Drop/Delete all Indexes:
mongo.db.books.drop_indexes()

Quit the Python Interpreter:
quit()