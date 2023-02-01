# fd
public static void main(String[] args) {
		// TODO Auto-generated method stub
         
		int n=177;
		int res;
		int count=0;
	
	// Counting the factors of a number
		
		for(int i=1;i<=n;i++) 
		{
		    	res=n%i;
		    	if(res==0)
			{
			// System.out.println(j);
				count++;
			}
			
		}
	// With counting 
	//	System.out.println(count);
		if(count>2)
		{
			System.out.println(n+" is not a prime number");
		}
		else
		{
			System.out.println(n+" is a prime number");
		
		}
		
	}
