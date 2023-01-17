#include <iostream>
#include <conio.h>
using namespace std;

int jam_awal,menit_awal,detik_awal;
int jam_akhir,menit_akhir,detik_akhir;
int waktu_pertama, waktu_kedua, total_waktu, biaya;
string kode;

void waktu()
    {
        printf("\nWaktu Awal [jj:mm:dd]\t\t: ");
            scanf("%d:%d:%d",&jam_awal, &menit_awal,&detik_awal);
        printf("Waktu Akhir [jj:mm:dd]\t\t: ");
            scanf("%d:%d:%d",&jam_akhir, &menit_akhir,&detik_akhir);
        waktu_pertama = (jam_awal*60) + (menit_awal*60) + detik_awal;
        waktu_kedua = (jam_akhir*60) + (menit_akhir*60) + detik_akhir;
        total_waktu = waktu_kedua - waktu_pertama;
    }
void yo()
    {   
        ulang :
        system("cls");
        printf("Cek Biaya Telfon Nih Boss!!!\n\n");
        printf("Kode Wilayah :\n");
        printf("=====================================================\n");
        printf("|*| KODE\t      DAERAH          TARIF       |*|\n");          
        printf("=====================================================\n");
        printf("|*| 021\t\t->    Jakarta     Rp. 150/60 Detik|*|\n");
        printf("|*| 0751\t->    Padang      Rp. 250/30 Detik|*|\n");
        printf("|*| 0737\t->    Medan       Rp. 375/25 Detik|*|\n");
        printf("|*| 0912\t->    Balikpapan  Rp. 415/20 Detik|*|\n");
        printf("|*| 0981\t->    Ternate     Rp. 510/17 Detik|*|\n");
        printf("=====================================================\n");
        printf("Masukkan Kode Wilayah\t\t: ");
        cin >> kode;
            if (kode == "021")
                {
                    waktu();
                    biaya = (total_waktu*60 / 60)*150;
                    cout << "\nBiaya yang dikeluarkan adalah Rp." << biaya;
                    getch();
                    goto ulang;
                }
            else if         (kode == "0751")
                {
                    waktu();
                    biaya = (total_waktu*60 / 30)*250;
                    cout << "\nBiaya yang dikeluarkan adalah Rp." << biaya;
                    getch();
                    goto ulang;
                }
            else if(kode == "0737")
                {
                    waktu();
                    biaya = (total_waktu*60 / 25)*375;
                    cout << "\nBiaya yang dikeluarkan adalah Rp." << biaya;
                    getch();
                    goto ulang;
                }
            else if(kode == "0912")
                {
                    waktu();
                    biaya = (total_waktu*60 / 20)*415;
                    cout << "\nBiaya yang dikeluarkan adalah Rp." << biaya;
                    getch();
                    goto ulang;
                }
            else if(kode == "0981")
                {
                    waktu();
                    biaya = (total_waktu*60 / 17)*510;
                    cout << "\nBiaya yang dikeluarkan adalah Rp." << biaya;
                    getch();
                    goto ulang;
                }
    }
main()
    {
        yo();
    }
