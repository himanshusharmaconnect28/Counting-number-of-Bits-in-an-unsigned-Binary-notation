# Counting-number-of-Bits-in-an-unsigned-Binary-notation
#include<iostream>
using namespace std;
int main() {
    int n = 22;
    int count = 0;
    while (n != 0) {
        if (n & 1) {
            count++;
        }
        n = n >> 1;
    }
    cout<< count;
    return 0;
}
