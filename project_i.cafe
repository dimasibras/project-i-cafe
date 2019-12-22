#include <iostream>
#include <string.h>
#include <conio.h>
#include <windows.h>
#include <fstream>
void judul();
void login();
void menutama();
void mainmenu();
void petunjuk();
void kodepc ();
void kodepc1 ();
void kodepc2 ();
void kodepc3 ();
void kodepc4 ();
void kodepc5 ();
void kodepc6 ();
void pc1 ();
void pc2 ();
void pc3 ();
void pc4 ();
void pc5 ();
void pc6 ();
void pesanan ();
void daftar ();
void garis1();
void exit();
using namespace std;
char nama1[128], nama2[128], nama3[128], nama4[128], nama5[128];
int kodepaket1=0, kodepaket2=0, kodepaket3=0, kodepaket4=0, kodepaket5=0;
int makanan1=0, makanan2=0, makanan3=0, makanan4=0, makanan5=0;
int minuman1=0, minuman2=0, minuman3=0, minuman4=0, minuman5=0;
string kp1, kp2, kp3, kp4, kp5;
string m1, m2, m3, m4, m5;
string n1, n2, n3, n4, n5;

int main ()
{
    system("color 71");
    for (int i=0;i<=100;i++)
{
    cout<<endl<<"Loading..."<<i<<"%"<<endl;
    system("cls");

}
cout<<"LOADING COMPLETE"<<endl;
Sleep(3000);
system("cls");
    login();
}
void login(){
    system("cls");
    system("color 71");
    string q1;
    string q2;
    judul();
    cout << "       Username : ";
    cin >> q1;
    cout << "       Password : ";
    cin >> q2;
    if (q1=="admin" && q2=="admin") {
        Sleep(3000);
        menutama();
    } else
    {
        cout << "       Maaf data yang anda input salah, silahkan coba lagi." << endl;
        Sleep(3000);
        return login();
    }
    }
void menutama(){
    system("cls");
    system("color 71");
   int kode;
    Data:
    system("cls");
    judul() ;
        cout << "\n                   MENU UTAMA" << endl;
        cout << "                   1. Aktivasi Paket Internet" << endl;
        cout << "                   2. Daftar Komputer yang Aktif" << endl;
        cout << "                   3. Petunjuk Penggunaan" << endl;
        cout << "                   0. Keluar\n" << endl;
        cout << "           Masukkan Pilihan Anda : ";
        cin >> kode;
        cout << "\n\n" << endl;
    switch (kode)
    {
    case 1 :
     system("cls");
     judul();
     kodepc();
     goto Data;
     break;
    case 2 :
     system("cls");
     judul();
     daftar();
     goto Data;
     break;
    case 3 :
     system("cls");
     judul();
     petunjuk();
     goto Data;
     break;
    case 0 :
     exit();
    }
}
void exit(){
    exit(0);}
