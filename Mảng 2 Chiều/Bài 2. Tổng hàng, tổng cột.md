![image](https://github.com/Llam-a/Practice_Cpp/assets/115911041/cba469a7-69a0-4231-92cd-2de104c665d5)

```
#include<bits/stdc++.h>

using namespace std;

int main(){
    int n, m; cin >> n >> m;
    int a[n][m];
    for(int i = 0; i < n; i++){
        for(int j = 0; j < m; j++){
            cin >> a[i][j];
        }
    }
    for(int i = 0; i < n; i++){
        long long tong = 0;
        for(int j = 0; j < m; j++){
            tong+=a[i][j];             
        }
        cout << tong << " ";
    }
    cout << endl;
    for(int i = 0; i < m;i++){
        long long tong = 0;
        for(int j = 0; j < n; j++){
            tong+=a[j][i];
        }
        cout << tong << " ";
    }

}
```
