#include<iostream>
using namespace std;

int main()
{
    int num,i;
    cout<<"Enter a number : ";
    cin>>num;
    for(i=3; i<num; i++)
    {
        int x,z,y=1;
        for(x=2; x<i; x++)
        {
            if(i%x==0)
            {
                y++;
                break;
            }
        }
        if(y<=1)
        {
            for(z=num-i; z>0; z--)
            {
                int a,b=1;
                for(a=2; a<z; a++)
                {
                    if(z%a==0)
                    {
                        b++;
                        break;
                    }
                }

                if(b<=1 && z+i==num)
                {
                    cout<<num<<"="<<i<<"+"<<z<<endl;
                }
                else
                {
                    cout<<"No result";
                    break;
                }
            }
        }
    }
}