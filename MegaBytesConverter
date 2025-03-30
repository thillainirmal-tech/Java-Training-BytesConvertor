public class MegaBytesConverter {
 
    public static void printMegaBytesAndKiloBytes(int kiloBytes) {
        if (kiloBytes < 0) {
            System.out.println("Invalid Value");
            return;
        }
        
        int mb = kiloBytes / 1024;
        int remainingKB = kiloBytes % 1024;
        System.out.println(kiloBytes + " KB = " + mb + " MB and " + remainingKB + " KB");
    }

    public static void main(String[] args) {
        // Test cases
        printMegaBytesAndKiloBytes(2500);   // Output: 2500 KB = 2 MB and 452 KB
        printMegaBytesAndKiloBytes(-1024);  // Output: Invalid Value
        printMegaBytesAndKiloBytes(5000);   // Output: 5000 KB = 4 MB and 872 KB
        printMegaBytesAndKiloBytes(0);      // Output: 0 KB = 0 MB and 0 KB
    }
}
