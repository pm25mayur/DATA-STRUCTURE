#include <iostream>
using namespace std;
int main()
{
    int book[5];
    int temp;
    cout << "Enter IDs of 5 Library Books:" << endl;
    for (int i = 0; i < 5; i++)
    {
        cout << "Book " << i + 1 << " ID:";
        cin >> book[i];
    }
    for (int i = 0; i < 4; i++)
    {
        for (int j = 0; j < 4 - i; j++)
        {
            if (book[j] > book[j + 1])
            {
                temp = book[j];
                book[j] = book[j + 1];
                book[j + 1] = temp;
            }
        }
    }
    cout << "Book IDs in Ascending Order:" << endl;
    for (int i = 0; i < 5; i++)
    {
        cout << book[i] << " ";
    }
    return 0;
}
