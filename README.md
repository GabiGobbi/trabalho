    #include <iostream>
 
    using namespace std;

    int main()
 
    {
 
    float n1, n2, n3, media, meio;
     
    cout<<"==MEDIA=="<<endl;
    cout<<endl<<"Digite sua nota 1: ";
    cin>>n1;
    cout<<endl<<"Digite sua nota 2: ";
    cin>>n2;
    cout<<endl<<"Digite sua nota 3: ";
    cin>>n3;
    meio=n1*2 + n2*3 + n3*5;
    media=meio/10;
    cout<<endl<<"Sua media eh: ";
    cout<<media;

    return 0;
    }
