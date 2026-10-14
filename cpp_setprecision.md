#include <iostream>
#include <iomanip>
using namespace std;

int main(){
	double a ;
	int b ;
	char c;
	double d;
	cin >> a >> b >> c >> d;
	cout << c << " " << b << " " << fixed << setprecision(2) << a  << " " << d;
	
	return 0;
}

关于怎样保留小数点后两位数字
1.需要引用头文件#include<iomanip>
2.需要写明fixed<<setprecision(2) <<
