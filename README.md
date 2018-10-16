# BoardIntSum
package pierwszeKroki.com.pl;

import java.util.stream.IntStream;

public class BoardIntSum {

	public static void main(String[] args) {
		// Metoda, która jako jedyny argument przyjmie zmienną typu int[] i zwróci sumę wszystkich elementów tablicy;
		int[] a = {-10,-20,10,20,30};
		int sum = IntStream.of(a).sum();
		System.out.println("The sum is " + sum);
	}

}

