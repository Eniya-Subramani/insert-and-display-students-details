# insert-and-display-students-details
Class Student {
int rollno;
String name;
void insertRecord(int r, String n) {
rollno = r;
name = n;
}
void displayInformation() {
System.out.println(rollno + &quot; &quot; + name);
}
}
Public class TestStudent4 {
Public static void main(String[] args) {
Student student1 = new Student();
Student student2 = new Student();

student1.insertRecord(1, &quot;Karan&quot;);
student2.insertRecord(222, &quot;Aryan&quot;);
student1.displayInformation();
student2.displayInformation();
}
}
OUTPUT:
1 Karan
222 Aryan
