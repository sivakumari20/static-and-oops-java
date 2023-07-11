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


import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    System.out.println("choose the animal");
	    System.out.println("1-dog 2-cat");
	    int choice=sc.nextInt();
	    if (choice==1)
	    {
	        dog doggy =new dog();
	         doggy.speak("siva");
	    }
	    else if(choice==2)
	    {
	        cat catty =new cat();
	        catty.speak("vasu");
	    }
	    else
	    {
	         animal anim=new animal();
	         anim.speak("shannu");
	   
	    
	    }
	   
	    
	    
	    
	}
}

public class animal
{
    public void speak(String name)
    {
        System.out.println( name +"animal sounds brooo");
    }
}

public class animal
{
    public void speak(String name)
    {
        System.out.println( name +"animal sounds brooo");
    }
}

public class cat extends animal {
    public void speak(String name)
    {
        System.out.println(name +"cat amkes meow meow");
    }
}

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    
	  try{
	    Scanner sc=new Scanner(System.in);
	    System.out.println("enter value of a");
	    int a=sc.nextInt();
	    System.out.println("enter value of b");
	    int b=sc.nextInt();
	    int  c=a/b;
	    System.out.println(c);
	  
	   
	}
	    
	    catch(ArithmeticException e)    //EXCEPTION HANDLING
	   {
	       System.out.println("enter correct value stupid");
	    }
	    catch(RuntimeException e)
	   {
	       System.out.println("enter correct type stupid");
	    }
	    finally{
	       System.out.println(" still enter appropriate value");
	   }
	   
	    
	    
	    
	}
}


import java.util.Scanner;
import java.io.File;
public class Main
{
	public static void main(String[] args) {
	    
	    File file =new File("SIVA CARR.txt");
	    if (file.exists()){
	        System.out.println("the file exists");
	    }
	    else{
	            System.out.println("that file does not exist");
	        }
	        }
	    }

     import java.util.Scanner;
import java.io.File;
public class Main
{
	public static void main(String[] args) {  //PROGRAM TO CHECK WHETHER A FILE E XISTS OR NOT
	    
	    File file =new File("C:/Users/91833/Desktop/SIVA CARR.txt");
	    if (file.exists()){
	        System.out.println("the file exists");
	    }
	    else{
	            System.out.println("that file does not exist");
	        }
	        }
	    }
	    
	  
	  
	    import java.util.Scanner;
import java.io.File;
public class Main                             // outputs path of the file
{
	public static void main(String[] args) {
	    
	    File file =new File("C:/Users/91833/Desktop/SIVA CARR.txt");
	    if (file.exists()){
	        System.out.println("the file exists");
	        System.out.println(file.getPath());
	        System.out.println(file.getAbsolutePath());
	    }
	    else{
	            System.out.println("that file does not exist");
	        }
	        }
	    }

     import java.util.Scanner;
import java.io.File;
public class Main
{
	public static void main(String[] args) {
	    
	    File file =new File("C:/Users/91833/Desktop/SIVA CARR.txt");
	    if (file.exists()){
	        System.out.println("the file exists");
	        System.out.println(file.getPath());
	        System.out.println(file.getAbsolutePath());
	        System.out.println(file.isFile());
	        file.delete();
	    }
	    else{
	            System.out.println("that file does not exist");
	        }
	        }
	    }
	    
	  
	  import java.util.Scanner;
import java.io.File;
import java.io.IOException;
import java.io.FileWriter;
public class Main
{                                         //writing into file or folder
	public static void main(String[] args) {
	    
	    try {
	        
	     FileWriter writer=new FileWriter("SIVA CARR.txt");
	     writer.write("roses are red");
	     writer.close();
	    }  
	    catch(IOException e){
	        e.printStackTrace();
	    }
	}
}
	    
	  
	import java.util.Scanner;
import java.io.File;
import java.io.IOException;
import java.io.FileWriter;
public class Main
{
	public static void main(String[] args) {
	    
	    try {
	        
	     FileWriter writer=new FileWriter("SIVA CARR.txt");
	     writer.write("roses are red \n violets are blue \n life is critiacal");
	     writer.append("siva an idiot");
	      writer.close();
	    }  
	    catch(IOException e){
	        e.printStackTrace();
	    }
	}
}
	    
filereader reads the contents of file as a stream of characteristics and returns an int value which returnsd the byte when read() returns -1 ,there is no more data to be read


	                 _
           H||
           H||
 __________H||___________
[|.......................|
||.........## --.#.......|
||.........   #  # ......|            @@@@
||.........     *  ......|          @@@@@@@
||........     -^........|   ,      - @@@@
||.....##\        .......|   |     '_ @@@
||....#####     /###.....|   |     __\@ \@
||....########\ \((#.....|  _\\  (/ ) @\_/)____
||..####,   ))/ ##.......|   |(__/ /     /|% #/
||..#####      '####.....|    \___/ ----/_|-*/
||..#####\____/#####.....|       ,:   '(
||...######..######......|       |:     \
||.....""""  """"...b'ger|       |:      )
[|_______________________|       |:      |
       H||_______H||             |_____,_|
       H||________\|              |   / (
       H||       H||              |  /\  )
       H||       H||              (  \| /
      _H||_______H||__            |  /'=.
    H|________________|           '=>/  \
                                 /  \ /|/
                               ,___/|

                               import java.util.Scanner;
import java.io.File;
import java.io.IOException;
import java.io.FileWriter;
import java.io.FileReader;
public class Main
{
	public static void main(String[] args) {
	    
	    try {
	     FileReader reader=new FileReader("piece.txt");
	     int data =reader.read();
	     while (data!=-1){                   //reading contents of afile 
	        
	     System.out.print((char)data);
	     data=reader.read();
	    }
	    }
	    catch(IOException e){
	        e.printStackTrace();
	    }
	   
	}
}
	   //how to create an audio player in java

    import java.util.Scanner;
import java.io.File;
import java.io.IOException;
import javax.sound.sampled.*;
import javax.sound.sampled.AudioInputStream;
import javax.sound.sampled.AudioSystem;
import javax.sound.sampled.Clip;
import javax.sound.sampled.LineUnavailableException;
import javax.sound.sampled.UnsupportedAudioFileException;
import java.io.File;
import java.io.IOException;
public class Main
{
	public static void main(String[] args) throws UnsupportedAudioFileException,IOException,LineUnavailableException{
	    Scanner sc=new Scanner(System.in);
	    
	    File file =new File("sample-3s.mp3");
	    AudioInputStream audiostream=AudioSystem.getAudioInputStream(file);
	    Clip clip=AudioSystem.getClip();
	    clip.open(audiostream);
	    
	    String response=sc.next();
	    clip.start();
	    
	    }
	   
	}

	    
	  
	  
	  
	  
	    
	  
	  
	  
	  

