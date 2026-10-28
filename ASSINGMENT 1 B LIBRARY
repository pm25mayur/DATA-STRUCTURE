#include <iostream>
using namespace std;
int main()
{
    int book[5];
    int searchID;
    cout << "Enter IDs of 5 Books:" << endl;
    for (int i = 0; i < 5; i++)
    {
        cout << "Book " << i + 1 << " ID:";
        cin >> book[i];
    }
    cout << "\nEnter Book ID to search: ";
    cin >> searchID;
    for (int i = 0; i < 5; i++)
    {
        if (book[i] == searchID)
        {
            cout << "Book Found!";
            return 0;
        }
    }
    cout << "Book Not Found!";
    return 0;
}
