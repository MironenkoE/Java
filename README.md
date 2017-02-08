
package replacsCat;

public class NewCat {
    public static String cat;
    public static String whale = "кит";
    public static void replaceWord(){
        cat = whale.replace("и","о");
        System.out.println("It was '"+whale+"' and became '"+cat+"'");
    }
    public static void show(){
        System.out.print("*********************************************\n\n");
        System.out.println("Используя метод replace зделать из кита – кота.\n");
        System.out.print("*********************************************\n\n");

    }
    public static void main(String[] args) {
show();
replaceWord();
    }
}
