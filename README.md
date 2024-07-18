# lecture-10
#include <iostream>
using namespace std;

int main() {
    // Variables declaration and initialization
    int i, j, k;
    i = 0;
    j = 0;
    k = 0;

    cout << "Initial values: " << i << " " << j << " " << k << endl;

    // Post-increment: j = i++ 
    // i is assigned to j first, then i is incremented
    j = i++;
    cout << "After j = i++: " << "i = " << i << ", j = " << j << ", k = " << k << endl;

    // Pre-increment: k = ++i 
    // i is incremented first, then the incremented value is assigned to k
    k = ++i;
    cout << "After k = ++i: " << "i = " << i << ", j = " << j << ", k = " << k << endl;

    // Demonstrating a simple for loop with post-increment
    cout << "Values from 1 to 100 using post-increment in for loop: " << endl;
    for (i = 1; i <= 100; i++) {
        cout << i << " ";
    }
    cout << endl;

    return 0;
}
