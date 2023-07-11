# static-and-oops-java

public class Main{
    public static void main(String [] args){            //static keyword usage
        friend friend1=new friend("siva");
        friend friend2=new friend("shannu");
        friend friend3=new friend("madhavi");
    System.out.println(friend1.noof);
    }
}

public class friend{
    static int noof;
    String name;
    friend(String name)
    {
        this.name=name;
        noof++;
    }
}
