public class MultiplesFindings {
    public static void main(String[] args) {
        int start = 71;
        int end = 150;

        System.out.println("Multiples of 2, 3, and 7 between " + start + " and " + end + ":");

        System.out.println("\nMultiples of 2:");
        for (int i = start; i <= end; i++) {
            if (i % 2 == 0) {
                System.out.print(i + " ");
            }
        }

        System.out.println("\n\nMultiples of 3:");
        for (int i = start; i <= end; i++) {
            if (i % 3 == 0) {
                System.out.print(i + " ");
            }
        }

        System.out.println("\n\nMultiples of 7:");
        for (int i = start; i <= end; i++) {
            if (i % 7 == 0) {
                System.out.print(i + " ");
            }
        }
    }
}