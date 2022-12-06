# PERMUTATION_NO



#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;
int main() {
    int arr[]={10,28,29,38,38};
    next_permutation(arr, arr+5);
    cout << arr[0]<<"  "<<arr[1]<<"  "<<arr[2];

    return 0;
}
