#include <iostream> 
using namespace std;

int main() {
double time , distance;

cout<<"Enter the distance taken by a car:"<<endl;
cin>>distance;
cout<<"Enter the time take by a car:"<<endl;
cin<<time;
double speed = distance/time;
cout<<"The speed taken by a car: "<<speed<<"hours"<<endl;

return 0;

}