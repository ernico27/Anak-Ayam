# Anak-Ayam

    #include<iostream>
    using namespace std;
    int main()
    {
    int x,jumlah_anak_ayam;
    cout << "\t\t ======================== \n";
    cout << "\t\t Program lagu anaka ayam \n";
    cout << "\t\t ======================== \n";
    cout << "\t\t Masukkan anak ayam : ";
    cin >> jumlah_anak_ayam;
    cout << "\t\t Lagu anak ayam " << jumlah_anak_ayam << endl;
    cout << "\t\t Mulai!! " << endl;

    for (x=jumlah_anak_ayam;x>0;x--)
    {
        if (x>1)
            cout << "\t\t Anak Ayam Turun " << x << " Mati 1 tinggal " << x-1 << endl;
        else if (x=1)
            cout << "\t\t Anak Ayam Turun 1 Mati 1 Tinggal Induknya" << endl;
    }
    return 0;
    }

## Hasilnya

![img](https://github.com/ernico27/Anak-Ayam/blob/master/anak%20ayam.png?raw=true)
