# Loops-activity1

// Activity 1
// number 1
#include <iostream>
using namespace std;

//first
int main() {
  int i = 0;
  
  cout << "Number from 0 to 10 " << endl;
  while (i <= 10) {
  	cout << i << " ";
    i++;
  }
  cout << endl;
  
 //second
  
   i = 10;
  
  cout << "Number from 10 to 0 " << endl;
  while (i >= 0) {
  cout << i << " ";
  i--;
  }
  cout << endl;
  
 
// number 2

 int sum = 0, num;
    cout << "Enter positive integers (0 to stop):" << endl;
    while (true) {
        cin >> num;
        if (num == 0) break;
        if (num > 0) sum += num;
    }
    cout << "Sum of positive integers: " << sum << endl;
    
// number3

 int number = 1;
    int product = 1;

    while (number <= 5) {
        product *= number; 
        number++;         
    }

    cout << "Product of numbers from 1 to 5: " << product << endl;
  return 0;
}
