#include <bits/stdc++.h>
using namespace std;

int main()
{
    int n;
    cin>>n;
    for (int i = 1; i <= n; i++)
    {
        for (int j = n; j > i; j--)
        {
            cout<<" ";
        }
        for (int j = 0; j < i; j++)
        {
            cout<<"*";
            
        }
        for (int j = 2; j <= i; j++)
        {
            cout<<j;
        }
        
        cout<<endl;
        
    }
        

    return 0 ;
}
