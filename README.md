# array_

// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;

int main() {
   
    int nums[]={1,3,3,9,10,4};
    int count1=0,count=0;
    int n=sizeof(nums)/sizeof(nums[0]);
    int i1=1;
    int i2=9;
    int j1=4;
    int j2=12;
    for(int i=0;i<n;i++){
        if(i1<=nums[i] and nums[i]<=j1)
        count1++;
    }
    cout<<count1<<endl;
     for(int i=0;i<n;i++){
        if(i2<=nums[i] and nums[i]<=j2)
        count++;
    }
    cout<<count;

    return 0;
}
