#include <iostream>
#include <bits/stdc++.h>
using namespace std;
struct Item {
    int value, weight;
    Item(int value, int weight)
        : value(value), weight(weight)
    {
    }
};
bool cmp(struct Item a, struct Item b)
{
    double r1 = (double)a.value / a.weight;
    double r2 = (double)b.value / b.weight;
    return r1 > r2;
}
double fractionalKnapsack(struct Item arr[],
                          int W, int size)
{
    sort(arr, arr + size, cmp);
    int curWeight = 0;
    double finalvalue = 0.0;
    for (int i = 0; i < size; i++) {
        if (curWeight + arr[i].weight <= W) {
            curWeight += arr[i].weight;
            finalvalue += arr[i].value;
        }
        else {
            int remain = W - curWeight;
            finalvalue += arr[i].value
                          * ((double)remain
                             / arr[i].weight);
            break;
        }
    }
    return finalvalue;
}
int main()
{
    int W = 10;
    Item arr[] = { { 250, 1 },
                   { 960, 8 },
                   { 360, 2 },
                   { 320, 4 },
                   { 840, 6 },
    };
    int size = sizeof(arr) / sizeof(arr[0]);
    cout << "Maximum profit earned = "
         << fractionalKnapsack(arr, W, size);
    return 0;
}
