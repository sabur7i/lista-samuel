# lista-samuel
#include <iostream>
#include <string>
using namespace std;

struct Pessoa {
    int idade;
    string nome;
    string endereco;
    
};

int main()
{
    struct Pessoa pessoa1; 
      cout<<"coloque suas informacoes"<<endl;
      cout<< "insira o seu nome:" << endl;
      cin>>pessoa1.nome;
      cout<< "insira a sua idade"<< endl;
      cin>>pessoa1.idade;
      cout<< "insira o seu endereço"<<endl;
      cin>>pessoa1.endereco;
      
      
         cout<<"nome:"<<pessoa1.nome<<endl;
         cout<<"idade:"<<pessoa1.idade<<endl;
         cout<<"endereço:"<<pessoa1.endereco;
      
      
    
}
