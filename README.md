//Write a program to create an integer array of size 5 and initialize it with values {1, 2, 3, 4, 5}.

 #include<bits/stdc++.h>
 using namespace std;
 int main(){
     int arr[5]={1,2,3,4,5};
     for(auto it:arr){
         cout<<it;
     }
    return 0;
}


------------------------------------------------------------------------------------------------------------
//Declare a vector of integers and take 5 inputs from the user to store in the vector
#include <bits/stdc++.h>
using namespace std;

int main() {
    vector<int> numbers(5);  

    cout << "Enter 5 integers: ";
    for (auto &it : numbers) {
        cin >> it;
    }

    cout << "You entered: ";
    for (auto it : numbers) {
        cout << it << " ";  
    }

    return 0;
}

-----------------------------------------------------------------------------------------------------------


//Create a vector of size 10 and initialize all elements with the value 100.

#include <bits/stdc++.h>
using namespace std;

int main() {
    vector<int> numbers(10,100);  

    
    for (auto it : numbers) {
        cout << it<<" ";
    }

  

    return 0;
}




---------------------------------------------------------------------------------------------------------------


//Initialize an array with the first 10 natural numbers and print them using a loop.


#include <bits/stdc++.h>
using namespace std;

int main() {
   int arr[10]={1,2,3,4,5,6,7,8,9,10};
   for(auto it:arr){
       cout<<it<<" ";
   }
  

    return 0;
}



---------------------------------------------------------------------------------------------------------------


//Create a vector with values {5, 10, 15, 20, 25}, then print the last element using the .back() function.

#include<bits/stdc++.h>


using namespace std;
int main(){
    
    vector<int>values={5,10,15,20,25};
    
    
    cout<<"the last element is : " << values.back();
}




---------------------------------------------------------------------------------------------------------------
//Given an array {2, 4, 6, 8, 10}, write a program to multiply each element by 3 and store the result in the same array.


#include<bits/stdc++.h>


using namespace std;
int main(){
    
    int arr[5]={2,4,6,8,10};
    for(auto &it:arr){
        cout<<it<<" ";
    }
    cout<<endl;
    cout<<"after multiply by 3 each element : ";
    for(auto it:arr){
        cout<<it*3<<" ";
    }
    return 0;
}

------------------------------------------------------------------------------------------------------------------

//Create a vector with user-input values and multiply each element by -1, then print the modified vector.

#include<bits/stdc++.h>


using namespace std;

int main(){
    
    vector<int>values(10);
    cout<<"please neter the 10 value "<< " ";
    for(auto &it:values){
        cin>>it;
    }
    cout<<endl;
    cout<<"after multiply by -1 each element : ";
    for(auto it:values){
        cout<<it*-1<<" ";
    }
    return 0;
}


--------------------------------------------------------------------------------------------------------------

//Declare an array of size n (user input) and initialize it with numbers from 1 to n. Multiply all even-indexed elements by 2.


#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cout << "Enter the size of the array: ";
    cin >> n;  
    int arr[n];  
    for (int i = 0; i < n; i++) {
        arr[i] = i + 1;  
    }

    
    for (int i = 0; i < n; i += 2) {  
        arr[i] *= 2;  
    }

    cout << "Modified array: ";
    for (int i = 0; i < n; i++) {
        cout << arr[i] << " ";
    }

    return 0;
}

--------------------------------------------------------------------------------------------------------------
