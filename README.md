# Comp-9.7

public class Ipad extends ElectronicEquipment{
    public void message()
{
    System.out.println("Attributes of iPad: ");
    System.out.println();
    super.message(); 
    super.namesOfManufacturers("Apple"); //calls superclass methods
    super.findWeight(2);
    super.findCost(799);
    super.findMonthlyPowerUsage(5);
    super.findColor("Space Gray");
    }

}
