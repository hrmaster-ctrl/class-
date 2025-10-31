#include <iostream>
using namespace std;

    class character {
        public:
        character(){
        cout<<"Fantasy genera has started"<<endl;
        cin>>name;
        cin>>age;
        cin>>race;
        cin>>height;
        
        }
        int age;
        string name;
        string race;
        int height;
        int attackpower;
        
        void printname(){
            cout<<name<<endl;
        }
        void printage(){
            cout<<age<<endl;
        }
        void printrace(){
            cout<<race<<endl;
        }
        void printheight(){
            cout<<height<<endl;
        }
        void printattackpower(){
            cout<<attackpower<<endl;
        }

    };
        //string 
        int main (){
            character fantasy;
            character torita;
            
            
            cout<<fantasy.age<<endl;
            cout<<fantasy.name<<endl;
            cout<<fantasy.race<<endl;
            cout<<fantasy.height<<endl;
            cout<<fantasy.attackpower<<endl;

            cout<<torita.age<<endl;
            cout<<torita.name<<endl;
            cout<<torita.height<<endl;
            cout<<torita.race<<endl;
            cout<<torita.attackpower<<endl;

            
            return 0;
        }
