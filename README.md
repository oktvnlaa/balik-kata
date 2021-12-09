#include <iostream>
//menggunakan librari string.h karena fungsi "strlen" akan dipakai
#include <string.h>
using namespace std;

int main(){
	//deklarasi variabel
	char kata [20];
	
	cout<<"\t Program Membalik Kata \n\n";
	cout<<"Masukkan sebuah kata : ";
	cin>>kata;
	
	cout<<"\n Kata Setelah Dibalik : ";
	
	//looping for untuk membalik kata
	for (int i = strlen(kata)-1; i>=0; i--){
		cout<<kata[i]<<" ";
	}
	
	//return 0;
}
