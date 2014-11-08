ArrayListFun
============
import java.util.ArrayList;


public class ArrayListFun {

	public static void main(String[] args) {

		ArrayList<Integer> list = new ArrayList<Integer> ();
		list.add(200);
		list.add(40);
		list.add(3);
		list.add(8);
		list.add(7);
		list.add(10);
		list.add(100);

		int smallest = list.get(0);

		for (int i = 0; i < list.size() ; i++) {
			if (list.get(i) < smallest) {
				smallest = list.get(i);
			}
		}

		System.out.println("Smallest: " + smallest);
		//ap test question : array list of integers: ArrayList<Integer>
	}

}
