# first-repositry
I @Nibi840 am new to github and this is my first repositry
#include<iostream>
using namespace std;
class Medical
{
    private:
    char Dname[20];
    int time;
    char Doname[20];
    int fee;
    public:
    void setData();
    void displayData();
};
void Medical :: setData()
{
    cout<<"Department Name";
    cin>>Dname;
    cout<<"Appointment time";
    cin>>time;
    cout<<"Doctors name";
    cin>>Doname;
    cout<<"Fees";
    cin>>fee;
}
 void Medical :: displayData()
 {
    cout<<"Department Name"<<Dname;
    cout<<"checkup time"<<time;
    cout<<"Doctors name"<<Doname;
    cout<<"Fees"<<fee;
    cout<<"-------------------------------"<<endl;

 }
 void mediacal :: listData()
 {
     cout>>
 }
 main()
 {
    Medical p[10];
    int i;
    for(i=1;i<4;i++)
    {
        p[i].setData();
    }
    for(i=1;i<4;i++)
    {
        p[i].displayData();
    }
 }
