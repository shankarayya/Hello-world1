# Hello-world1

class Mythread extends Thread
{
    public void run()
    {
      System.out.println("Child class varibale");
    }
}
class ThreadDemo
{
  public static void main(String...args)
  {
    MyThreaddemo t=new MyThreadDemo();
    t.start();
    for(int i=0; i<10; i++)
    {
      System.out.println("Main class Thread");   
    }
   }
}
