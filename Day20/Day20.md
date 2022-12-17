## Day 20

**access specifiers:**
- public
- private
- protected

**when to use base()?**
- base is used when there is no default constructor 
- The constructor of a base class used to instantiate the objects of the base class

```
namespace Inheritance
{
    public class Program
    {
        Static void main(String[] args)
        {
            Animal a1 = new Animal();
        }
    }
    public class LivingThings
    {
        protected string Name;
        public LivingThings(string name)
        {
            Name = name;
        }
    }
    public class Animal : LivingThings
    {
        public Animal() : base("Default")
        {
            Name = "Animal";
        }
        public Animal(string name) : base(name)
        {
            Name = name;
        }
    }
}
```

### here are notes:
![Images](https://github.com/realtirtha/100DaysOfCode-ProgressTracker/blob/main/images/20a.jpg)