#include <iostream>
#include <string>
using namespace std;

int main(){
    string a;

    cout<<"Enter your Word:";
    cin>>a;

    if (a== "BRAX"){
        cout<<"An SOE student in Universidad de Dagupan";
    }else if (a== "BATMAN"){
        cout<<"A Detective Comics fictional character who is a Masked Vigilante thar fights criminals in the city of Gotham.";
    }else if (a== "CALCULATOR"){
        cout<<"A Calculator is used for computing simple and complex math problems or equations";
    }else if(a== "KEYBOARD"){
        cout<<"A Keyboard is used as an input device in order to incode a command or show a word or a sentence on an output device(ex:monitor)";
    }else if (a== "MONITOR"){
        cout<<"A Monitor is used as an Output device in order to show the results or outputs of an input device";
    }else{
        cout<<"No word is found";
    }

    return 0;
}
