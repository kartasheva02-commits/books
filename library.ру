from books import Book

class Library:
    def init(self):
        self.books = []
    
    def add_book(self, book):
        if isinstance(book, Book):
            self.books.append(book)
            return True
        return False
    
    def find_books_by_author(self, author):
        return [book for book in self.books if book.author.lower() == author.lower()]
    
    def get_all_books(self):
        return self.books.copy()
    
    def len(self):
        return len(self.books)
