
# Input Code :
## • Data Pesawat
```
```java
public class PesawatTempur {

    private final String warna;
    }
```
## • Fungsi Untuk Menyalakan Mesin
```
```java
public void nyalakanMesin() {
        System.out.println("Mesin pesawat dinyalakan...");
    }
```
## • Fungsi Untuk Terbang
```
```java
 public void terbang() {
        if (this.kecepatan > 0) {
            if (this.energi >= 10) { 
    }
```
## • Fungsi Untuk Menambah Kecepatan
```
```java
public void tambahKecepatan(int kecepatan) {
        this.kecepatan += kecepatan;
        if (this.kecepatan > MAX_KECEPATAN) {
    }
```
## • Fungsi Untuk Mengurangi Kecepatan
```
```java
public void kurangiKecepatan(int kecepatan) {
        this.kecepatan -= kecepatan;
        if (this.kecepatan < 0) {
    }
```
## • Fungsi Untuk Belok
```
```java
public void belok(String arah) {
        this.arah = arah;
        System.out.println("Pesawat berbelok ke arah " + this.arah);
    }
```
## • Fungsi Untuk Turun
```
```java
public void turun() {
        if (this.ketinggian - 100 >= 0) {
            this.ketinggian -= 100;
    }
```
## • Fungsi Untuk Naik
```
```java
public void naik() {
        if (this.ketinggian + 100 <= MAX_KETINGGIAN) {
            this.ketinggian += 100;
    }
```
## • Fungsi Untuk Menampilkan Informasi Pesawat
```
```java
public void infoPesawat() {
        System.out.println("------------------------");
        System.out.println("Informasi Pesawat:");
```

## • Membuat Objek Pesawat
```
```java
public static void main(String[] args) {

        PesawatTempur pesawat1 = new PesawatTempur("Putih");
```

## • Menampilkan Informasi awal pesawat
```
```java
        pesawat1.infoPesawat();
```

## • Menyalakan Mesin Pesawat
```
```java
        pesawat1.nyalakanMesin(); 
```

## • Menambah Kecepatan Pesawat
```
```java
        pesawat1.tambahKecepatan(200);
```

## • Terbang
```
```java
        pesawat1.terbang();
```

## • Belok Ke Arah Barat
```
```java
        pesawat1.belok("Barat");
```

## • Menambah Kecepatan Lagi
```
```java
        pesawat1.tambahKecepatan(100);
```

## • Menampilkan Informasi Pesawat
```
```java
        pesawat1.infoPesawat();
```

## • Mengurangi Kecepatan
```
```java
        pesawat1.kurangiKecepatan(50);
```

## • Turun
```
```java
        pesawat1.turun();
```

## • Naik
```
```java
        pesawat1.naik();
```

## • Menampilkan Informasi Pesawat
```
```java
        pesawat1.infoPesawat();
    }
}
