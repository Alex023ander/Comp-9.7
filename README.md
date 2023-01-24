# Comp-9.7

public class Macbook extends ElectronicEquipment{
    public void message()
{
    System.out.println("Attributes of Macbook: ");
    System.out.println();
    super.message(); // explicitly invokes the parent's version
    super.namesOfManufacturers("Apple"); //calls superclass methods
    super.findWeight(3);
    super.findCost(1799);
    super.findMonthlyPowerUsage(20);
    super.findColor("Space Gray");
    }

}
