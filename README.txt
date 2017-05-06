--------------------------------------------------------------------------------------
Address Class: 
All constructors and methods working.
List of methods: 
Address(String stNumber, String stName, String city, String state, String zip)
Address(Address a)
getStNumber()
setStNumber(String stNumber)
getStName()
setStName(String stName)
getCity()
setCity(String city)
getState()
setState(String state)
getZip()
setZip(String zip)
toString()
--------------------------------------------------------------------------------------
Person Class:
All constructors and methods working and inherited methods working.
List of methods: 
Person(String fName, String lName, String phone, Address address)
Person(Person p)
getPerStaticId()
getfName()
setfName(String fName)
getlName()
setlName(String lName)
getId() 
setId(String id) 
getPhone() 
setPhone(String phone) 
getAddress()
setAddress(Address address)
toString()
--------------------------------------------------------------------------------------
BodyBag Class: All constructors and methods working.
List of methods: 
BodyBag(int maxSize) 
addPerson(Person person)
findById(String id)
removeById(String id)
displayByType(Person person)
displayStudentsInOrder()
printStudentsInOrder()
displayFacultyInOrder()
printFacultyInOrder()
importStudentText(String textFileLoc)
importFacultyText(String textFileLoc)
importText(String textFileLoc) 
getBagLen()
--------------------------------------------------------------------------------------
Student Class:
All constructors and methods working and inherited methods working.
List of methods: 
Student(String fName, String lName, String phone, String major, Address address, String[] coursesTook, String[] coursesTaking, String[] coursesToTake)
Student(Student s)
getStudStaticId()
getMajor()
setMajor(String major)
getCoursesTook()
public void setCoursesTook(String[] coursesTook)
getCoursesTaking() 
setCoursesTaking(String[] coursesTaking) 
getCoursesToTake()
setCoursesToTake(String[] coursesToTake)
getCreditsTaking(CourseBag bag)
toString()
--------------------------------------------------------------------------------------
Faculty Class:
All constructors and methods working and inherited methods working.
List of methods: 
Faculty(String fName, String lName, String title, String phone, String officeAddress, Address address, double salary)
Faculty(Faculty f) 
getFacStaticId() 
getOfficeAddress() 
setOfficeAddress(String officeAddress)
getTitle()
setTitle(String title) 
getSalary()
setSalary(double salary)
toString()
--------------------------------------------------------------------------------------
Textbook Class: All constructors and methods working.
List of methods: 
Textbook(String title, String author, String publisher, String isbn, double price)
Textbook(Textbook t) 
getTitle() 
setTitle(String title)
getAuthor() 
setAuthor(String author) 
getPublisher() 
setPublisher(String publisher) 
getIsbn()
setIsbn(String isbn) 
getPrice() 
setPrice(double price)
toString()
--------------------------------------------------------------------------------------
TextbookBag Class: All constructors and methods working.
List of methods: 
TextbookBag(int maxSize)
add(Textbook textbook)
findByIsbn(String isbn)
removeByIsbn(String isbn)
display()
getBagLen()
importText(String textFileLoc)
--------------------------------------------------------------------------------------
Course Class: All constructors and methods working.
List of methods: 
Course(String courseTitle, String courseNumber, String textbookISBN, int numberOfCredits)
Course(Course c) 
getCourseTitle() 
setCourseTitle(String courseTitle) 
getCourseNumber() 
setCourseNumber(String courseNumber) 
getTextbookISBN() 
setTextbookISBN(String textbookISBN) 
getNumberOfCredits() 
setNumberOfCredits(int numberOfCredits)
toString() 
--------------------------------------------------------------------------------------
CourseBag Class: All constructors and methods working.
List of methods: 
CourseBag(int maxSize)
add(Course course)
findByCourseNumber(String courseNumber)
removeByCourseNumber(String courseNumber)
display()	
getBagLen()
importText(String textFileLoc)
--------------------------------------------------------------------------------------