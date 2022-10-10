# java-ArrayList-iterate
iterate through the elements in the ArrayList


package personal;

import java.util.ArrayList;

public class JavaUtilArrayList {
	public static void main(String[] args) {
		
		    // create an ArrayList
		    ArrayList<String> animals = new ArrayList<>();
		    ArrayList <Integer> price = new ArrayList<>();
		    
		    //add ArrayList
		    animals.add("Cow");
		    animals.add("Cat");
		    animals.add("Dog");
		    price.add(30000);
		    price.add(10000);
		    price.add(18000);
		    
		    System.out.println("| PET HOUSE |\r");
		    System.out.println(animals);
		    System.out.println(price);

		    
		    System.out.println("\rAccessing individual pets:  ");
		    // iterate using for-each loop
		    for (String element: animals) {
		      System.out.print(element);
		      System.out.print(", "); 
		    }for (Integer petsPrice: price) {
		    	System.out.print(" \rPhp " + petsPrice);
		    	
		    }
	}
}
