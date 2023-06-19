#include <iostream>
#include <algorithm>
#include <vector>
using namespace std;

int main()
{
    vector<int> v;
    v.push_back(1);
    v.push_back(3);
    v.push_back(6);
    v.push_back(7);

    cout << "Finding 6-> " << binary_search(v.begin(), v.end(), 6) << endl;
    cout << "Lower Bound-> " << lower_bound(v.begin(), v.end(), 6) - v.begin() << endl;
    cout << "Upper Bound-> " << upper_bound(v.begin(), v.end(), 4) - v.begin() << endl;

    int a = 3;
    int b = 5;

    cout << "Max-> " << max(a, b) << endl;
    cout << "Min-> " << min(a, b) << endl;

    swap(a, b);

    cout << "A-> " << a << endl;
    cout << "B-> " << b << endl;

    string abcd = "abcd";
    reverse(abcd.begin(), abcd.end());

    cout << "Reverse String-> " << abcd << endl;

    rotate(v.begin(), v.begin() + 2, v.end());
    cout << "After Rotate" << endl;
    for (auto i : v)
    {
        cout << i << " ";
    }
    cout << endl;

    cout << "After Sort" << endl;

    sort(v.begin(), v.end());
    for (auto i : v)
    {
        cout << i << " ";
    }
    cout << endl;

    return 0;
}
