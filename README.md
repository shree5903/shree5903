- š Hi, Iām @shree5903
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
shree5903/shree5903 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
class GfG
{
	public static int palinArray(int[] a, int n)
           {
                 StringBuffer sb = new StringBuffer();
                 String s;
                 String k;
                 int count =0;
                 for(int i =0; i <a.length; i++)
                 {
                     s = String.valueOf(a[i]);
                     sb.append(s);
                     k = sb.reverse().toString();
                     if(s.equals(k))
                     {
                         sb.delete(0,sb.length());
                         count++;
                         continue;
                     }
                     else{
                         break;
                     }
                 }
                                  if(count == a.length){return 1;}
                                  else{return 0;
           }
}
}
