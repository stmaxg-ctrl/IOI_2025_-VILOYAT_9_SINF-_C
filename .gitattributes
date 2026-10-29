#include <iostream>
#include <string>
#include <set>
#include <vector>
#include <algorithm>
#include <cmath>
using namespace std;



int main(){
    int t;
    cin>>t;
    string a1="SMS",a2="MSM";
    while(t--){
        int n,nq=0;
        cin>>n;
        string a;
        cin>>a;
        for(int i=0;i+3<=n;i++){
            if(a[i]=='S'&&a[i+1]=='M'&&a[i+2]=='S'){
                a[i+2]='M';
                nq++;
            }
            if(a[i]=='M'&&a[i+1]=='S'&&a[i+2]=='M'){
                a[i+2]='S';
                nq++;
            }
        }
        cout<<nq<<endl;

    }
    return 0;
}

