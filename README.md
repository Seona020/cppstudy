# cppstudy

#include <iostream>
using namespace std;

int main(){


    double fd, cd;
    cout << "화씨온도입력: ";
    cin >> fd;
    /* 여기코딩*/
    cd = (5/9)*(fd-32);
    cout << "섭씨온도는" << cd << " 입니다." << endl;

    return 0;
}
