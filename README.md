# Java_Snippets

### basic structure

file extention:

    .java
      
basic class structure:
     
     public class ClassName {
       // method
     }
       
basic method structure(main):
    
        public static void method(String[] args){
          // instructions
        }
        
#### commenting code: 

  single line:
  
      //
      
  several lines:
  
        /*
       Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et 
       dolore magna aliqua. Venenatis tellus in metus vulputate eu scelerisque felis. Nam libero justo laoreet 
       sit amet. Sit amet consectetur adipiscing elit. Nisl rhoncus mattis rhoncus urna neque viverra justo nec.
       */
           
#### example:

    public class HelloWorld{
      public static void main(String[] args){
        System.out.println("HelloWorld!")
      }
    }
   
### Running a program

Compiling(Produces a .class file):

    $ javac FileName.java
        
Executing: 

    $ java FileName
  
