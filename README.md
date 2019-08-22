#include <iostream>
 #include<vector>
 #include<algorithm>
 using namespace std;



 int main(){
     vector<int> v;
     v.push_back(10);
     v.push_back(45);
      v.push_back(18);
       v.push_back(35);
        v.push_back(145);

        sort(v.begin(),v.end());
    
         v.pop_back();
        int k= (int)v.size();

        for(int i=0;i<k;i++){

            cout<<v[i]<<" ";
        }
        cout<<endl;


         

 }