void kodepc (){
    system("cls");
    system("color 71");
   int kodekom;
    Data:
    system("cls");
    judul() ;
        cout << "\n                   Pilih Unit PC Yang Diinginkan" << endl;
        cout << "                   1. PC 1" << endl;
        cout << "                   2. PC 2" << endl;
        cout << "                   3. PC 3" << endl;
        cout << "                   4. PC 4" << endl;
        cout << "                   5. PC 5" << endl;
        cout << "                   0. Kembali" << endl;
        cout << "           Masukkan Pilihan Anda : ";
        cin >> kodekom;
        cout << "\n\n" << endl;
    switch (kodekom)
    {
    case 1 :
     system("cls");
     judul();
     kodepc1();
     goto Data;
     break;
    case 2 :
     system("cls");
     judul();
     kodepc2();
     goto Data;
     break;
     case 3 :
     system("cls");
     judul();
     kodepc3();
     goto Data;
     break;
    case 4 :
     system("cls");
     judul();
     kodepc4();
     goto Data;
     break;
     case 5 :
     system("cls");
     judul();
     kodepc5();
     goto Data;
     break;
     case 0 :
     menutama();
    }
}
void kodepc1(){
    system("cls");
    system("color 71");
    judul();
    cout << "Data Pelanggan Paket Unit PC 1" << endl;
    cout << "\n" << endl;
    cout << "NPM Pengguna               : ";
    cin >> nama1;
    cout << "Durasi Paket : " << endl;
    cout << "1. 1 Jam" << endl;
    cout << "2. 2 Jam" << endl;
    cout << "3. 3 Jam" << endl;
    cin >> kodepaket1;
    if(kodepaket1 == 1) {
        kp1 = "1 Jam";
    } else if (kodepaket1 == 2) {
        kp1 = "2 Jam";
    } else if (kodepaket1 == 3) {
        kp1 = "3 Jam";
    }
    cout << "Pesan Makanan              : " << endl;
    cout << "1. Indomie Goreng Original" << endl;
    cout << "2. Indomie Kari Ayam" << endl;
    cout << "3. Nasi Goreng" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> makanan1;
    if(makanan1 == 1) {
        m1 = "Indomie Goreng Original";
    } else if (makanan1 == 2) {
        m1 = "Indomie Kari Ayam";
    } else if (makanan1 == 3) {
        m1 = "Nasi Goreng";
    } else if (makanan1 == 0) {
        m1 = "Tidak Pesan";
    }
    cout << "Pesan Minuman              : " << endl;
    cout << "1. Air Mineral Dingin" << endl;
    cout << "2. Teh Manis Dingin" << endl;
    cout << "3. Cappuchino Dingin" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> minuman1;
    if(minuman1 == 1) {
        n1 = "Air Mineral Dingin";
    } else if (makanan1 == 2) {
        n1 = "Teh Manis Dingin";
    } else if (makanan1 == 3) {
        n1 = "Cappuchino Dingin";
    } else if (minuman1 == 0) {
        n1 = "Tidak Pesan";
    }
    cout << "\n\n\n";
    {
    int konfirmasi;
    judul();
      cout << "Berikut Data Pelanggan Paket Unit PC 1 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama1 << endl;
      cout << " Durasi Paket       : " << kp1 << endl;
      cout << " Pesan Makanan      : " << m1 << endl;
      cout << " Pesan Minuman      : " << n1 << endl;
      cout << "\n\n";
       garis1();
       cout <<" Paket Telah Diaktifkan " <<endl;
       garis1();
       Sleep(5000);
       return menutama();
       getch();
}}
void kodepc2(){
    system("cls");
    system("color 71");
    judul();
    cout << "Data Pelanggan Paket Unit PC 1" << endl;
    cout << "\n" << endl;
    cout << "NPM Pengguna               : ";
    cin >> nama2;
    cout << "Durasi Paket : " << endl;
    cout << "1. 1 Jam" << endl;
    cout << "2. 2 Jam" << endl;
    cout << "3. 3 Jam" << endl;
    cin >> kodepaket2;
    if(kodepaket2 == 1) {
        kp2 = "1 Jam";
    } else if (kodepaket2 == 2) {
        kp2 = "2 Jam";
    } else if (kodepaket2 == 3) {
        kp2 = "3 Jam";
    }
    cout << "Pesan Makanan              : " << endl;
    cout << "1. Indomie Goreng Original" << endl;
    cout << "2. Indomie Kari Ayam" << endl;
    cout << "3. Nasi Goreng" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> makanan2;
    if(makanan2 == 1) {
        m2 = "Indomie Goreng Original";
    } else if (makanan2 == 2) {
        m2 = "Indomie Kari Ayam";
    } else if (makanan2 == 3) {
        m2 = "Nasi Goreng";
    } else if (makanan2 == 0) {
        m2 = "Tidak Pesan";
    }
    cout << "Pesan Minuman              : " << endl;
    cout << "1. Air Mineral Dingin" << endl;
    cout << "2. Teh Manis Dingin" << endl;
    cout << "3. Cappuchino Dingin" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> minuman2;
    if(minuman2 == 1) {
        n2 = "Air Mineral Dingin";
    } else if (minuman2 == 2) {
        n2 = "Teh Manis Dingin";
    } else if (minuman2 == 3) {
        n2 = "Cappuchino Dingin";
    } else if (minuman2 == 0) {
        n2 = "Tidak Pesan";
    }
    cout << "\n\n\n";
    {
    int konfirmasi;
    judul();
      cout << "Berikut Data Pelanggan Paket Unit PC 2 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama2 << endl;
      cout << " Durasi Paket       : " << kp2 << endl;
      cout << " Pesan Makanan      : " << m2 << endl;
      cout << " Pesan Minuman      : " << n2 << endl;
      cout << "\n\n";
       garis1();
       cout <<" Paket Telah Diaktifkan " <<endl;
       garis1();
       Sleep(5000);
       return menutama();
       getch();
}}
void kodepc3(){
    system("cls");
    system("color 71");
    judul();
    cout << "Data Pelanggan Paket Unit PC 3" << endl;
    cout << "\n" << endl;
    cout << "NPM Pengguna               : ";
    cin >> nama3;
    cout << "Durasi Paket : " << endl;
    cout << "1. 1 Jam" << endl;
    cout << "2. 2 Jam" << endl;
    cout << "3. 3 Jam" << endl;
    cin >> kodepaket3;
    if(kodepaket3 == 1) {
        kp3 = "1 Jam";
    } else if (kodepaket3 == 2) {
        kp3 = "2 Jam";
    } else if (kodepaket3 == 3) {
        kp3 = "3 Jam";
    }
    cout << "Pesan Makanan              : " << endl;
    cout << "1. Indomie Goreng Original" << endl;
    cout << "2. Indomie Kari Ayam" << endl;
    cout << "3. Nasi Goreng" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> makanan3;
    if(makanan3 == 1) {
        m3 = "Indomie Goreng Original";
    } else if (makanan3 == 2) {
        m3 = "Indomie Kari Ayam";
    } else if (makanan3 == 3) {
        m3 = "Nasi Goreng";
    } else if (makanan3 == 0) {
        m3 = "Tidak Pesan";
    }
    cout << "Pesan Minuman              : " << endl;
    cout << "1. Air Mineral Dingin" << endl;
    cout << "2. Teh Manis Dingin" << endl;
    cout << "3. Cappuchino Dingin" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> minuman3;
    if(minuman3 == 1) {
        n3 = "Air Mineral Dingin";
    } else if (minuman3 == 2) {
        n3 = "Teh Manis Dingin";
    } else if (minuman3 == 3) {
        n3 = "Cappuchino Dingin";
    } else if (minuman3 == 0) {
        n3 = "Tidak Pesan";
    }
    cout << "\n\n\n";
    {
    int konfirmasi;
    judul();
      cout << "Berikut Data Pelanggan Paket Unit PC 3 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama3 << endl;
      cout << " Durasi Paket       : " << kp3 << endl;
      cout << " Pesan Makanan      : " << m3 << endl;
      cout << " Pesan Minuman      : " << n3 << endl;
      cout << "\n\n";
       garis1();
       cout <<" Paket Telah Diaktifkan " <<endl;
       garis1();
       Sleep(5000);
       return menutama();
       getch();
}}
void kodepc4(){
    system("cls");
    system("color 71");
    judul();
    cout << "Data Pelanggan Paket Unit PC 4" << endl;
    cout << "\n" << endl;
    cout << "NPM Pengguna               : ";
    cin >> nama4;
    cout << "Durasi Paket : " << endl;
    cout << "1. 1 Jam" << endl;
    cout << "2. 2 Jam" << endl;
    cout << "3. 3 Jam" << endl;
    cin >> kodepaket4;
    if(kodepaket4 == 1) {
        kp4 = "1 Jam";
    } else if (kodepaket4 == 2) {
        kp4 = "2 Jam";
    } else if (kodepaket4 == 3) {
        kp4 = "3 Jam";
    }
    cout << "Pesan Makanan              : " << endl;
    cout << "1. Indomie Goreng Original" << endl;
    cout << "2. Indomie Kari Ayam" << endl;
    cout << "3. Nasi Goreng" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> makanan4;
    if(makanan4 == 1) {
        m4 = "Indomie Goreng Original";
    } else if (makanan4 == 2) {
        m4 = "Indomie Kari Ayam";
    } else if (makanan4 == 3) {
        m4 = "Nasi Goreng";
    } else if (makanan4 == 0) {
        m4 = "Tidak Pesan";
    }
    cout << "Pesan Minuman              : " << endl;
    cout << "1. Air Mineral Dingin" << endl;
    cout << "2. Teh Manis Dingin" << endl;
    cout << "3. Cappuchino Dingin" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> minuman4;
    if(minuman4 == 1) {
        n4 = "Air Mineral Dingin";
    } else if (minuman4 == 2) {
        n4 = "Teh Manis Dingin";
    } else if (minuman4 == 3) {
        n4 = "Cappuchino Dingin";
    } else if (minuman4 == 0) {
        n4 = "Tidak Pesan";
    }
    cout << "\n\n\n";
    {
    int konfirmasi;
    judul();
      cout << "Berikut Data Pelanggan Paket Unit PC 4 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama4 << endl;
      cout << " Durasi Paket       : " << kp4 << endl;
      cout << " Pesan Makanan      : " << m4 << endl;
      cout << " Pesan Minuman      : " << n4 << endl;
      cout << "\n\n";
       garis1();
       cout <<" Paket Telah Diaktifkan " <<endl;
       garis1();
       Sleep(5000);
       return menutama();
       getch();
}}
void kodepc5(){
    system("cls");
    system("color 71");
    judul();
    cout << "Data Pelanggan Paket Unit PC 5" << endl;
    cout << "\n" << endl;
    cout << "NPM Pengguna               : ";
    cin >> nama5;
    cout << "Durasi Paket : " << endl;
    cout << "1. 1 Jam" << endl;
    cout << "2. 2 Jam" << endl;
    cout << "3. 3 Jam" << endl;
    cin >> kodepaket5;
    if(kodepaket5 == 1) {
        kp5 = "1 Jam";
    } else if (kodepaket5 == 2) {
        kp5 = "2 Jam";
    } else if (kodepaket5 == 3) {
        kp5 = "3 Jam";
    }
    cout << "Pesan Makanan              : " << endl;
    cout << "1. Indomie Goreng Original" << endl;
    cout << "2. Indomie Kari Ayam" << endl;
    cout << "3. Nasi Goreng" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> makanan5;
    if(makanan5 == 1) {
        m5 = "Indomie Goreng Original";
    } else if (makanan5 == 2) {
        m5 = "Indomie Kari Ayam";
    } else if (makanan5 == 3) {
        m5 = "Nasi Goreng";
    } else if (makanan5 == 0) {
        m5 = "Tidak Pesan";
    }
    cout << "Pesan Minuman              : " << endl;
    cout << "1. Air Mineral Dingin" << endl;
    cout << "2. Teh Manis Dingin" << endl;
    cout << "3. Cappuchino Dingin" << endl;
    cout << "0. Tidak Pesan" << endl;
    cin >> minuman5;
    if(minuman5 == 1) {
        n5 = "Air Mineral Dingin";
    } else if (minuman5 == 2) {
        n5 = "Teh Manis Dingin";
    } else if (minuman5 == 3) {
        n5 = "Cappuchino Dingin";
    } else if (minuman5 == 0) {
        n5 = "Tidak Pesan";
    }
    cout << "\n\n\n";
    {
    int konfirmasi;
    judul();
      cout << "Berikut Data Pelanggan Paket Unit PC 5 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama5 << endl;
      cout << " Durasi Paket       : " << kp5 << endl;
      cout << " Pesan Makanan      : " << m5 << endl;
      cout << " Pesan Minuman      : " << n5 << endl;
      cout << "\n\n";
       garis1();
       cout <<" Paket Telah Diaktifkan " <<endl;
       garis1();
       Sleep(5000);
       return menutama();
       getch();
}}
void daftar(){
system("cls");
    system("color 71");
   int kodekom;
    Data:
    system("cls");
    judul() ;
        cout << "\n                   List Unit PC iCafe FASILKOM" << endl;
        cout << "                   1. PC 1" << endl;
        cout << "                   2. PC 2" << endl;
        cout << "                   3. PC 3" << endl;
        cout << "                   4. PC 4" << endl;
        cout << "                   5. PC 5" << endl;
        cout << "                   0. Kembali" << endl;
        cout << "           Masukkan Pilihan Anda : ";
        cin >> kodekom;
        cout << "\n\n" << endl;
    switch (kodekom)
    {
    case 1 :
     system("cls");
     judul();
     pc1();
     goto Data;
     break;
    case 2 :
     system("cls");
     judul();
     pc2();
     goto Data;
     break;
     case 3 :
     system("cls");
     judul();
     pc3();
     goto Data;
     break;
    case 4 :
     system("cls");
     judul();
     pc4();
     goto Data;
     break;
     case 5 :
     system("cls");
     judul();
     pc5();
     goto Data;
     break;
    case 0 :
     menutama();
    }
}
void pc1 (){
      cout << "Berikut Data Pelanggan Paket Unit PC 1 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama1 << endl;
      cout << " Durasi Paket       : " << kp1 << endl;
      cout << " Pesan Makanan      : " << m1 << endl;
      cout << " Pesan Minuman      : " << n1 << endl;
      Sleep(6000);
       return menutama();
       getch();
    }
