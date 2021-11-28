#include <iostream>
using namespace std;
int main(){
    int input;
    cout<<"Input the specified number: ";
    cin>>input;
    
    for(int i = 0; i <= input;){
        cout<<i++<<" ";
    }
    cout<<endl;
    
    return 0;
}
