#include <iostream>
using namespace std;
int main()
{
    int rno[10];
    int marks[10];
    int n = 0;
    int choice;
    int searchRoll;
    do
    {
        cout << "\n\n===== STUDENT MANAGEMENT SYSTEM =====";
        cout << "\n1. Add Student";
        cout << "\n2. Display Students";
        cout << "\n3. Search Student";
        cout << "\n4. Exit";
        cout << "\nEnter your choice: ";
        cin >> choice;
        // Add Student
        if (choice == 1)
        {
            cout << "\nEnter Roll Number: ";
            cin >> rno[n];
            cout << "Enter Marks: ";
            cin >> marks[n];
            n++;
            cout << "Student Added!";
        }
        // Display Students
        else if (choice == 2)
        {
            cout << "\n===== STUDENT RECORDS =====\n";
            for (int i = 0; i < n; i++)
            {
                cout << "Roll Number: " << rno[i] << endl;
                cout << "Marks: " << marks[i] << endl;
            }
        }
        // Search Student
        else if (choice == 3)
        {
            cout << "\nEnter Roll Number to search: ";
            cin >> searchRoll;
            bool found = false;
            for (int i = 0; i < n; i++)
            {
                if (rno[i] == searchRoll)
                {
                    cout << "\nStudent Found!";
                    cout << "\nRoll Number: " << rno[i];
                    cout << "\nMarks: " << marks[i];
                    found = true;
                }
            }
            if (!found)
            {
                cout << "\nStudent Not Found!";
            }
        }
        // Exit
        else if (choice == 4)
        {
            cout << "\nThank you!";
        }
        else
        {
            cout << "\nInvalid Choice!";
        }
    } while (choice != 4);
    return 0;
}