void pc2 (){
      cout << "Berikut Data Pelanggan Paket Unit PC 2 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama2 << endl;
      cout << " Durasi Paket       : " << kp2 << endl;
      cout << " Pesan Makanan      : " << m2 << endl;
      cout << " Pesan Minuman      : " << n2 << endl;
      Sleep(6000);
       return menutama();
       getch();
    }
void pc3 (){
      cout << "Berikut Data Pelanggan Paket Unit PC 3 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama3 << endl;
      cout << " Durasi Paket       : " << kp3 << endl;
      cout << " Pesan Makanan      : " << m3 << endl;
      cout << " Pesan Minuman      : " << n3 << endl;
      Sleep(6000);
       return menutama();
       getch();
    }
void pc4 (){
      cout << "Berikut Data Pelanggan Paket Unit PC 4 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama4 << endl;
      cout << " Durasi Paket       : " << kp4 << endl;
      cout << " Pesan Makanan      : " << m4 << endl;
      cout << " Pesan Minuman      : " << n4 << endl;
      Sleep(6000);
       return menutama();
       getch();
    }
void pc5 (){
      cout << "Berikut Data Pelanggan Paket Unit PC 5 : " << endl;
      cout << "\n";
      cout << " NPM Pengguna       : " << nama5 << endl;
      cout << " Durasi Paket       : " << kp5 << endl;
      cout << " Pesan Makanan      : " << m5 << endl;
      cout << " Pesan Minuman      : " << n5 << endl;
      Sleep(6000);
       return menutama();
       getch();
    }
void petunjuk()
{
    cout << "                        PETUNUJUK PENGGUNAAN APLIKASI                                      " << endl;
    cout << " " <<endl;
    cout << "1. Aplikasi ini ditujukan untuk membantu operator mendaftarkan data dan pesanan" << endl;
    cout << "   pelanggan iCafe yang ingin menggunakan layanan dengan memesan kode unit PC. " << endl;
    cout << "2. Ketik pilihan angka (bukan huruf) sesuai dengan menu yang ingin anda pilih. " << endl;
    cout << "3. Saat mengisi data pelanggan, mohon jangan menggunakan spasi di antara dua " << endl;
    cout << "   huruf/ angka. Karena dapat menimbulkan error/ kesalahan." << endl;
    Sleep(20000);
       return menutama();
}
void garis1 ()
{
    cout << "===============================================================================" << endl;
}
void judul(){
    garis1();
    cout << "                      APLIKASI PENDAFTARAN PAKET INTERNET                                    " << endl;
    cout << "                         Internet Cafe FASILKOM UNSIKA                                       " << endl;
    cout << "              Telp: 085714200950 | e-mail: icafe.unsika@gmail.com                           " << endl;
    garis1 ();
    cout << "\n" << endl;
}
