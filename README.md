# JAVA
第一支JAVA

public class HelloWorld{

     public static void main(String []args){
        System.out.println("Hello World");
     }
}

--

編譯
$javac HelloWorld.java

==> 會產生HelloWorld.class

--

執行
$java -Xmx128M -Xms16M HelloWorld

Hello World

--

println()和print()有何差別?

public class HelloWorld2{

     public static void main(String []args){
        System.out.print("Hello ");
	System.out.print("Mydeargreatteacher");
	System.out.println("Hello World");
     }
}

--

Hello MydeargreatteacherHello World

--

Hello MydeargreatteacherHello World
public class HelloWorld21{

     public static void main(String []args){
        System.out.print("Hello ");
	System.out.println("Mydeargreatteacher");
	System.out.println("Hello World");
     }
}

--

Hello Mydeargreatteacher
Hello World

--


