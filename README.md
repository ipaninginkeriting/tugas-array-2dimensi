public class JadwalSederhana {
    public static void main(String[] args) {
        String[][] jadwal = {
            {"Matematika", "Bahasa Indonesia", "IPA"},      // Senin
            {"Bahasa Inggris", "Agama", "PJOK"},             // Selasa
            {"IPS", "Seni", "TIK"}                           // Rabu
        };

        String[] hari = {"Senin", "Selasa", "Rabu"};

        for (int i = 0; i < jadwal.length; i++) {
            System.out.println("Jadwal " + hari[i] + ":");
            for (int j = 0; j < jadwal[i].length; j++) {
                System.out.println("  Jam ke-" + (j + 1) + ": " + jadwal[i][j]);
            }
            System.out.println(); // Spasi antar hari
        }
    }
}
