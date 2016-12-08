# Assignment9.2
package collectionsdemos;

import java.util.HashSet;
import java.util.Iterator;

public class Assignement92 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		String  stringOne = new String("ramesh");
		String  stringTwo = new String("Kumar");
		String  stringThree = new String("Satheesh"); 
		String  stringFour = new String("Kumar");
		String  stringFive  = new String("manju");

		HashSet<String> hashset = new HashSet<String>();
		hashset.add(stringOne);
		hashset.add(stringTwo);
		hashset.add(stringThree);
		hashset.add(stringFour);
		hashset.add(stringFive);

		System.out.println(hashset);

		System.out.println("*********************************************************************************************");
		Iterator iterator = hashset.iterator();
		while(iterator.hasNext()){
			String str = (String) iterator.next();
			System.out.println(str);
	}

}
}
