
#include <iostream>

using namespace std;

int main()
{   
    int hvalue;
    int bvalue;
    
    cout<<"Value for height:";
    cin >> hvalue;
    
    cout << "Value for base:";
    cin >> bvalue;
    
    int answer = 0.5 * hvalue * bvalue;
    
    cout << "answer" << answer;

    return 0;
    
}
