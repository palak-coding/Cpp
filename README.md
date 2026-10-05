# Cpp
#include <iostream>
using namespace std;

int main() {int k;
    int size;
    cout<<"the size:";
    cin>>size;
        int arr[100];
    cout<<"the elements "<<size <<"of array arr:\n ";
    for(int i=0;i<size;i++)
        {cin>>arr[i];
        }
    for(int i=0;i<size;i++)
        {cout<<arr[i]<<",";}

    
        int size1;
    cout<<"\nthe size of brr:\n";
    cin>>size1;
        int brr[100];
    cout<<"the elements "<<size1 <<"of array: ";
    for(int j=0;j<size1;j++)
        {cin>>brr[j];
        }
    for(int j=0;j<size;j++)
        {cout<<brr[j]<<",";}

 int crr[100];
            cout<<"\nAfter merging of arr and brr:\n";


    for(int i=0;i<size;i++){
        crr[k]=arr[i];
        k++;
    }

    for(int j=0;j<size1;j++){
        crr[k]=brr[j];
        k++;
    }

    for(int k=0;k<size+size1;k++){
        cout<<crr[k]<<" ,";
        
    }

    
    return 0;
    
}
