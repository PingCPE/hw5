hw5
===

#include<stdio.h>
#include<iostream>
using namespace std;

int main()
{
    string table[] = {"abcd","efgh","ijkl","mnop"};
    for (int c = 0; c <= 4; c++)
    {
        for(int r = 0; r<= 4; r++)
        {
            string word = word + table[c][r];
            cout<<word;
        }
    }
}
