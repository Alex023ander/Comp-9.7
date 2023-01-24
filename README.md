# Comp-9.7

public void message() //defines message method, prints message for every subclass

    {
        System.out.println("WARNING: Excessive use may cause strain to eyes "
            + "and produce headaches!");
    }

    public void namesOfManufacturers(String manufacturers) //method definition
    {
        System.out.println("Names of Manufacturers: " + manufacturers);
    }

    public void findWeight(int weight)
    {
        System.out.println("Weight: " + weight + " pounds");
    }

    public void findCost(int cost)
    {
        System.out.println("Cost: $" + cost);
    }

    public void findMonthlyPowerUsage(int monthlyPowerUsage)
    {
        System.out.println("Monthly Power Usage: " + monthlyPowerUsage);
    }

    public void findColor(String color)
    {
        System.out.println("Color: " + color); //formats ouput
        System.out.println("");
        System.out.println("*");
        System.out.println("");
    }
}
