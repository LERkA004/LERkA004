#include<iostream> 
using namespace std; 

int main()
{
int k, i = 1, sum_k = 0, number;
cout << " Enter the amount of integers = "; cin >> k;
if (k > 0)
{ 
    do {
    cout << "Enter integer nr. " << i << ": "; 
    cin >> number;
    sum_k += number; 
    i++;
    } while (i <= k);

cout << " Enter the amount of integers to sum = "; cin >> k;
if (k == 0) {
    cout << " You should enter the positive integer "; // if k is not positive integer programm will show us the following message
} else {
    if (k > 0) { // loop will work only when k > 0
        do {
        cout << "Enter integer nr. " << i << ": "; 
        cin >> number;
        sum_k += number; 
        i++;
        } while (i <= k);
    }
    cout << " The total sum of " << k << " integers is: "  << sum_k;
}
cout << " The total sum of " << k << " integers is: "  << sum_k;
return 0;
}
