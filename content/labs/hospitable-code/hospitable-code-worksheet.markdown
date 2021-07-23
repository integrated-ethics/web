---
title: Hospitable Code Practices
author: Lori Carter
pagecat: worksheet
date: 2021-07-21
---

&nbsp;

<div>
<input class = "tabset" type="radio" name="tabs" id="tab5" checked />
<label for="tab5">Choose a langauge:</label>
<input class = "tabset" type="radio" name="tabs" id="tab1" />
<label for="tab1">C++</label>
<input class = "tabset" type="radio" name="tabs" id="tab2" />
<label for="tab2">Java</label>
<input class = "tabset" type="radio" name="tabs" id="tab3" />
<label for="tab3">Python</label>
<input class = "tabset" type="radio" name="tabs" id="tab4" />
<label for="tab4">R</label>
<div class="tab content5">
</div>

<div class="tab content1">


```eval
#include <iostream>
#include <vector>
#include <exception>
using namespace std;

bool w(vector<int> y)
{
	int z = 0;
	for (int i = 0; i < y.size(); i++)
		z += y.at(i);
		if(z>20)
			return false;
	return true;
}
void f(int * r, bool a)
{
	if (*r == 14 && a)
		*r = 11;
	else if (*r == 14 && !a)
		*r = 1;
	else if (*r > 10)
		*r = 10;
}
int main()
{
	int seed;
	cin >> seed;
	srand(seed);
	char n,c;
	do{
		vector <int> x;
		int p = 0;
		int * h = &p;
		p = rand() % 14 + 1;
		f(h,true);
		x.push_back(p);
		int t=0;
		do{
			p = rand() % 14 + 1;
			if (t <= 10)
				f(h, true);
			else
				f(h, false);
			x.push_back(p);
			//cout << "you have " << endl;
			t = 0;
			for (int i = 0; i < x.size(); i++) {
				t += x.at(i);
				cout << x.at(i) << " ";
			}
			cout << endl;
			if (w(x)) {
				cout << "Another?" << endl;
				cin >> c;
			}
		} while (w(x) && c=='y');
		int o = rand() % 20;
		if (w(x) && o < t)
			cout << "You win! :)" << endl;
		else if (w(x) && o > t) {
			cout << "You got beat :(" << endl;
			cout << "Other person had " << o << endl;
		}
		else if (w(x) && o == t)
			cout << "You tied :/" << endl;
		else
			cout << "You lose. :(" << endl;
		cout << "again? y or n" << endl;
		cin >> n;
	} while (n == 'y');
	cin.ignore(1);
	return 0;
}
```
</div>
<div class="tab content2">

```
import java.util.*;

public class hMod
{
   public static boolean w(ArrayList<Integer> y)
   {
      int z = 0;
      for (int i = 0; i < y.size(); i++)
         z += y.get(i);
         if(z>20)
            return false;
      return true;
   }
   public static void f(int r, boolean a)
   {
      if (r == 14 && a)
         r = 11;
      else if (r == 14 && !a)
         r = 1;
      else if (r > 10)
         r = 10;
   }
   public static void main(String[]args)
   {
      Scanner sc=new Scanner(System.in);
      Random srand = new Random();
      char n,c='y';
      do{
         ArrayList <Integer> x = new ArrayList<Integer>();
         int p = 0;
        
         p = srand.nextInt(14) + 1;
         System.out.println("first p "+p);
         f(p,true);
         x.add(p);
         int t=0;
         do{
            p = srand.nextInt(14) +1;
            System.out.println("next p "+p);
            if (t <= 10)
               f(p, true);
            else
               f(p, false);
            x.add(p);
            //System.out.println("you have " );;
            t = 0;
            for (int i = 0; i < x.size(); i++) {
               t += x.get(i);
               System.out.print( x.get(i) + " ");
            }
            System.out.println();
            if (w(x)) {
               System.out.println("Another?" );
               c =sc.next().charAt(0);
            }
         } while (w(x) && c=='y');
         int o = srand.nextInt(20);
         if (w(x) && o < t)
         {
            System.out.println( "You win! :)");
            System.out.println("Other person had " + o);}
         else if (w(x) && o > t) {
            System.out.println("You got beat :(" );
            System.out.println("Other person had " + o);
         }
         else if (w(x) && o == t)
            System.out.println( "You tied :/");
         else
         {
            System.out.println("You lose. :(");
            System.out.println("Other person had " + o);
            }
         System.out.println("again? y or n" );
         n=sc.next().charAt(0);
      } while (n == 'y');
     
   }
}
```
</div>
<div class = "tab content3">
Python code coming soon.
<br>
</div>
<div class = "tab content4">
R code coming soon.
<br>
</div>
</div>

<hr>

## Looking at some code

1.  Choose one of the languaes listed above. 
    Copy the code into a file on your computer; compile if necessary; and run it.
    (You don't have to inspect the code itself at this point.)

2.  Based on running the code, what is your best guess as to what this code does?

3.  Is the program easy to use? Why or why not? Give at least 2 reasons.

4.  Now look at the code itself. Spend about 10 minutes trying to make the
    code more user-friendly. 
    <!-- Paste the improved code below. -->

5.  List 3 challenges that you had in trying to make the code
    more user friendly.

## Consider this

You are the manager of a software team. Some of your
    team members are writing code without good variable names or
    comments. One way to address the situation would be with a
    deontological approach. Recall that the deontological ethical
    framework relies on a set of rules. One such rule may be that
    "variable names must be meaningful and you must use comments at
    least every 5 lines in your code." 
    
6. How do you think this would go over with the team member?

7. Would there be a better way to approach the team member? Suggest a
method for approaching the team member using one of the other ethical
frameworks.

8. Describe how you would explain the situation and the need to the
team member.

### Peer Review of Hospitality Assignment

Compare your previous answers with another student or group of students.

9. Identify two points that both you and the other group made when reviewing
the code.

10. Identify one point that the other student or group made that you did not.
    Do you agree or disagree with the author on this point. Why or why not?
