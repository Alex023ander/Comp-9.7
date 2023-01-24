# Comp-9.7

public class iphone extends ElectronicEquipment{
    public void message()
{
    System.out.println("Attributes of iPhone: ");
    System.out.println();
    super.message(); // explicitly invokes the parent's version
    super.namesOfManufacturers("Apple"); //calls superclass methods
    super.findWeight(1);
    super.findCost(999);
    super.findMonthlyPowerUsage(3);
    super.findColor("Silver");
    }
    
}
