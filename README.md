public class MyClass {
    public static void main(String[] args) {
        double sizeAmount = 25;
        if (sizeAmount % 2 == 0){
            double angleSize = (1-2 / sizeAmount) * 180;
            System.out.println("The angle size in the polygon is " + angleSize + " degrees.");
        }
        else{
            double areaSize = Math.sqrt(15) * sizeAmount / 4 * Math.tan(180 / sizeAmount);
            System.out.println("The polygon's area's size is " + areaSize + " square meters.");
        }
    }
}
