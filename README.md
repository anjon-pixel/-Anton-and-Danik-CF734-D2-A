# -Anton-and-Danik-CF734-D2-A
Codeforces Solution


#include<bits/stdc++.h>

using namespace std;

int main(){

    int a,count1=0,count2=0;
    cin>>a;
    string S;
    cin>>S;

    for(int i=0;i<a;i++){

        if(S[i]=='A'){

            count1++;
        }
        else if(S[i]=='D'){

            count2++;
        }

    }
    if(count1>count2){

        cout<<"Anton";
    }
    else if(count1<count2){

        cout<<"Danik";
    }
    else if(count1==count2){

        cout<<"Friendship";
    }
    return 0;
}
