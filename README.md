# tusk
<!-- I developed  code to find the largest element in array -->
#include <iostream>
using namespace std;
int main()
{
    int num[10], n, larger;

    cout << "enter any element find largest no\n";
    cin >> n;
    for (int i = 0; i < n; i++)
    {
        cout << "enter any no " << i + 1 << "\n";
        cin >> num[i];
    }
    larger = num[0];
    for (int i = 1; i < n; i++)
    {
        if (larger < num[i])
            larger = num[i];
    }
    cout << "lagest element in array \n"
         << larger;
    return 0;
}
