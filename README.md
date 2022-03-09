package aaaaaa;

public class StringRev {
	public static void main(String args[])
	{
		        String str = "google";
		        String RevString = "";
		        for(int i=str.length()-1;i>=0;i--)
		        {
		          RevString += str.charAt(i);
		        }
		        System.out.println(RevString);
   }
		
	}


