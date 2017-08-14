#include <iostream>
#include <conio.h>
#include <stdlib.h>
using namespace std;

int main()
{
    int m=0;
    char a, b, c, d, e, q;
    cout << "*****************************************************" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                     MATHS TEST                    *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*****************************************************" << endl << endl << endl;
    do {
    cout << "You have to solve five mathematics questions. The result will be displayed after you have entered all the answers." << endl << endl;
    cout << "QUESTION NO# 01" << endl << endl;
    cout << "567-264 =" << endl << endl;
    cout << "a) 312" << endl;
    cout << "b) 831" << endl;
    cout << "c) 303" << endl;
    cout << "d) 198" << endl << endl;
    cout << "Enter an option: ";
    cin >> a;
    if (a=='c')
        m++;
    system("cls");

    cout << endl << "QUESTION NO# 02" << endl << endl;
    cout << "987 % 5 =" << endl << endl;
    cout << "a) 0" << endl;
    cout << "b) 2" << endl;
    cout << "c) 1" << endl;
    cout << "d) 985" << endl << endl;
    cout << "Enter an option: ";
    cin >> b;
    if (b=='b')
        m++;
    system("cls");

    cout << endl << "QUESTION NO# 03" << endl << endl;
    cout << "3675 / 25 =" << endl << endl;
    cout << "a) 147" << endl;
    cout << "b) " << endl;
    cout << "c) " << endl;
    cout << "d) " << endl << endl;
    cout << "Enter an option: ";
    cin >> c;
    if (c=='a')
        m++;
    system("cls");

    cout << endl << "QUESTION NO# 04" << endl << endl;
    cout << "63/4 + 52/24 =" << endl << endl;
    cout << "a) 430/24" << endl;
    cout << "b) 320/63" << endl;
    cout << "c) 112/24" << endl;
    cout << "d) 215/12" << endl << endl;
    cout << "Enter an option: ";
    cin >> d;
    if (d=='d')
        m++;
    system("cls");

    cout << endl << "QUESTION NO# 05" << endl << endl;
    cout << "487*3 =" << endl << endl;
    cout << "a) 1461/2" << endl;
    cout << "b) 346*3" << endl;
    cout << "c) 2922/2" << endl;
    cout << "d) 136*6" << endl << endl;
    cout << "Enter an option: ";
    cin >> e;
    if(e=='c')
        m++;
    system("cls");
    cout << "*****************************************************" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                    TEST END                       *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*                                                   *" << endl;
    cout << "*****************************************************" << endl << endl << endl;
    cout << "Your score is " << m <<" / 5" << endl;
    cout << "Do you want to take the test again (y/n) ?";
    cin >> q;
    if(q!='y' || q!='n')
        break;
    } while(q!='n');
    return 0;
}

