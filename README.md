# Codeforcescpp-234A
#include <bits/stdc++.h>
using namespace std;

int main() {
	freopen("input.txt","r",stdin);
  freopen("output.txt","w",stdout);
  int n;
	string s;
	cin >> n;
	cin >> s;
	for (int i = 0; i < n / 2; i++) {
		if (s[i] == 'R' && s[i + n / 2] == 'L')
			cout << i + n / 2 + 1 << " " << i + 1 << endl;
		else
			cout << i + 1 << " " << i + n / 2 + 1 << endl;
	}
	return 0;
}
