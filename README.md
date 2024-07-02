# JavaCollections
Here are some codes:


import java.util.*;

public class ArrayListEx 
{
public static void main(String args[])
    {
     ArrayList<String> al = new ArrayList<String>();
     al.add("A");
al.add("B");
al.add("C");
al.add("D");
al.add(null);
al.add("D");
        System.out.println(al);
        
        ArrayList al1 = new ArrayList();
        al1.add("a");
        al1.add("b");
        al1.add("c");
        al1.add("d");
        al.addAll(2,al1);
        System.out.println(al);
        
        al.remove("d");
        al.remove(3);
        
        System.out.println(al);
        
        String s = al.get(1);
        
        System.out.println(s);
        
        int i = al.size();
        
        System.out.println("Array Size: "+i);
        
        System.out.println(al);
        
        boolean check = al.contains("a");
        
        System.out.println(check);
        
        int j = al.indexOf("a");
        
        System.out.println("Index of a :"+j);
        
        int k = al.lastIndexOf("a");
        System.out.println("Last index of a:"+k);
        
        LinkedList<String> l = new LinkedList<String>();
        
        l.add("a");
        l.add("b");
        l.add("c");
        l.add("d");
        
        System.out.println(l);
        int m = l.size();
        System.out.println("LinkedList Size: "+m);
        
        l.remove(2);
        
        System.out.println(l);
        
        l.removeFirst();
        l.removeLast();
        
        System.out.println(l);
        
        l.add("c");
        l.add("d");
        
        String c = l.get(2);
        
        System.out.println(c);
        l.set(1,"K");
        
        System.out.println(l);
    }
}
