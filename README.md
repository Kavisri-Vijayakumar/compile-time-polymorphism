package main;


public class Main {
    public int addition(int x,int y){
        return x+y;
    }
    public int addition(int x,int y,int z){
        return x+y+z;
    }
    public double addition(double x,double y){
        return x+y;
    }

    
    public static void main(String[] args) {
        Main number=new Main();
        int res1=number.addition(777,555);
        System.out.println("addition of two numbers:"+res1);
        int res2=number.addition(333,777,555);
        System.out.println("addition of three numbers:"+res2);
        double res3=number.addition(10.15,20.22);
        System.out.println("addition of two numbers:"+res3);
    }
    
}

output
addition of two numbers:1332
addition of three numbers:1665
addition of two numbers:30.369999999999997
