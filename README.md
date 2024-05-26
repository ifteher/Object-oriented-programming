///creat a class with constractor in oop.
#include<bits/stdc++.h>
using namespace std;
class youtubechannel
{
public:
    string Name;
    string OwnerName;
    int subscriberCount;
    list<string>publishedVideoTitles;
};
int main()
{
    youtubechannel ytchannel;
    ytchannel.Name = "ZayedOfficials";
    ytchannel.OwnerName = "Zayed";
    ytchannel.subscriberCount = 1800;
    ytchannel.publishedVideoTitles = {"C++ for beginners vedio:1","HTML & CSS vedio:1" , "C++ OOP vedio:1"};
    cout<<"Name: "<<ytchannel.Name<<endl;
    cout<<"OwnerName: "<<ytchannel.OwnerName<<endl;
    cout<<"subscriberCount: "<<ytchannel.subscriberCount<<endl;
    cout<<"publishedVideoTitles are : "<<endl<<endl;

    for(auto vedioTitle : ytchannel.publishedVideoTitles)
    {
        cout<<vedioTitle<<endl;
    }
    return 0;
}
