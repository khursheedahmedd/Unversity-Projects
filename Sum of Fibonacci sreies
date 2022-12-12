#include <iostream>
using namespace std;

int main()
{
    int n;

    cout << "How much numbers you wants from Fibonacci series : ";
    cin >> n;

    int arr[n];
    arr[0]=0;
    arr[1]=1;
    for (int i = 2; i < n; i++)
    {
        arr[i] = arr[i - 1] + arr[i - 2];
    }
    int t = 0;
    for (int i = 0; i < n; i++)
    {
        t += arr[i];
    }
    cout << "\nSum of Fibonacci series is : " << t;

    return 0;
}
