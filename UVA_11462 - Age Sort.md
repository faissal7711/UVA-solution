# UVA-solution
solutions for the problems in UVA
//============================================================================
// Name        : test.cpp
// Author      : foo
// Version     :
// Copyright   : Your copyright notice
// Description : Hello World in C++, Ansi-style
//============================================================================

#include <bits/stdc++.h>
#include <string>
#include <algorithm>
using namespace std;
map<char, int> mp;
map<long, long> count;
map<int, int> count1;
set<char> st;
set<int> re;
char ch1, ch2, ch3;
int c = 0;
priority_queue<char> pq1, pq2;
int main() {
	int n;
	while((scanf("%d",&n)) && n)
	{
		int a[n];
			for (int i = 0; i < n; ++i) {
				scanf("%d",&a[i]);
			}
			sort(a,a+n);
			if(n)
			for (int i = 0; i < n; ++i) {
				cout<<a[i];
				if(i != n-1)
					cout<<" ";
			}
			printf("\n");
	}
	return 0;
}
/*  		error in this test cases
 *
 * 9
 * 2 1 3 5 4 1 2 3 1
 * 0
 *
 */
