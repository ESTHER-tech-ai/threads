
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
