#include <iostream> 
using namespace std;
 
class Time
{
    private:
        int seconds;
        int hh,mm,ss;
    public:
        void getTime(void);
        void convertInSeconds(void);
        void displayTime(void);
};
 
void Time::getTime(void)
{
    cout<<"Enter time:"<<endl;
    cout<<"Hours?  ";          
    cin >> hh;
    cout<<"Minutes?  ";          
    cin >> mm;
    cout<<"Seconds?  ";          
    cin >> ss;
}
 
void Time::convertInSeconds(void)
{
    seconds=hh*3600+mm*60+ss;
}
 
void Time::displayTime(void)
{
    cout<<"The time is="<<hh<<":"
                        <<mm<<":"
                        <<ss<<endl;
    cout<<"Time in total seconds:"<<seconds;
}
 
int main()
{
    Time T;
    T.getTime();
    T.convertInSeconds();
    T.displayTime();
    
    return 0;
}
