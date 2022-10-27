
#include <iostream>
using namespace std;

int main()
{
    int n, m, a;
    cin >> n >> m;
    a = n / m + 1;

    if (n % m == 0)
    {
        for (int i = 0; i < m; i++)
        {
            cout << n / m << " ";
        }
    }
    if (n % m != 0)
    {
        for (int i = 0; i < m - n % m; i++)
        {
            cout << n / m << " ";
        }
        for (int i = 0; i < n % m; i++)
        {
            cout << a << " ";
        }
    }
    system("pause");
}
