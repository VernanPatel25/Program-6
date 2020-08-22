class program_6
{
    public static void main(String args[])
    {
       int rows = 4, number = 1, count, j;
       for ( count = 1 ; count <= rows ; count++ )
       {
           for ( j = 1 ; j <= count ; j++ )
           {
                System.out.print(number+" ");
                
                number++;
           }
           System.out.println();
       }
   }
}
