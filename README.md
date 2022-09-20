# AssessmentS20
package Animal;

public abstract class Pet {
    private String name;

    public Pet(String name) {
        this.name = name;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    @Override
    public String toString() {
        return "Pet{" +
                "name='" + name + '\'' +
                '}';
    }

    public abstract void printProductName();


}package Animal;

public abstract class Feline extends Pet {
    public Feline(String name) {
        super(name);
    }


}package Animal;

public class Dog extends Pet {


    public Dog(String name) {
        super(name);
    }

    @Override
    public void printProductName() {

    }


}
}
