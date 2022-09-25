//program to craete node in the linked list 
#include<iostream>
using namespace std;
class Node{
    public:
    int data;
    Node*next;
//using constructor 
 Node(int data){
//this is not a pointer, but can be usedlike a pointer mostly (try assignment).
this->data=data;
this->next=NULL;
}
};
int main()
{
    Node*node1=new Node(10);
    cout<<node1->data<<endl;
    cout<<node1->next<<endl;
    return 0;
}
