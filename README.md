
# include <iostream>
#include <cstdlib>
#include <ctime>

using namespace std;

int main(){
    int maxValue = 6;
    int minValue = 1;
    long elapseSeconds = time(0);
    srand(elapseSeconds);
    int number = rand()%((maxValue-minValue)+1)+ minValue;
    cout<< number;
    return 0;
    
}


//This programming allows me to generate a random number between 1 and 6 using the =RAND() equation to create a 
//random number after running the program. I set the max value to be 6 and minimum value to be 1 so that we don't 
//get anything beyond the desired range.

