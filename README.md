//# Lab6-SwitchMenu.cpp.
#include <iostream>
using namespace std;

int main() {
    int choice;

    cout << "Menu Options:\n";
    cout << "1. Area of Circle\n";
    cout << "2. Area of Rectangle\n";
    cout << "3. Exit\n";
    cout << "Enter your choice: ";
    cin >> choice;

    switch (choice) {
        case 1:
            cout << "Area of Circle" << endl;
            break;

        case 2:
            cout << "Area of Rectangle" << endl;
            break;

        case 3:
            cout << "Goodbye!" << endl;
            break;

        default:
            cout << "Invalid choice." << endl;
    }

    return 0;
}

//GuideQuestions
//#1.The program will continue to execute the next cases even they don't match.
//#2.If you have to compare one variable to a several constant value to make the code clean,fast and also easy to read.
