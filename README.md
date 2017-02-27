# stringCount
public class stringcount
{
    public static void main (String arg[])
    {
        String string = ("Java apple cake");
        int count = 0;
        for (int i=0; i < string.length(); i++){
            if (string.charAt(i) =='a'){
                count++;
            }
        }
        System.out.println(count);
    }
}
