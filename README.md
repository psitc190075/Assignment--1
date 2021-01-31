# Assignment-#include <iostream>
#include <string>
#include <math.h>
using namespace std;

int main()
{    string name;
     const int vat=12;
     int ID;


    cout<<"...................Welcome TO INF SUPERMARKET................"<<endl;
    cout<<"******       Two things are done in the supermarket     *****"<<endl;
    cout<<"1.Purchasing an item"<<endl;
    cout<<"2.Make enquiries"<<endl;

    cout<<"    What is your name?   "<<endl;
    getline(cin,name);


cout<<"Items sold\n";
cout<<"A.Printer=$35\n";
cout<<"B.Phone=$55\n";
cout<<"C.Table=$15\n";

cout<<"Enter your unique ID in numbers"<<endl;
cin>>ID;

cout<<"What do you want to buy(one item at a time for now"<<endl;
string buy;
cin>>buy;

string A="printer";
string B="Phone";
string c="Table";

double printer=35;
double phone=55;
double table=15;
double totalcost,totalamountpaid;



cout<<"Please enter the quantity you want to buy?"<<endl;
int quantity;
cin>>quantity;

cout<<"Please enter amount?"<<endl;
int moneynow;
cin>>moneynow;

if(moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"Your money is not enough to purchase item"<<endl;


}
  else if(buy=="printer" || buy=="Printer" || buy=="PRINTER"){

    totalcost=(quantity*printer);
    cout<<"$"<<"The total cost is:  "<< totalcost<<endl;
    totalamountpaid=totalcost+vat;
    cout<<"$"<<"Total amount to be paid with vat: "<<totalamountpaid<<endl;
    double balance;
    balance= moneynow - totalamountpaid;

    cout<<"Your balance after payment: "<<balance<<endl;


    cout<<"..............................................."<<endl;
    cout<<"** RECEIPT ** "<<endl;
    cout<<"NAME OF THE CUSTOMER: "<<name<<endl;
    cout<<"UNIQUE ID: "<<ID<<endl;
    cout<<"ITEM BOUGHT: "<<buy<<endl;
    cout<<"QUANTITY BOUGHT: "<<quantity<<endl;
    cout<<"vat amount: "<<"$"<<vat<<endl;
    cout<<"total cost: "<< "$"<<totalcost<<endl;
    cout<<"total amount paid: "<<"$"<<totalamountpaid<<endl;
    cout<<"balance: "<<"$"<<balance<<endl;
    cout<<".............................................."<<endl;
         cout<<"Thank You For Transacting With Us: "<<endl;
}





if(moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"Your money is not enough to purchase item"<<endl;


}
  else if(buy=="phone" || buy=="Phone" || buy=="PHONE"){

    totalcost=(quantity*phone);
    cout<<"The total cost is:  "<< totalcost<<endl;
    totalamountpaid=totalcost+vat;
    cout<<"Total amount to be paid with vat: "<<totalamountpaid<<endl;
    double balance;
    balance= moneynow - totalamountpaid;

    cout<<"Your balance after payment: "<<balance<<endl;


    cout<<"................................"<<endl;
    cout<<"** RECEIPT ** "<<endl;
    cout<<"NAME OF THE CUSTOMER: "<<name<<endl;
    cout<<"UNIQUE ID: "<<ID<<endl;
    cout<<"ITEM BOUGHT: "<<buy<<endl;
    cout<<"QUANTITY BOUGHT: "<<quantity<<endl;
    cout<<"vat amount: "<<"$"<<vat<<endl;
    cout<<"total cost: "<<"$"<<totalcost<<endl;
    cout<<"total amount paid: "<<"$"<<totalamountpaid<<endl;
    cout<<"balance: "<<"$"<<balance<<endl;
    cout<<"......................................."<<endl;
        cout<<"Thank You For Transacting With Us: "<<endl;
}




if(moneynow<printer || moneynow<phone || moneynow<table){
        cout<<"Your money is not enough to purchase item"<<endl;


}
  else if(buy=="table" || buy=="Table" || buy=="TABLE"){

    totalcost=(quantity*phone);
    cout<<"The total cost is:  "<< totalcost<<endl;
    totalamountpaid=totalcost+vat;
    cout<<"Total amount to be paid with vat: "<<totalamountpaid<<endl;
    double balance;
    balance= moneynow - totalamountpaid;

    cout<<"Your balance after payment: "<<balance<<endl;


    cout<<"............................"<<endl;
    cout<<"** RECEIPT ** "<<endl;
    cout<<"NAME OF THE CUSTOMER: "<<name<<endl;
    cout<<"UNIQUE ID: "<<ID<<endl;
    cout<<"ITEM BOUGHT: "<<buy<<endl;
    cout<<"QUANTITY BOUGHT: "<<quantity<<endl;
    cout<<"vat amount: "<<"$"<<vat<<endl;
    cout<<"total cost: "<<"$"<<totalcost<<endl;
    cout<<"total amount paid: "<<"$"<<totalamountpaid<<endl;
    cout<<"balance: "<<"$"<<balance<<endl;
    cout<<"....................................."<<endl;
         cout<<"Thank You For Transacting With Us: "<<endl;
}


    return 0;
}
