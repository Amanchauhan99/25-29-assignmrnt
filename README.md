# 25-29-assignmrnt

##sum of array

package myProjects;

public class Recsumarray {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		 int arr[] = {2,3,4,5,6,7};
		 int n=0;
         int sum = calculateSum(arr, arr.length);
 
          System.out.println(sum);
	}
	     private static int calculateSum(int arr[], int n) {

	         if (n <= 0) {
	            return 0;
	          }
	          return calculateSum(arr, n-1 ) + arr[n-1];
	       }

	}
