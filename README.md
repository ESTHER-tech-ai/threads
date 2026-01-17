
Class Multi extends Thread
{
Public void run()
{
System.out.println (“thread is running…”)
}
Public static void main(String args[])
{
Multi t1=new Multi();
t1.sart();
}
}

Class Multi extends Thread
{
Public void run()
{
System.out.println (“thread is running…”)
}
Public static void main(String args[])
{
Multi t1=new Multi();
t1.sart();
}
}
Output: thread is running…

2. By implementing runnable interface

Class Multi3 implements Runnable
{
Public void run()
{
System.out.println(“thread is running…”);
}
Public static void main(String args[])
{
Multi3 m1=newMulti3();
Thread t1=new Thread(m1);
}
}
