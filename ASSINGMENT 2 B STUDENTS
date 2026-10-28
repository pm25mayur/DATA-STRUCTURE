#include <iostream>
using namespace std;
int main()
{
    int rno[5];
    int searchID;
    cout << "Enter Roll No. of 5 Students:" << endl;
    for (int i = 0; i < 5; i++)
    {
        cout << "Student " << i + 1 << " : ";
        cin >> rno[i];
    }
    cout << "\nEnter Roll No. to search: ";
    cin >> searchID;
    for (int i = 0; i < 5; i++)
    {
        if (rno[i] == searchID)
        {
            cout << "Roll No. Found!";
            return 0;
        }
    }
    cout << "Roll No. Not Found!";
    return 0;
}
