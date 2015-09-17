# c-TC1017
Here are some of my codes for c++ class 
echo "# c-TC1017" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/A01154027/c-TC1017.git
git push -u origin master

#include <iostream>
#include <cstdlib>
#include <ctime>
using namespace std;
int main ()  {
int x;
srand (time(NULL));
int r= rand() % 100 + 1;
cout <<"Try to guess the number.";
cin>> x;
while (x!=r)
  {
    if (x<r)
    {
      cout <<"That is too low. Try again."<< endl;
      cin>> x;
    }
    if (x>r)
    {
      cout <<"That is too high. Try again."<< endl;
      cin>> x;
    }
    if (x==r)
    {
      cout <<"That is the right number. Congratulations."<<endl;
      cout <<"Let us dance."<<endl;
    }
}

  return 0;
  }
