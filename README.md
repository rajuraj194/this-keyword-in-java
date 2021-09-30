# this-keyword-in-java

Can Anyone give one example for "this" keyword?

this is one of the java keywords and it helps in referring to the current object. When we use the dot(.) operator on this keyword, then we can access the member variables of the current object. this keyword can also be used to call one constructor from another constructors of the same class.

The parameter names passed to the constructors can have the same name as the member variables of that class.
Example 
class Student
{
    String name;
    int marks;
    char section;

    Student(String nameParam, int marksParam, char sectionParam)
    {
        name = nameParam;
        marks = marksParam;
        section = sectionParam;
    }
} 
can be rewritten as

Student(String name, int marks, char section)
{
    this.name = name;
    this.marks = marks;
    this.section = section;
}
