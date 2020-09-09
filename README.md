# -669-A---Ahahahahahahahaha
#include <bits/stdc++.h>
using namespace std;
#define ull unsigned long long

int main() {

    int t;
    cin>>t;
    while(t--){
        int n;
        cin>>n;
        vector<int> A(n);
        int count1=0,count0=0;
        for(int i=0;i<n;i++){
            cin>>A[i];
            if(A[i]==0) count0++;
            else count1++;
        }
        if(count1<=n/2){
                cout<<count0<<endl;
        for(int i=0;i<count0;i++){

                cout<<0<<" ";

            }
            cout<<endl;
        }
        else{
                
            if(count1%2==0){
                    cout<<count1<<endl;
                for(int i=0;i<count1;i++){
                    cout<<1<<" ";
                }
                cout<<endl;
            }else{
                cout<<count1-1<<endl;
                for(int i=0;i<count1-1;i++){
                    cout<<1<<" ";
                }
                cout<<endl;
            }
        }
        }
    }



