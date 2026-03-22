from books import Book
from library import Library

def main():
    # Создаем библиотеку
    library = Library()
    
    # Добавляем книги
    book1 = Book("Преступление и наказание", "Федор Достоевский", 1866)
    book2 = Book("Война и мир", "Лев Толстой", 1869)
    book3 = Book("Мастер и Маргарита", "Михаил Булгаков", 1967)
    
    library.add_book(book1)
    library.add_book(book2)
    library.add_book(book3)
    
    # Демонстрация функционала
    print("Все книги в библиотеке:")
    for book in library.get_all_books():
        print(f" - {book}")
    
    print(f"\nВсего книг: {len(library)}")
    
    print("\nКниги Толстого:")
    tolstoys_books = library.find_books_by_author("Лев Толстой")
    for book in tolstoys_books:
        print(f" - {book}")

if name == "main":
    main()
