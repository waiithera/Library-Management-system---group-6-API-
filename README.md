# Library-Management-system

## Group Members
- Member 1: 145350
- Member 2: 145886
- Member 3: 114460
- Member 4: 161416
- Member 5: 145515

## Project Implementation

### Models and Relationships
- Book: Represents a book in the library.
- Author: Represents an author of books.
- Member: Represents a library member.
- Borrow Records: Represents the loan records a book to a member.
- Librarians: Represent the librarian personel.

### View/viewsets and Roles
- BookViewSet: Handles CRUD operations for books.
- AuthorViewSet: Handles CRUD operations for authors.
- MemberViewSet: Handles CRUD operations for members.
- BorrowRecordsSet: Handles CRUD operations for borrow records.
- LibrariansSet: Handles the CRUD operations for librarians.

### Serializers
- BookSerializer: Serializes Book model data.
- AuthorSerializer: Serializes Author model data.
- MemberSerializer: Serializes Member model data.
- BorrowRecordSerializer: Serializes Borrow Record model data.
- LibrariansSerializer: Serializes Librarians model data.

### URL Patterns


### Setup Instructions
1. Clone the repository.
2. Navigate to the project directory.
3. Create a virtual environment: `python -m venv .venv`
4. Activate the virtual environment:
   - Windows: `.venv\Scripts\activate`
   - macOS/Linux: `source .venv/bin/activate`
5. Install the dependencies: `pip install -r requirements.txt`
6. Run the migrations: `python manage.py migrate`
7. Start the development server: `python manage.py runserver`

### Testing
- **Test Cases**: Tested all CRUD operations for each model.
- **Test Methods**: Used Postman for testing endpoints.
- **Screenshots location** : It is named after Postman Test Cases Screenshots for the tests.
- **Results**: All tests passed successfully.

