# Nov-07-2021-L10ExercisesProblems
only in .txt

//--------------------------FOR LOOP ODDS OR EVEN----------------------------------

    #include <iostream>
    #include <string>

    using namespace std;
    int main()
    {

    for (int i=20; i<=24; i++){
    if( i % 2 == 0){
    cout << i << " - even \n";
    }
    else{
    cout << i << " -odd \n";
    }
    }
    }

//--------------------------NESTED FOR LOOP 7STAR 7LINES----------------------------------
		       
    #include <iostream>
    #include <string>

    using namespace std;
    int main()
    {

    for (int i=0; i<7; i++){
    for(int j=0; j<7; j++){
    cout << "*";
    }
    cout << endl;
    }

    }
