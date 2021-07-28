class Fibonacci
{
public static void main(String[] args)
{
Scanner scn = new Scanner(System.in)
int n = scn.nextInt()
int n1=0,n2=1;
for(int i=0;i<n;i++)
{
System.out.println(n1);
int c = n1+n2;
n1=n2;
n2=c;
}

}
}
