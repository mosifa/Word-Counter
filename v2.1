#include<iostream>
#include<conio.h>
#include<windows.h>
#include<vector>
using namespace std;

void gotoxy(int i , int j){
HANDLE consoleHandle = GetStdHandle(STD_OUTPUT_HANDLE);
COORD cursorCoord;
cursorCoord.X=i;
cursorCoord.Y=j;
SetConsoleCursorPosition(consoleHandle , cursorCoord);
}

void header()
{
	cout<<'\n'<<"\tWords Counter by: "<<'\n'
	<<"                               _  __      "<<'\n'
    <<"	                      (_)/ _|     "<<'\n'
	<<"	 _ __ ___    ___   ___ _| |_ __ _   "<<'\n'
	<<"	| '_ ` _  \\ / _ \\ / __| |  _/ _` |         NO. Words: "<<'\n'
	<<"	| | | | | || (_) |\\__\\  | || (_| |         NO. Characters: "<<'\n'
	<<"	|_| |_| |_| \\___/ |___/_|_| \\_,__|         NO. Lines:"<<'\n'
	<<endl<<endl<<"\t=================================="<<endl<<endl
	<<"Type Here: ";
}

 int main()
 {
 	vector<char>key(1) ; int wr=0 ; int cr=0 ; int ln=13 ;
 	header();
	gotoxy(73 , 5) ; cout << wr;
	gotoxy(73 , 6) ; cout << cr;

    while(wr<=300)
    {
    	firstofloop:
    	if(cr%51 == 0)
    	{
    		ln++;
    		gotoxy(73 , 7);
			cout << ln-13 <<'\b';
		}
		gotoxy(cr - (ln-14)*51 , ln);                             //line function(go to next line after 50 characters)
  		key.push_back(1);
   		key[cr] = getch();

  		if ((key[cr] == char(0)) || (key[cr] == char(224)))       //cursor's moving
        {
            key[cr] = getch();
            switch (key[cr])
            {
                case 75 :
                    gotoxy(cr-- , ln);
                    break;
                case 77 :
                    gotoxy(cr++ , ln);
                 	break;
      		}

      		goto firstofloop;
      	}

      	if (key[cr] == char(8))                                   //backspace function
   		{
   			gotoxy((cr--)-1 , ln);
   			cout<<" "<<'\b';
   			for(int asc=32 ; asc<=64 ; asc++)
   				{
				if( (key[cr] <='z' && key[cr]>='a') || (key[cr] <='Z' && key[cr] >= 'A') )
				{
					if((key[cr-1] == char(asc)))
					{
						wr--;
						gotoxy(73 , 5);
						cout << wr+1 <<'\b';
					}
				}

				}
   			goto firstofloop;
   		}

   		cout << key[cr];
   		gotoxy(73 , 6);
		cout << cr+1 <<'\b';

   		for(int asc=32 ; asc<=64 ; asc++)
   			{
				if( (key[cr] <='z' && key[cr]>='a') || (key[cr] <='Z' && key[cr] >= 'A') )
				{
					if((key[cr-1] == char(asc)))
					{
						wr++;
						gotoxy(73 , 5);
						cout << wr+1 <<'\b';
					}
				}

			}
		cr++;
 	}
 	gotoxy(16 , ln+2);
    cout<<" Your Words Has Reached the Maximum NO. 300! "
		<<endl<<endl<<endl;
    return 1;
   }
