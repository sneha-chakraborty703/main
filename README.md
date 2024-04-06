class mythread extends Thread
{
    public void run() {
        for (int i = 1; i <= 5; i++) {
            System.out.println("Sneha");
            try {
                sleep(1000);
            } catch (Exception e) {
            }
            System.out.println("Chakraborty");
            try {
                sleep(1000);
            } catch (Exception e) {

            }
        }
    }

}
class test{
    public static void main(String ar[])
    {
        mythread ob=new mythread();
        ob.start();
    }
}
