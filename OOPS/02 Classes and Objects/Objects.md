# Object

## Objects are instances of class. When a class is defined, no memeory is allocated. But wheen it is instanciated, memory is allocated. 


``` cpp
class geek
{
public:


    string geekname;
    void printF() { cout << "Geekname is :" << geekname; };
}

int main()
{
    geek obj1;    // obj1 is an object that is used as an instance of class geek.

    obj1.geekname = "Parth";
    obj1.printF();
    return 0;
}