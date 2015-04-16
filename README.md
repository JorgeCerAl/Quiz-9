# Quiz-9



#include <iostream>
using namespace std;

int triangles1(int x){
    x = x - 1;

for(int ii = 0; ii < x; ii++){
for(int i = 0; i < x; i++){
cout << "T";
}
x = x - 1;
cout << endl;
ii = 0;

}
cout << "T" << endl;
return 0;
}

int triangles2(int x){
int i = 0, u;
for(int ii = 0; ii < x; ii++){
 i = 1 + i;
u = i;
for(i ; i != 0; i--){
cout << "T";
}
i = u;
x = x - 1;
cout << endl;
ii = 0;

}
return 0;
}

int main(){
int x;

cout << "Tamaño de tu triangulo\n";
cin >> x;
triangles2(x);
triangles1(x);

return 0;
}
