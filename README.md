# 🟢 Program Menghitung Luas Lingkaran

Program ini dibuat menggunakan bahasa *Java* untuk menghitung *luas lingkaran* berdasarkan *input jari-jari* yang dimasukkan oleh pengguna.

---

## 📘 Deskripsi

Program akan meminta pengguna untuk memasukkan nilai jari-jari lingkaran, kemudian menghitung luas menggunakan rumus:

\[
\text{Luas} = \pi \times r^2
\]

Hasil perhitungan kemudian ditampilkan di layar.

---

## 🧩 Kode Program

```java
import java.util.Scanner;

public class LuasLingkaran {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Masukkan jari-jari lingkaran: ");
        double jariJari = input.nextDouble();

        double luas = Math.PI * jariJari * jariJari;

        System.out.println("Luas lingkaran dengan jari-jari " + jariJari + " adalah " + luas);

        input.close();
    }
}