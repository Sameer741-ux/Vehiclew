class Vehicle{
    void run(){
        System.out.println("run karta haii");
    }
}
class Bike extends Vehicle{
    void run(){
        System.out.println("ye bhi chalta haii");
        super.run();
    }
}
class hello3{
    public static void main(String[] args){
        Vehicle obj= new Bike();
        obj.run();
    }
}
