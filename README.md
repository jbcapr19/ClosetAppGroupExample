# Closet Application

## Create an application that will allow you to pack items from your closet for a trip. 

You need to create a class that will run your program, 
and create customized classes, which would be your data types.

- ClosetApp class
- Closet class
- Jacket class
- Shirt class
- Pants class
- Footwear class

You need at least 1 jacket, 1 shirt, 1 pants and 1 footwear per trip.

You can add as many as attributes as you'd like per each class.
For example, a shirt can be made of cotton, polyester or linen.
You would express that by creating a variable called "material" in the Shirt class.

In your ClosetApp class, create 3 separate instances of your mini closets and give them unique names.
Add them to an arraylist, and allow the user to look for a specific closet based on the name,
then display the contents of that closet.


public class Shirt {
	private String material;
	
	public Shirt(){
	}
	
	public void setMaterial(String material){
		this.material = material;
	}
	
	public String getMaterial(){
		return material;
	}

}
