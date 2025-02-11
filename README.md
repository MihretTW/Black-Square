# Black-Square
#include<iostream>
using namespace std;
int main(){
    int count=0;
    int arr[4];
    for(int i=0;i<4;i++){
        cin>>arr[i];
    }
    string s;
    cin>>s;
    for(int i=0; i<s.length();i++){
        int index=s[i]-'1';
       count+=arr[index];
    }
    cout<<count;
}
