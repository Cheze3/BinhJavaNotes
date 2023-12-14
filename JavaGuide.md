### Data Types:
1. boolean (True/False)
2. int ('1, 2, 3')
3. double('larger numbers')
4. float('1.45, 6.4')
5. char ("A", "b", "!")
6. String("Hello world!")

### Reference Data Types:

1. **Object:** The root class of all Java classes.
2. **String:** Represents a sequence of characters.
3. **Array:** A collection of elements of the same data type.
4. **Class:** Represents a class type.
5. **Interface:** Represents an interface type

### Setup:

"public static void main(String[] args) {}"

Tao void:
[Public] static void "name" (input variables)

### Fuction:

1. **Main Function:**
    
    - `public static void main(String[] args)`: The main entry point of any Java program.
2. **Input and Output:**
    
    - `System.out.println("Hello, World!");`: Prints a message to the console.
    - `Scanner scanner = new Scanner(System.in);`: Reads input from the console.
3. **Variables and Data Types:**
    
    - `int num = 10;`: Declares an integer variable.
    - `double pi = 3.14;`: Declares a double-precision floating-point variable.
    - `String name = "John";`: Declares a String variable.
4. **Control Flow:**
    
    - `if (condition) { /* code */ }`: Executes code block if the condition is true.
    - `else if (condition) { /* code */ }`: Additional condition to check if the previous if statement is false.
    - `else { /* code */ }`: Executes if none of the previous conditions are true.
    - `switch (variable) { case value: /* code */ break; }`: Switch statement for multiple conditions.
5. **Loops:**
    
    - `for (int i = 0; i < 10; i++) { /* code */ }`: Executes a block of code repeatedly.
    - `while (condition) { /* code */ }`: Executes a block of code while a condition is true.
    - `do { /* code */ } while (condition);`: Executes a block of code at least once and then repeatedly while a condition is true.
6. **Methods/Functions:**
    
    - `public void myFunction() { /* code */ }`: Declares a method.
    - `int add(int a, int b) { return a + b; }`: Method with parameters and a return value.
7. **Arrays:**
    
    - `int[] numbers = {1, 2, 3, 4, 5};`: Declares an array of integers.
8. **Classes and Objects:**
    
    - `class MyClass { /* code */ }`: Declares a class.
    - `MyClass obj = new MyClass();`: Creates an instance of a class.
9. **Exception Handling:**
    
    - `try { /* code */ } catch (Exception e) { /* handle exception */ }`: Handles exceptions.
10. **File I/O:**
    

- `File file = new File("filename.txt");`: Creates a File object.
- `FileReader reader = new FileReader(file);`: Reads from a file.
- `BufferedWriter writer = new BufferedWriter(new FileWriter("filename.txt"));`: Writes to a file.
11. **Void**
- `static void 'name' (input variables){'code'}`: Creates a void

### Object Orientated Programing:

- Encapsulation (Tính đóng gói , tính bao đóng)

- Access modifier: private, public, protected, default - Bảo vệ tính an toàn dữ liệu của đối tượng, đảm bảo tính đúng đắn của chương trình. 

- Abstraction - Giấu sự chi tiết - abstract class, abstract, interface - Inheritance - Subclass kế thừa lại các thuộc tính và phương thức của parent class (supper clas) - extend, override - 

- Polymorphism - Biểu hiện ở override và overload - Override: Phương thức ở lớp con ghi đè lên phương thức của lớp cha - Overload - Những phương cùng tên nhưng lại khác nhau về: số lượng tham số hoặc kiểu tham số


Four Basic Principle of OOP 
- Encapsulation (getter setter, prevent access)
	- often use this concept to hide an object’s internal representation or state from the outside. This is called [information hiding](https://en.wikipedia.org/wiki/Encapsulation_(computer_programming)#An_information-hiding_mechanism).
- Data Abstraction 
	- Getter
	- Hide insignificant details
	- Force sub'objects' to re-define functions
- Inheritance (command: "extends")
	- To make sub-class
	- Carries the same properties and attribute
- Polymophism (có thể thực hiện nhiều cách khác nhau)
	

 Object & Class - Object là real entity - Class là template của object - Class là định nghĩa của object 
  - Constructor - Hàm khởi tạo, mục đích là khởi tạo những thuộc tính ban đầu của object - Được gọi qua từ khóa new - Tất cả các class đều có ít nhất 1 constructor - Nếu class không có constructor thì mặc định đã có một constructor không có tham số 
  - Constructor có 2 loại: Có tham số, không tham số 
  
### Overide & Overload:
Overide: overide other function with same name (inheratant)
Overload: run function with different amount or type of properties