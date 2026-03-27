# Student-Management-System-Java-OOP
OOP Assignment 2 - Java Student Management System
abstract class Person {
    protected String name;
    protected int id;

    public Person(String name, int id) {
        this.name = name;
        this.id = id;
    }

    
    public String getName() {
        return name;
    }

    public int getId() {
        return id;
    }


    public abstract void displayInfo();
}
